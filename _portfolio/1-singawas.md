---
title: "SiNgawas"
excerpt: "An internal exam supervision management system for Fasilkom UI, featuring automated scheduling, role-based access, and CI/CD deployment."
collection: portfolio
---

SiNgawas is a full-stack web platform designed to manage exam supervision operations at the Faculty of Computer Science, Universitas Indonesia. It streamlines the entire process from exam scheduling, supervisor assignment, to room management, through an integrated system.

The platform consists of a **React-based frontend** (built with TypeScript, Vite, and Tailwind) and a **Django-based backend** (using Django REST Framework and SQLite). SiNgawas supports role-based access control, authentication via SSO UI, and CSV import for scheduling. Users include administrators, lecturers, and assistants.

Key features include:

- **Role-based access** and SSO integration for secure user management
- **Dynamic scheduling** of exam supervisors with auto-plotting powered by Celery
- **Admin interface** and public-facing web dashboard
- **End-to-end CI/CD pipelines** for both frontend and backend using GitLab
- **Monitoring and observability** with Sentry integration
- **API documentation** via Swagger and Postman, following OpenAPI 3.0
- **Deployment via Docker** on a VM managed through Kawung (internal Fasilkom infrastructure)

The system is deployed in a **production environment** at:  
[https://singawas.cs.ui.ac.id](https://singawas.cs.ui.ac.id)  
⚠️ *Access is restricted to members of Fasilkom UI only.*

A recorded demo of the system is available on YouTube:  
[Watch the video](https://www.youtube.com/watch?v=AGJVNEo5Vuc)
