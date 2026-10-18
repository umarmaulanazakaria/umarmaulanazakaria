# Umar Maulana Zakaria

**Junior Fullstack Developer | Web & Mobile Development**

I build web and mobile applications with a focus on clear user experiences, reliable backend workflows, and well-structured data. My current stack includes **TypeScript, React, React Native, Node.js, Express, Prisma, and PostgreSQL**.

I'm developing my skills through hands-on projects that connect frontend, backend, database, and third-party integrations.

## Featured Project — BARBER BARBAR

**Three applications. One backend. One connected barbershop workflow.**

An integrated barbershop management system built for an internship project and fullstack portfolio: **Admin Web**, **React Native Staff Minimal V3**, and **Customer Web mobile-first**.

### Admin Web

| Dashboard | Pesanan | Membership |
| --- | --- | --- |
| <a href="https://github.com/umarmaulanazakaria/barberbarbar/blob/main/docs/showcase/dashboard.jpg"><img src="https://raw.githubusercontent.com/umarmaulanazakaria/barberbarbar/main/docs/showcase/dashboard.jpg" alt="Actual Admin Web dashboard with synthetic API data" width="280" /></a> | <a href="https://github.com/umarmaulanazakaria/barberbarbar/blob/main/docs/showcase/pesanan.jpg"><img src="https://raw.githubusercontent.com/umarmaulanazakaria/barberbarbar/main/docs/showcase/pesanan.jpg" alt="Actual Admin Web pesanan with synthetic API data" width="280" /></a> | <a href="https://github.com/umarmaulanazakaria/barberbarbar/blob/main/docs/showcase/membership.jpg"><img src="https://raw.githubusercontent.com/umarmaulanazakaria/barberbarbar/main/docs/showcase/membership.jpg" alt="Actual Admin Web membership with synthetic API data" width="280" /></a> |

*Actual Web application UI from main, captured with synthetic intercepted API responses; not live operational data or proof of payment.*

### Staff Mobile

| Pesanan | Walk-in Reguler | Riwayat |
| --- | --- | --- |
| <a href="https://github.com/umarmaulanazakaria/barberbarbar-mobile/blob/main/docs/showcase/staff/pesanan.jpg"><img src="https://raw.githubusercontent.com/umarmaulanazakaria/barberbarbar-mobile/main/docs/showcase/staff/pesanan.jpg" alt="Edited Staff presentation visual: pesanan" width="210" /></a> | <a href="https://github.com/umarmaulanazakaria/barberbarbar-mobile/blob/main/docs/showcase/staff/walkin-reguler.jpg"><img src="https://raw.githubusercontent.com/umarmaulanazakaria/barberbarbar-mobile/main/docs/showcase/staff/walkin-reguler.jpg" alt="Edited Staff presentation visual: walkin-reguler" width="210" /></a> | <a href="https://github.com/umarmaulanazakaria/barberbarbar-mobile/blob/main/docs/showcase/staff/riwayat.jpg"><img src="https://raw.githubusercontent.com/umarmaulanazakaria/barberbarbar-mobile/main/docs/showcase/staff/riwayat.jpg" alt="Edited Staff presentation visual: riwayat" width="210" /></a> |

*Presentation visuals based on Staff screenshots supplied by the project owner. Identities and example data were edited; some content and prices differ from the live catalogue. These are not raw native captures, Android test evidence or verified provider transactions.*

[Full Staff gallery: Member walk-in, completed history and empty state](https://github.com/umarmaulanazakaria/barberbarbar-mobile/tree/main#galeri-staff-mobile-minimal-v3). **Beranda is not available. Profil is withheld because the source email has not been verified as fictional; a safe example.com demo version is needed.** [Image provenance](https://github.com/umarmaulanazakaria/barberbarbar-mobile/blob/main/docs/showcase/README.md).

### Customer Web · mobile-first

| Catalogue | Booking | Payment | Private tracking |
| --- | --- | --- | --- |
| <a href="https://github.com/umarmaulanazakaria/barberbarbar-customer/blob/main/docs/showcase/katalog.jpg"><img src="https://raw.githubusercontent.com/umarmaulanazakaria/barberbarbar-customer/main/docs/showcase/katalog.jpg" alt="Actual Customer Web katalog with synthetic API data" width="190" /></a> | <a href="https://github.com/umarmaulanazakaria/barberbarbar-customer/blob/main/docs/showcase/booking.jpg"><img src="https://raw.githubusercontent.com/umarmaulanazakaria/barberbarbar-customer/main/docs/showcase/booking.jpg" alt="Actual Customer Web booking with synthetic API data" width="190" /></a> | <a href="https://github.com/umarmaulanazakaria/barberbarbar-customer/blob/main/docs/showcase/pembayaran.jpg"><img src="https://raw.githubusercontent.com/umarmaulanazakaria/barberbarbar-customer/main/docs/showcase/pembayaran.jpg" alt="Actual Customer Web pembayaran with synthetic API data" width="190" /></a> | <a href="https://github.com/umarmaulanazakaria/barberbarbar-customer/blob/main/docs/showcase/tracking.jpg"><img src="https://raw.githubusercontent.com/umarmaulanazakaria/barberbarbar-customer/main/docs/showcase/tracking.jpg" alt="Actual Customer Web tracking with synthetic API data" width="190" /></a> |

*Actual browser UI with synthetic intercepted API responses. The tracking form is empty to keep access codes private; no provider transaction was created for these images.*

[Admin gallery](https://github.com/umarmaulanazakaria/barberbarbar/tree/main) · [Staff gallery](https://github.com/umarmaulanazakaria/barberbarbar-mobile/tree/main) · [Customer gallery](https://github.com/umarmaulanazakaria/barberbarbar-customer/tree/main)

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

**Evidence and limits:** main finalization passed builds/TypeScript, 14 backend fixture/mock suites, the Customer UI suite across eight viewports, and Staff Android/Hermes export. Admin/Customer capture used synthetic API responses without touching a database or payment provider; Staff visuals are supplied presentation edits, not new device captures. Native-device, printer and fresh live-provider acceptance are not claimed here; dependency advisories remain documented. [Current audit](https://github.com/umarmaulanazakaria/barberbarbar/blob/main/docs/audit/AUDIT-SISTEM-TERKINI.md).

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
