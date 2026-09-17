# Architecture

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

## Components

- **Client** — submits jobs to the scheduler.
- **Scheduler** — receives jobs and assigns them to available workers.
- **Job Queue** — holds pending jobs until a worker is ready.
- **Worker** — executes jobs and returns results.
- **Health/Heartbeat mechanism** — tracks worker liveness and detects failures.
