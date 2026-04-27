# Prateek Verma

Backend engineer building multi-tenant B2B SaaS systems. Currently shipping **TaskFlow** at Digital Inclined.

Final-year B.Tech at Thapar Institute · graduating June 2026 · **open to backend / full-stack roles starting July 2026** (Delhi NCR or Bangalore, hybrid preferred).

---

## Currently shipping

**TaskFlow** — Multi-tenant B2B SaaS for employee task, project & meeting management with WhatsApp-based reminders. Sole engineer. In pilot with 3 companies.

- 82+ REST endpoints across 15 modules over 23 Prisma models
- BullMQ + Redis for delayed-job WhatsApp reminders (chosen over DB-polling cron for O(1) dispatch, retries, dead-letter)
- Two-tier RBAC, JWT with refresh-token rotation, TOTP 2FA
- Realtime chat & notifications via Socket.io, Cloudinary + AWS S3, Google Calendar sync
- Node 20 · Express 5 · PostgreSQL 15 · Prisma 6 · Redis · Socket.io · Next.js 14
- Source private (active commercial pilot) — case study: **[TaskFlow →](https://github.com/Pvk1294/taskflow)**

## Selected projects

**[Spendly](https://github.com/Pvk1294/Spendly)** — Privacy-first expense tracker for India. Auto-captures spend by parsing transaction SMS on-device — no raw SMS leaves the phone, no credentials handed to aggregators. Hybrid pipeline: regex parser + a separate Python trainer that fine-tunes a local Mistral-7B model via Ollama on labelled samples. WhatsApp OTP + Firebase Google Sign-In, two-token sessions with real server-side revocation.
*React Native · TypeScript · Node.js · Prisma · PostgreSQL · Ollama (Mistral-7B)*

**[Meta Ads CRM](https://github.com/Pvk1294/internship-showcase-digital-inclined)** — Production CRM backend at a Noida ad agency. 1-click ad-account sync for 100+ business accounts; automated weekly client PDF reporting cut manual effort by ~90%. JWT + bcrypt + WhatsApp OTP + TOTP, deployed on GCP Compute Engine + Cloud SQL behind Nginx.
*Software Developer Intern · Digital Inclined · Jun – Aug 2025*

**[Distributor Loyalty Platform](https://github.com/Pvk1294/internship-showcase-vadhiyar-seeds)** — QR-based loyalty rewards platform for a seed distributor network. Bulk QR generation (ZIP downloads), single-use scan-to-points, points ledger, audit trails. 60%+ API call reduction via local caching on the React Native client.
*Full-Stack Developer Intern · Vadhiyar Seeds · Jun – Aug 2025*

## Background

```
Languages       JavaScript · TypeScript · Python · SQL
Backend         Node.js · Express · Prisma · BullMQ · Socket.io · REST · JWT
Databases       PostgreSQL · Redis · MongoDB · Firebase
Cloud           AWS (EC2) · GCP (Compute Engine, Cloud SQL) · Docker · Nginx
Frontend        Next.js · React · React Native · Tailwind
Tooling         Git · Postman · Cloudinary · Ollama
```

## Contact

- **Email** — pvk1294@gmail.com
- **LinkedIn** — [linkedin.com/in/pvk1294](https://linkedin.com/in/pvk1294)
- **Portfolio** — [pvk-portfolio.vercel.app](https://pvk-portfolio.vercel.app)
- **LeetCode** — [leetcode.com/u/pvk1294](https://leetcode.com/u/pvk1294)
