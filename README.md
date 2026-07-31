# Hi, I'm Shivam Patel

Computer Engineering Co-op student at the University of Guelph building software where **systems thinking, reliability, and practical engineering** matter.

My portfolio spans backend services, operating-system observability, computer architecture, safety-oriented embedded control, and object-oriented application design. I enjoy taking a small working prototype and pushing it toward a clearer architecture, richer domain model, stronger validation, better testability, and more useful tooling.

## Featured engineering projects

### [CampusFlow API](https://github.com/shiv814/campusflow-api)

[![CampusFlow quality](https://github.com/shiv814/campusflow-api/actions/workflows/test.yml/badge.svg)](https://github.com/shiv814/campusflow-api/actions/workflows/test.yml)

A dependency-free Python and SQLite academic-planning platform.

- searchable course catalogue with departments, delivery modes, capacities, prerequisites, and meeting schedules
- complete plan lifecycle with ordered courses, grades, notes, status, credit totals, and progress measurement
- prerequisite-order, timetable-conflict, and credit-overload validation
- eligible-course recommendations, analytics, CSV export, pagination, CORS, and request IDs
- backward-compatible schema upgrades and end-to-end HTTP tests

**Engineering focus:** API design, persistence, domain validation, database migrations, integration testing, analytics.

---

### [SystemSight Monitor](https://github.com/shiv814/systemsight-monitor)

[![SystemSight quality](https://github.com/shiv814/systemsight-monitor/actions/workflows/test.yml/badge.svg)](https://github.com/shiv814/systemsight-monitor/actions/workflows/test.yml)

A cross-platform Python observability toolkit built with `psutil`.

- CPU, load, memory, swap, disk, network, temperature, uptime, and process collection
- warning/critical thresholds, health scoring, and remediation recommendations
- bounded metric history with trends, JSON/CSV export, and z-score anomaly detection
- stateful alert lifecycle: open, escalate, remind, and recover
- CLI snapshot/watch/report modes plus JSON and Prometheus-compatible HTTP endpoints

**Engineering focus:** observability, time-series analysis, alert state machines, portable system programming, test doubles.

---

### [CacheCraft Simulator](https://github.com/shiv814/cachecraft-simulator)

[![CacheCraft build](https://github.com/shiv814/cachecraft-simulator/actions/workflows/build.yml/badge.svg)](https://github.com/shiv814/cachecraft-simulator/actions/workflows/build.yml)

A dependency-free C++17 cache-architecture simulator and experiment CLI.

- configurable capacity, block size, associativity, latency, and deterministic random seed
- LRU, FIFO, and random replacement policies
- write-back/write-through and write-allocate/no-write-allocate strategies
- typed read/write/instruction traces with multi-block access expansion
- compulsory, conflict, and capacity miss classification using a fully associative shadow cache
- dirty lines, writebacks, memory traffic, AMAT, JSON output, policy comparison, set-state inspection, and two-level hierarchy support

**Engineering focus:** computer architecture, memory systems, modern C++, deterministic simulation, measurement.

---

### [Smart Mobility Controller](https://github.com/shiv814/smart-mobility-controller)

[![Mobility build](https://github.com/shiv814/smart-mobility-controller/actions/workflows/build.yml/badge.svg)](https://github.com/shiv814/smart-mobility-controller/actions/workflows/build.yml)

A safety-oriented C++17 control core and Arduino integration prototype for powered mobility.

- discrete commands and normalized differential-drive joystick mixing
- Eco, Normal, and Sport modes with separate acceleration and deceleration ramps
- braking-before-reversal, watchdog timeout, obstacle slowdown/stop, and battery derating
- emergency-stop and sensor-fault latching, seat interlock, safe fault clearing, and event history
- detailed telemetry and deterministic CSV scenario simulation
- host-tested portable controller plus an Arduino I/O integration sketch

**Engineering focus:** embedded control, state machines, fail-safe behaviour, hardware/software boundaries, scenario testing.

> Portfolio prototype only; it is not certified medical-device software.

---

### [University Management System](https://github.com/shiv814/university-management-system)

[![University system build](https://github.com/shiv814/university-management-system/actions/workflows/build.yml/badge.svg)](https://github.com/shiv814/university-management-system/actions/workflows/build.yml)

A dependency-free Java 17 academic-record and enrollment application.

- validated students, courses, credits, terms, capacities, and prerequisite sets
- enrolled, waitlisted, completed, and dropped lifecycle states
- FIFO waitlists with automatic seat promotion
- prerequisite enforcement, transcripts, earned/attempted credits, and weighted GPA
- course recommendations, search, dashboard analytics, and quoted interactive commands
- correctly escaped CSV persistence with complete save/load restoration

**Engineering focus:** object-oriented domain modeling, immutable records, collection design, persistence, lifecycle invariants.

## Portfolio verification

Every project includes automated tests and a GitHub Actions workflow. The Python projects run across multiple supported Python versions, the C++ projects build in Debug and Release configurations across Linux, Windows, and macOS, and the Java project compiles and tests on Java 17 and 21 across all three operating systems.

## Technical toolkit

| Area | Technologies |
|---|---|
| Languages | Python, C++, Java, C, SQL, HTML/CSS |
| Backend and data | REST/HTTP, JSON, SQLite, CSV persistence, analytics |
| Systems | Linux concepts, process/system metrics, cache architecture, memory behaviour |
| Embedded | Arduino, differential motor control, watchdogs, sensor interlocks, telemetry |
| Build and quality | Git, GitHub Actions, CMake, Make, pytest, deterministic host tests |
| Design | State machines, immutable domain records, layered architecture, validation, fault handling |

## How I approach engineering work

1. Define the domain rules and failure cases before adding interfaces.
2. Separate hardware, transport, persistence, and analysis concerns where possible.
3. Make unsafe or invalid states explicit through types, validation, and state transitions.
4. Build deterministic tests around the most important behaviours and edge cases.
5. Document tradeoffs, usage, architecture, and realistic next steps—not only the happy path.

## Current interests

Embedded systems, backend engineering, operating-system tooling, computer architecture, observability, reliability, simulation, and hardware-software integration.

## Contact

- GitHub: [@shiv814](https://github.com/shiv814)
- Email: `pateshiv16@gmail.com`
