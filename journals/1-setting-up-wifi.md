
# Setting Up Wifi

The Linux Ubuntu server does not come with wifi,  
hence packages and modules does not exist. You will need to install a network manager to enable wifi.

#### Steps To Enable Network Manager.
- Check the linux distribution using the command:
```bash  
lsb_release -a
```  
This will include the codename of the distribution which is equivalent to the distribution name.

- Download the network manager with its dependencies from the Ubuntu repository.  
  -- [Network Manager](https://ubuntu.pkgs.org/24.04/ubuntu-main-amd64/network-manager_1.46.0-1ubuntu2_amd64.deb.html)
  -- [Libteamctl](https://pkgs.org/download/libteamdctl0)
  -- [Libnmo](https://pkgs.org/download/libnm0)`
  -- [Libndp](https://pkgs.org/download/libndp0)
  --  [LibBluetooth3](https://pkgs.org/download/libbluetooth3)

- Copy the downloaded dependencies into a flashDrive
- Mount the Flash drive to the linux server and validate the port

```bash  
lblk
sudo mount /dev/<verify the port name in lblk> /mnt/
``` 
- cd into /mnt and install the package and alson verify the version
```bash
dpkg -i *
nmcli --version
```
After all the package are installed set up wifi connection using the ui, follow all the instructions and add a connection.
```bash
nmtui
```
upon adding a connection validate the wifi configurations in the network manager config file.
```bash
sudo vi /etc/netplan/90-NM-9317783d-4c69-4d7d-b2cc-b2f9a983397f.yaml
```
- Apply the changes.
```bash
sudo netplan --debug apply
```
- Verify the Wifi connection againt the UUID of the connection added
 ```bash
nmcli c
```
