# Umar Maulana Zakaria

**Junior Fullstack Developer | Web & Mobile Development**

I build web and mobile applications with a focus on clear user experiences, reliable backend workflows, and well-structured data. My current stack includes **TypeScript, React, React Native, Node.js, Express, Prisma, and PostgreSQL**.

I'm developing my skills through hands-on projects that connect frontend, backend, database, and third-party integrations.

## Featured Project — BARBER BARBAR

**Three applications. One backend. One connected barbershop workflow.**

An integrated barbershop management system built for an internship project and fullstack portfolio: **Admin Web**, **React Native Staff Minimal V3**, and **Customer Web mobile-first**.

[![Current BARBER BARBAR Admin dashboard](https://raw.githubusercontent.com/umarmaulanazakaria/barberbarbar/main/docs/showcase/dashboard.jpg)](https://github.com/umarmaulanazakaria/barberbarbar/tree/main)

*Actual application UI captured from the current main source on 18 October 2026, with synthetic intercepted API responses. These screenshots are not evidence of real payments or live customer data.*

### A look inside

| Admin operations | Customer Web · desktop |
| --- | --- |
| [![Membership management with synthetic data](https://raw.githubusercontent.com/umarmaulanazakaria/barberbarbar/main/docs/showcase/membership.jpg)](https://github.com/umarmaulanazakaria/barberbarbar/tree/main) | [![Customer Web desktop homepage](https://raw.githubusercontent.com/umarmaulanazakaria/barberbarbar-customer/main/docs/showcase/hero.jpg)](https://github.com/umarmaulanazakaria/barberbarbar-customer/tree/main) |

| Customer Web · mobile-first booking | Customer Web · online payment screen |
| --- | --- |
| <a href="https://github.com/umarmaulanazakaria/barberbarbar-customer/tree/main"><img src="https://raw.githubusercontent.com/umarmaulanazakaria/barberbarbar-customer/main/docs/showcase/pilih-layanan.jpg" alt="Real Customer Web service selection at mobile viewport" width="300" /></a> | <a href="https://github.com/umarmaulanazakaria/barberbarbar-customer/tree/main"><img src="https://raw.githubusercontent.com/umarmaulanazakaria/barberbarbar-customer/main/docs/showcase/pembayaran.jpg" alt="Real Customer Web DP screen with synthetic data, no provider transaction" width="300" /></a> |

**Staff native gallery is pending:** Beranda, Pesanan, Walk-in, Riwayat and Profil require capture from an actual Android device/emulator. No native device or AVD was available; Web images are not presented as Android evidence. [Capture checklist](https://github.com/umarmaulanazakaria/barberbarbar-mobile/blob/main/docs/screenshots/README.md).

### Three applications, one backend

| Application | Purpose | Repository |
| --- | --- | --- |
| **Admin Web & Backend** | Dashboard, Membership, customers, service operations, payments, reports and shared API. | [Explore main](https://github.com/umarmaulanazakaria/barberbarbar/tree/main) |
| **React Native Staff** | Minimal V3 workflows for arrivals, walk-ins, service progress, cashier operations and history. | [Explore main](https://github.com/umarmaulanazakaria/barberbarbar-mobile/tree/main) |
| **Customer Web mobile-first** | Browser-based catalogue, guest booking, Member eligibility, online DP and private tracking. | [Explore main](https://github.com/umarmaulanazakaria/barberbarbar-customer/tree/main) |

### Engineering highlights

- Shared **Express + Prisma + PostgreSQL** backend and transactional business rules.
- Guest bookings with 45-minute slots; regular bookings use 50% DP and a 15-minute deadline.
- Membership eligibility checked by the backend, with physical member-card/KTP verification in store; no KTP photo or NIK storage.
- Connected booking and walk-in lifecycle, final barber assignment, outstanding balance and final invoice.
- Midtrans Sandbox integration with server-side signature/status verification and idempotent payment handling; callbacks alone do not mark a booking paid.
- Socket.IO signals trigger REST refetches; the backend remains authoritative for price and status.

**Evidence and limits:** main finalization passed builds/TypeScript, 14 backend fixture/mock suites, the Customer UI suite across eight viewports, and Staff Android/Hermes export. Screenshot capture used synthetic API responses without touching a database or payment provider. Native-device, printer and fresh live-provider acceptance are not claimed here; dependency advisories remain documented. [Current audit](https://github.com/umarmaulanazakaria/barberbarbar/blob/main/docs/audit/AUDIT-SISTEM-TERKINI.md).

**Educational portfolio and local/Sandbox demo — not a Production release claim.**

### Tech Stack

| Area | Technologies |
|---|---|
| **Frontend** | React, React Native, Expo, TypeScript, JavaScript, HTML, CSS, Tailwind CSS |
| **Backend** | Node.js, Express, REST API, JWT, Socket.IO |
| **Database & Tools** | PostgreSQL, Prisma, Git, GitHub, VS Code |

### Explore My Work

- [BARBER BARBAR — Web Management & Backend](https://github.com/umarmaulanazakaria/barberbarbar/tree/main)
- [BARBER BARBAR — Mobile Staff](https://github.com/umarmaulanazakaria/barberbarbar-mobile/tree/main)
- [BARBER BARBAR — Customer Web mobile-first](https://github.com/umarmaulanazakaria/barberbarbar-customer/tree/main)
- [All repositories](https://github.com/umarmaulanazakaria?tab=repositories)

**Open to Junior Fullstack Developer opportunities.**
