# Intensive 2-Week GoLang Curriculum for DevOps Engineers

---

## General Resources
- [A Tour of Go](https://tour.golang.org/welcome/1)
- [Go Programming Language Book (gopl.io)](https://www.gopl.io/)
- [Go Official Documentation](https://golang.org/doc/)
- [Golang Full Course (freeCodeCamp)](https://www.youtube.com/watch?v=yyUHQIec83I)
- [Exercism Go Track](https://exercism.org/tracks/go)

---

# Week 1 — Master the Basics

## Day 1
**Focus:** Setup + Basic Syntax

**Tasks:**
- Install Go, set up environment (VSCode + Go plugin)
- Understand `$GOPATH`, `go.mod`, Modules
- Complete the first 3 sections of [A Tour of Go](https://tour.golang.org/welcome/1)
- Write 3 tiny programs:
    - Fibonacci function
    - String reversal
    - Simple CLI greeting program

**Reference:**
- [A Tour of Go - Basics](https://tour.golang.org/welcome/1)

---

## Day 2
**Focus:** Types (structs, slices, maps)

**Tasks:**
- Deep dive into types
- Write a "contacts book" using maps
- Write duplicate finder in slices

**Reference:**
- [A Tour of Go - Methods and Interfaces](https://tour.golang.org/methods/1)

---

## Day 3
**Focus:** Interfaces and Embedding

**Tasks:**
- Create shape interface with Circle/Rectangle structs
- Implement a small "storage engine" with multiple backends

**Reference:**
- [A Tour of Go - Interfaces](https://tour.golang.org/methods/9)

---

## Day 4
**Focus:** Error Handling

**Tasks:**
- Learn `error` type and custom errors
- Write a file parser with graceful error handling

**Reference:**
- [Go Blog - Error handling and Go](https://blog.golang.org/error-handling-and-go)

---

## Day 5
**Focus:** Packages and Modules

**Tasks:**
- Create multi-package apps
- Write a CLI calculator app

**Reference:**
- [Go Modules - Official Guide](https://blog.golang.org/using-go-modules)

---

## Day 6
**Focus:** Testing and Benchmarking

**Tasks:**
- Learn to write `_test.go` files
- Table-driven tests
- Write benchmarks

**Reference:**
- [Testing in Go](https://golang.org/pkg/testing/)

---

## Day 7
**Focus:** Web Server Basics

**Tasks:**
- Build a simple REST API using `net/http`
- Mini in-memory To-Do app (CRUD tasks)

**Reference:**
- [Building Web Servers in Go](https://golang.org/doc/articles/wiki/)

---

# Week 2 — Real Engineering Skills

## Day 8
**Focus:** Concurrency Basics

**Tasks:**
- Learn goroutines and channels
- Launch 5 goroutines that print their ID

**Reference:**
- [Concurrency in Go - Tour Section](https://tour.golang.org/concurrency/1)

---

## Day 9
**Focus:** Select, Mutex, WaitGroups

**Tasks:**
- Learn `select` statement
- Scrape 5 websites concurrently

**Reference:**
- [Go Blog - Share by Communicating](https://blog.golang.org/share-memory-by-communicating)

---

## Day 10
**Focus:** Context Package

**Tasks:**
- Learn how to use `context.Context`
- HTTP server with 2s timeout per request

**Reference:**
- [Go Context Docs](https://golang.org/pkg/context/)

---

## Day 11
**Focus:** Structuring Bigger Apps

**Tasks:**
- Clean architecture practices
- Refactor To-Do app to layered structure

**Reference:**
- [Practical Go - Application Structure](https://golangbot.com/packages/)

---

## Day 12
**Focus:** Building CLI Tools

**Tasks:**
- Learn `cobra` framework
- Build a CLI to interact with To-Do server

**Reference:**
- [Cobra CLI Documentation](https://github.com/spf13/cobra)

---

## Day 13
**Focus:** Prometheus Exporter or Kubernetes Operator Basics

**Tasks:**
- Build a simple HTTP Prometheus metrics exporter
- OR
- Learn basics of `kubebuilder` and building an Operator

**Reference:**
- [Prometheus Exporter Example](https://prometheus.io/docs/guides/go-application/)
- [Kubebuilder Quick Start](https://book.kubebuilder.io/quick-start.html)

---

## Day 14
**Focus:** Final Mini-Project

**Option 1:** URL Monitoring Service
- Monitor uptime for a list of URLs
- Record metrics, expose on `/metrics`
- Use concurrency + channels

**Option 2:** Mini Kubernetes Pod Simulator
- Simulate pods with lifecycle events
- CLI to create/list/delete pods

**Reference:**
- Combine all skills from previous days

---

# 🔍 Daily Log Template (copy for each day)

```markdown
## Day X - [Topic]

### Concepts Studied
-

### Exercises Completed
-

### Problems/Challenges
-

### Notes
-

### Confidence Level (1-10)
-
```

---
