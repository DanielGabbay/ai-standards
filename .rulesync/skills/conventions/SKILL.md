---
name: project-conventions
description: Specific coding conventions for Angular 21 and .NET 8.
---

# Angular Conventions
- **Standalone Components:** Exclusive use.
- **Dependency Injection:** Use `inject()` instead of constructor injection.
- **RxJS vs Signals:** Prefer Signals for state and binding. Use RxJS only for complex streams (debounce/switchMap) and convert to signals via `toSignal`.

# .NET Conventions
- **API Design:** Use Async/Await consistently.
- **DTOs:** Use `record` types for DTOs.
- **Logging:** Use structured logging (Serilog).
