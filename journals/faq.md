### How can I get all the resources for a specific journal in a NS
```
kubectl api-resources --verbs=list --namespaced -o name | xargs -n 1 kubectl get -n longhorn-system
```

### How to forcefully delete a NS, but make sure no dangling part
```NS=`kubectl get ns |grep Terminating | awk 'NR==1 {print $1}'` && kubectl get namespace "$NS" -o json   | tr -d "\n" | sed "s/\"finalizers\": \[[^]]\+\]/\"finalizers\": []/"   | kubectl replace --raw /api/v1/namespaces/$NS/finalize -f -```
