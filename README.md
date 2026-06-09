# Day 4 — Linux Searching, Filters & Processes 🚀

This repository contains my Linux practice focused on searching, filtering, log analysis, and process management.

## Topics Covered

### Searching & Filters

- Pipes (`|`)
- grep
- find
- locate
- which
- Log searching practice

### Process Management

- Linux processes
- Background jobs
- Process monitoring
- Process termination

---

## Searching Commands

Search inside files:

```bash
grep "error" app.log
```

Recursive search:

```bash
grep -r "main" .
```

Find files:

```bash
find . -name "*.txt"
```

Locate files:

```bash
locate file.txt
```

Find command location:

```bash
which python
```

Pipe examples:

```bash
ls | grep ".txt"
```

```bash
grep "ERROR" server.log | tail -5
```

---

## Process Commands

Show running processes:

```bash
ps
```

Show all processes:

```bash
ps aux
```

Live process monitor:

```bash
top
```

Enhanced process monitor:

```bash
htop
```

Modern system monitor:

```bash
btop
```

Run process in background:

```bash
sleep 60 &
```

Show background jobs:

```bash
jobs
```

Kill process by PID:

```bash
kill PID
```

Force kill process:

```bash
kill -9 PID
```

---

## Log Search Practice

```bash
grep "ERROR" server.log
```

```bash
grep -i "warning" server.log
```

```bash
grep "fail" server.log | tail -10
```

---

## Learning Goal

Understand how Linux searches files, filters output, monitors processes, and manages running programs using terminal commands.

---
Learning Linux one command at a time 💻
