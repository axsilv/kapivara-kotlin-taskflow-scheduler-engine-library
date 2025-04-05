# Kapivara - Taskflow Scheduler Engine Library

Kapivara is a lightweight, coroutine-based job scheduler for Kotlin that integrates seamlessly with a rule engine DSL. Ideal for microservices, event-driven applications, and automation tools where you want to decouple scheduling logic from business rules.

---

## 🚀 Features

- 📆 Schedule jobs with fixed intervals or delays
- 🧠 Evaluate complex business rules using a simple DSL
- 🔄 Integrate both to build powerful decision-driven task automation
- 🔧 Coroutine-based, non-blocking execution
- 🧪 Clock injection for deterministic testing

---

## 📦 Modules

### `core`
- Contains the clock abstraction (`ClockProvider`) for testable and consistent time handling.

### `scheduler`
- Defines the scheduler system with job definitions, delay/interval support, and coroutine-based execution.

### `ruleengine`
- Provides a mini rule engine DSL that allows defining conditional actions in a clean and testable way.

---

## 🔧 Example
TBD
