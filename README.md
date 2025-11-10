# 🧭 Project: **TaskBoard Pro**

## 📝 Description
**TaskBoard Pro** is a **full‑stack, real‑time task management platform** built with **Laravel 11**, **Vue 3**, and **Vite**.  
It provides a modern architecture with *DDD‑inspired modules*, robust API authentication, real‑time broadcasting, background job processing,  
and a fully typed, minimal core optimized for high‑performance teams and CI/CD environments.

---

## ⚙️ Core Features

- **Realtime Collaboration** — Powered by **Laravel Reverb (WebSocket Server)** and **Laravel Echo**, enabling instant updates across all clients with sub‑3 ms latency.  
- **Modern API Architecture** — Fully RESTful API secured via **Laravel Sanctum**; stateless session flow ready for SPA / mobile integration.  
- **Minimal Laravel 11 Core** — Clean bootstrap structure (`bootstrap/app.php`) using the new fluent API for routing, middleware, exceptions, and service bindings.  
- **Typed Query Builder & Enums** — PHP 8.3 Enums with Laravel’s typed query support deliver precise type safety and cleaner domain logic.  
- **Task Scheduling DSL** — Fluent, cron‑free scheduling (`->weekdays()->between('09:00','17:00')`) for automated reminders, backups, and maintenance tasks.  
- **Process & Queue System** — Use of **Laravel Process API** and rate‑limited jobs ensures safe background execution and high throughput.  
- **SQLite Experimental Mode** — Ultra‑fast integration testing and CI pipelines using in‑memory databases; no external DB dependencies.  
- **Vite‑Powered Frontend** — Lightning‑fast asset builds, ESM‑based imports, and Hot Module Replacement for instant developer feedback.  
- **Tailwind UI – Clean and Adaptive** — Minimalist UI built on Tailwind and DaisyUI components.

---

## 🧩 Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | Vue 3 + Vite 5 + Tailwind CSS |
| **Backend** | Laravel 11 (PHP 8.3), SQLite / Redis |
| **Realtime** | Laravel Reverb + Echo (WebSockets) |
| **API / Auth** | Laravel Sanctum |
| **Testing / CI** | PHPUnit / Pest + GitHub Actions + SQLite In‑Memory |
| **Architecture** | Domain‑Driven Design (DDD‑oriented) |
| **Deployment** | Docker‑ready / GitHub Actions pipeline |

---

## 📦 Key Modules

| Module | Description |
|---------|-------------|
| **Tasks** | CRUD & status tracking with Enum‑backed states (`TODO`, `IN_PROGRESS`, `DONE`) |
| **Teams** | Lightweight workspace management and user assignment |
| **Notifications** | Real‑time push notifications via Reverb |
| **Scheduler** | Automated maintenance and task reminders using the new DSL |
| **Activity Feed** | Stream of user actions rendered live over WebSockets |

---

## 🧠 Highlights

- Built entirely with **Laravel 11 Minimal Skeleton** (no ServiceProviders or config files by default).  
- Fully **Typed PHP 8.3 Codebase** — strict DTOs, Enums, and Value Objects across domains.  
- Integrates **modern DevOps practices**: CI‑ready, stateless, horizontally scalable.  
- Designed for **enterprise teams** requiring real‑time collaboration and consistent performance.

---

## 👤 Author

**Amid Ahmadiafshar**  
**Senior Full‑Stack Developer** — PHP / Laravel / Vue 3 / Type‑Safe Systems  
Iran · [LinkedIn / Portfolio links if needed]

---

## 🩶 Short GitHub Description
> Full‑stack, real‑time task management app built with Laravel 11 & Vue 3 — Vite, Reverb, Type‑Safe Core, DDD Structure.

---

## 🪪 License
This project is licensed under the **Creative Commons Attribution‑NonCommercial 4.0 International (CC BY‑NC 4.0)** license.  
You may view, fork, and modify the code for personal or educational use,  
but **commercial use, resale, or proprietary redistribution are strictly prohibited**.  
© 2025 Amid Ahmadiafshar — All rights reserved.
