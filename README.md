# CI4 Admin UI Standard

Production-grade standardized admin panel architecture for CodeIgniter 4 projects.

This repository defines a consistent admin UI system for scalable business platforms such as Classified Systems, MLM Platforms, SaaS Applications, CRM, ERP, HRMS, and Subscription-based products.

The goal is simple:

**No legacy admin HTML. No inconsistent layouts. No random UI decisions.**

Only clean, maintainable, professional admin architecture.

---

# Core Standard

Every admin page must follow a unified structure:

* `admin_layout` extend
* `page-header-card`
* Standard breadcrumbs
* Actions row below header
* `modern-wrapper` / `modern-wrapper narrow`
* `content-card` sections
* Standard notifications include
* Standard filter sections
* Modern table components
* Responsive form sections
* Right sidebar support where needed

This ensures consistency across all modules.

---

# Standard Table Layout

All list pages use:

* Page header card
* Stats cards overview
* Filter section
* Content card
* Modern responsive table

No legacy table layouts are allowed.

---

# Standard Form Layout

All form pages use:

* Header (title + subtitle only)
* Breadcrumb + actions row
* Main content section
* Right sidebar (optional)
* Structured content cards
* No buttons inside page header

This improves workflow clarity and scalability.

---

# Stats Cards Standard

Uses:

```html
stats-grid
stat-card
stat-icon
stat-label
stat-value
```

Used for dashboard summaries and module overview metrics.

---

# Ideal Use Cases

* Classified Platforms
* MLM Systems
* SaaS Platforms
* CRM / ERP
* HRMS
* Subscription Systems
* Payment Systems
* Admin-heavy business applications

---

# Why This Standard Matters

Most projects fail because admin systems become inconsistent over time.

This standard solves:

* poor maintainability
* inconsistent UI
* developer confusion
* slow onboarding
* weak scalability
* technical debt from legacy pages

It creates a system that scales cleanly.

---

# Tech Stack

* CodeIgniter 4
* PHP
* MySQL
* Bootstrap 4/5
* Twig / Blade compatible structure
* Production-ready admin architecture

---

# Positioning

This is not a template.

This is a professional admin UI system standard designed for serious production platforms.

It helps teams build faster, maintain better, and scale safely.

---

# Website

[https://vayrixlabs.com/](https://vayrixlabs.com/)

---

# Author

CodeIgniter 4 Business Systems Specialist

Focus Areas:

* Classified Platforms
* MLM Systems
* SaaS / CRM
* Admin Dashboards
* Subscription Logic
* Payment Architecture
* ROI & Commission Systems

---

# Future Modules

Planned additions:

* Reusable CRUD standards
* Payment UI standards
* Subscription module standards
* Gateway integration patterns
* Reporting dashboard standards
* User panel UI standards
* Frontend + Twig standards

---

Built for production.
Not for demos.
