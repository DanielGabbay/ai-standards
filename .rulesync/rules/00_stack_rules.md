---
root: true
---

# Global Tech Stack & Architecture

## Core Technologies
- **Frontend:** Angular 21 (Nx Monorepo), TypeScript (Strict Mode).
- **Backend:** .NET 8, C#, Entity Framework Core.
- **State Management:** SignalStory (Global state), Angular Signals (Local state).
- **UI Libs:** PrimeNG, TailwindCSS.

## Key Architecture Principles
1.  **Modern Angular:** Usage of `input()`, `output()`, and `viewChild()` signals is mandatory. Avoid Zone.js patterns.
2.  **Performance:** `ChangeDetectionStrategy.OnPush` is required for all components.
3.  **Backend:** Clean Architecture. Controllers are thin; logic resides in Services/Handlers.
4.  **Database:** EF Core with Migrations. No tracking queries (`AsNoTracking`) for read operations.
