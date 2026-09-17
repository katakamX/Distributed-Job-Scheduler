# Distributed Job Scheduler

## Overview
A simple distributed job scheduler built from scratch as an internship-level systems project. It explores how clients submit jobs, how a scheduler queues and assigns them, and how multiple workers execute jobs concurrently while the system detects and recovers from worker failures.

## Goals
Planned capabilities (not implemented yet):
- Job submission
- Job queue
- Scheduler
- Multiple workers
- Networking
- Concurrent execution
- Worker health checking
- Failed-worker detection
- Job retry
- Performance measurement

## Basic Architecture

```
Client
  ↓
Scheduler
  ↓
Job Queue
  ↓
Worker 1
Worker 2
Worker 3
  ↓
Job Execution
  ↓
Result
```

## Planned Components

- **Client** — submits jobs to the scheduler.
- **Scheduler** — receives jobs and assigns them to available workers.
- **Job Queue** — holds pending jobs until a worker is ready.
- **Worker** — executes jobs and returns results.
- **Health/Heartbeat mechanism** — tracks worker liveness and detects failures.

## Technologies

- C++
- Linux
- Networking
- Multithreading
- Distributed systems concepts
- Git

Docker may be considered later, but is not part of the initial implementation.

## Learning Objectives

- Processes vs threads
- Multithreading
- Synchronization
- Networking
- Client-server communication
- Job scheduling
- Concurrency
- Fault tolerance
- Distributed systems

## Development Plan

- Phase 1 — Project foundation
- Phase 2 — Job representation
- Phase 3 — Basic scheduler
- Phase 4 — Worker
- Phase 5 — Client-worker/scheduler communication
- Phase 6 — Multiple workers
- Phase 7 — Heartbeats and failure detection
- Phase 8 — Job retry
- Phase 9 — Performance testing
- Phase 10 — Documentation

Phases are not implemented yet.

## Current Status

Initial project scaffold only. No functionality has been implemented yet.

## Project Philosophy

Build one component at a time and understand every component before moving forward.
