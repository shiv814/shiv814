# Portfolio Engineering Matrix

| Project | Core problem | Strongest engineering signal | Verification |
|---|---|---|---|
| CampusFlow | academic planning over dependency and schedule constraints | API boundaries, graph algorithms, optimization, SQLite | Python 3.10–3.13 CI, domain/API/algorithm tests, demo artifacts |
| SystemSight | turn raw host metrics into operational signals | observability, stateful alerting, forecasting, SLOs | Linux/Windows/macOS CI, deterministic metric doubles, offline report demo |
| CacheCraft | compare cache designs against workloads | computer architecture, measurement, modern C++ | Debug/Release on three OSes, experiment smoke tests, analysis tests |
| Smart Mobility | fail safe around motion commands and unreliable inputs | embedded state machines, safety boundaries, hardware/software thinking | Debug/Release on three OSes, scenario tests, hazard + validation docs |
| University System | preserve academic-record invariants under lifecycle changes | OOP domain modeling, data integrity, planning algorithms | Java 17/21 on three OSes, original + advanced test runners, HTML demo |

## Shared engineering themes

1. **Explicit models** — turn ambiguous requirements into typed data and state transitions.
2. **Determinism** — make important behavior reproducible enough to test in CI.
3. **Boundaries** — separate transport, state mutation, analytics, persistence and reporting.
4. **Failure behavior** — test invalid input, stale state, conflicts and recovery paths rather than only happy paths.
5. **Communication** — architecture diagrams and trade-off notes explain why the code is structured the way it is.
