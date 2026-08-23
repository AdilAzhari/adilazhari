# 👋 Hi, I'm Adil Omer

Backend Software Engineer based in Malaysia 🇲🇾

I build reliable backend systems using **PHP and Laravel**, with a focus on clean architecture, domain-driven design, database consistency, and maintainable software design.

I enjoy solving complex backend problems involving business rules, transactional workflows, asynchronous processing, API integrations, and system reliability.

---

## 🧠 Engineering Focus

I am most interested in building systems where correctness and maintainability matter.

My main areas of focus:

- Designing Laravel applications with clear domain boundaries and separation of concerns
- Applying **Domain-Driven Design (DDD)** principles to model complex business logic
- Building reliable transactional workflows involving payments, orders, and external integrations
- Designing REST APIs with predictable contracts and maintainable structures
- Improving application performance through database optimization, indexing, and caching
- Implementing asynchronous workflows using queues and background workers
- Writing automated tests using **PestPHP / PHPUnit**
- Building modern interfaces with **Vue.js, Inertia.js, and Livewire**

---

# 📦 Open Source Packages

I maintain a small set of focused, single-purpose Laravel packages rather than one large toolkit — each solves one problem well and ships with a full automated quality pipeline (PestPHP, PHPStan, Rector, Laravel Pint).

## [laravel-trace](https://github.com/AdilAzhari/laravel-trace)

Application-level tracing for Laravel applications — request, query, and event-level spans for understanding what an application actually did during a request.

## [laravel-idempotency](https://github.com/AdilAzhari/laravel-idempotency)

Prevents duplicate request execution using idempotency keys. Built for protecting write operations such as payments, orders, and external API calls where retrying the same request can create unwanted side effects.

- Middleware-based idempotency handling
- Request fingerprinting using SHA-256
- Response replay for repeated requests
- Conflict detection for reused keys with different requests
- Cache-based locking to prevent concurrent execution
- Extensible contracts for storage, locking, and fingerprinting

## [laravel-auto-slug](https://github.com/AdilAzhari/laravel-auto-slug)

Automatic slug generation for Eloquent models, published on [Packagist](https://packagist.org/packages/adilazhari/laravel-auto-slug).

---

# 🌱 Open Source Contributions

Beyond my own packages, I contribute fixes upstream to packages I use:

- **[laravel/socialite#790](https://github.com/laravel/socialite/pull/790)** — traced and documented an undocumented config requirement in `SocialiteManager::buildProvider()`
- **[santifer/career-ops#3199](https://github.com/santifer/career-ops/pull/3199)** (merged) and **[#3217](https://github.com/santifer/career-ops/pull/3217)** — hardened CLI flag validation against silent typo/argument bugs in an open-source job-search tracking tool

---

# 🚀 Featured Projects

## [Madarik — School Management System](https://github.com/AdilAzhari/madarik)

A multi-tenant Laravel SaaS platform for academic workflows, student records, and administrative operations, with domain isolation and RBAC.

### Highlights

- Designed backend workflows for student management, grading, and reporting
- Implemented role-based access control for different user groups
- Used Redis queues for background processing tasks
- Built interactive dashboards using Laravel, Vue.js, and Inertia.js
- Focused on maintainable domain logic and scalable application structure

---

## Modular E-Commerce System

A Laravel application focused on applying software design principles to complex business workflows.

### Highlights

- Structured application logic around clear business domains
- Applied Domain-Driven Design concepts such as:
  - Value Objects
  - Domain Events
  - Business rule isolation
- Designed multi-tenant architecture with automated tenant scoping
- Implemented event-driven workflows between business modules
- Built administrative interfaces using Filament

---

# 📚 Currently Learning

## Backend Architecture

Exploring deeper concepts around:

- Domain-Driven Design
- Event-driven architectures
- CQRS patterns
- Distributed systems fundamentals
- Database consistency and transaction design

---

## Payments & Reliability

Learning how to build resilient payment workflows involving:

- Webhook handling
- Idempotent processing
- Payment reconciliation
- Failure recovery strategies

---

## Real-Time Applications

Exploring:

- Laravel Reverb
- WebSocket-based communication
- Real-time dashboards
- Event broadcasting patterns

---

# 🛠️ Technical Stack

### Backend

- PHP 8.x
- Laravel
- REST APIs
- MySQL
- Redis
- Queues
- Background processing

### Architecture & Design

- Domain-Driven Design
- SOLID Principles
- Clean Architecture
- Event-Driven Architecture
- Design Patterns

### Frontend

- Vue.js 3
- Inertia.js
- Livewire
- Alpine.js
- Tailwind CSS

### Testing & Quality

- PestPHP
- PHPUnit
- PHPStan
- Rector
- Laravel Pint

### Tools & Infrastructure

- Git
- GitHub Actions
- Docker
- Composer
- NPM

### Integrations

- Stripe Payments
- Webhooks
- OAuth
- API Documentation

---

# 🤝 Open To Collaboration

I am interested in collaborating on projects involving:

- Laravel backend development
- API design and integrations
- Payment and transactional systems
- Real-time applications
- Database optimization
- Software architecture improvements

---

# 💬 Topics I Enjoy Discussing

- Laravel application architecture
- Designing maintainable backend systems
- Database transactions and consistency
- Domain-driven design
- Testing strategies
- API design
- Open-source package development

---

# ⚡ Engineering Philosophy

I value **predictability over cleverness** and **clarity over unnecessary abstraction**.

Good software is not only about making code work. It is about creating systems that remain understandable, adaptable, and reliable as they grow.

I enjoy refactoring complex systems because it reveals better boundaries, clearer responsibilities, and stronger design decisions.

---

# 🌐 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adil-omer-8aab21167/)

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:adilazhariosman@gmail.com)

---

# 📊 GitHub Activity

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=AdilAzhari&show_icons=true&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=AdilAzhari&layout=compact&hide_border=true)
