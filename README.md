# Hi, I'm Adil Omer 👋

Backend Software Engineer based in Malaysia 🇲🇾, building reliable Laravel systems — clean architecture, domain-driven design, and software that stays maintainable as it grows.

<p>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel">
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue.js">
  <img src="https://img.shields.io/badge/Inertia.js-9553E9?style=flat-square&logo=inertia&logoColor=white" alt="Inertia.js">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
</p>

---

## Open Source

I maintain a small set of focused, single-purpose Laravel packages rather than one large toolkit — each solves one problem well and ships with a full automated quality pipeline (PestPHP, PHPStan, Rector, Laravel Pint).

| Package | Description |
|---|---|
| **[laravel-trace](https://github.com/AdilAzhari/laravel-trace)** | Application-level tracing — request, query, and event-level spans for understanding what an application actually did during a request. |
| **[laravel-idempotency](https://github.com/AdilAzhari/laravel-idempotency)** | Prevents duplicate request execution via idempotency keys: request fingerprinting, response replay, conflict detection, and cache-based locking — for payments, orders, and external API calls where a retried request can't be allowed to double-execute. |
| **[laravel-auto-slug](https://github.com/AdilAzhari/laravel-auto-slug)** | Automatic slug generation for Eloquent models. Published on [Packagist](https://packagist.org/packages/adilazhari/laravel-auto-slug). |

**Upstream contributions** — fixes to packages I use, not just my own:

- **[laravel/socialite#790](https://github.com/laravel/socialite/pull/790)** — traced and documented an undocumented config requirement in `SocialiteManager::buildProvider()`
- **[santifer/career-ops#3199](https://github.com/santifer/career-ops/pull/3199)** (merged) & **[#3217](https://github.com/santifer/career-ops/pull/3217)** — hardened CLI flag validation against silent typo/argument bugs

---

## Featured Projects

### Madarik — School Management System

A multi-tenant Laravel SaaS platform for academic workflows, student records, and administrative operations, with domain isolation and RBAC. Sold as a commercial product to schools, so the source is closed — the live demo is the best way to explore it.

🔗 **Live demo:** [madarik.aljebal-albeedos.com](https://madarik.aljebal-albeedos.com)

<details>
<summary><strong>Demo credentials</strong> (click to expand — same password for every role)</summary>
<br>

| Role | Email |
|---|---|
| Developer | `developer@madarik.test` |
| Principal | `principal@madarik.test` |
| Admin | `admin@madarik.test` |
| Parent | `parent@madarik.test` |

**Password (all roles):** `o/\Efy1vP0k?aOgM`

</details>

- Backend workflows for student management, grading, and reporting
- Role-based access control across distinct user groups (developer, principal, admin, parent)
- Redis-queued background processing, dashboards built with Laravel, Vue.js, and Inertia.js

### Modular E-Commerce System

A Laravel application applying DDD to complex, multi-tenant business workflows.

- Business logic structured around clear domains, using value objects, domain events, and isolated business rules
- Multi-tenant architecture with automated tenant scoping and event-driven workflows between modules
- Administrative interfaces built with Filament

---

## Connect

<p>
  <a href="https://www.linkedin.com/in/adil-omer-8aab21167/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:adilazhariosman@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=AdilAzhari&show_icons=true&hide_border=true&theme=default" alt="GitHub Stats" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AdilAzhari&layout=compact&hide_border=true&theme=default" alt="Top Languages" height="165">
</p>
