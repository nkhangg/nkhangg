# Hi, I'm Phạm Nhứt Khang

**Backend-focused Full-stack Engineer** · Cần Thơ, Vietnam
NestJS · Laravel · PostgreSQL · Redis · React

I build and run production systems for e-commerce businesses in Australia and the US: multi-channel product sync (eBay, Amazon SP-API, Magento, Google Merchant), online payments and auction automation. I also work on a multi-tenant SaaS for construction finance. 2+ years, involved end to end: requirements, design, coding, testing, deployment and production support.

## Tech

- **Backend:** TypeScript, Node.js, NestJS, PHP 8, Laravel, REST APIs, queues (BullMQ, Laravel Horizon), multi-tenancy, RBAC, webhooks, Socket.IO, SSE
- **Data:** PostgreSQL, MySQL, Redis, OpenSearch, Prisma, TypeORM, Eloquent, query optimization, PgBouncer
- **Testing & ops:** PHPUnit, Jest, E2E tests against real databases, load testing, Docker Compose, Linux, Nginx, CI/CD (Gitea Actions)
- **Frontend:** React, Next.js, TanStack Query, Tailwind CSS, shadcn/ui, Mantine

## Work highlights

Company source code is private, so these are summaries rather than links.

- **Multi-channel product sync** (Laravel, MySQL, Redis, OpenSearch): merges 8 source groups into a ~360,000-product catalog and pushes it to 4 sales channels. Led the refactor of the legacy monolith into 13 modules. Moving to the eBay bulk API made price/stock updates 10.9× faster (measured on sandbox); an attribute index table cut product filtering from 4+ s to ~120 ms on 360k products. Wrote ~3,800 of the project's 4,600+ PHPUnit tests.
- **Construction-finance SaaS** (NestJS, Prisma, PostgreSQL, PgBouncer, BullMQ; unreleased): database-per-tenant admin platform with tenant database migration between servers. Load tests went from 150 to 750 virtual users read-only (p95 < 300 ms, no errors) and 300 with writes. Ported the API from Express to NestJS without changing the API contract, covered by 135 unit + 156 E2E tests on real PostgreSQL.
- **Auction automation** (NestJS, Puppeteer, Socket.IO, Chrome Extension MV3): bots that watch and bid across auction sites, a real-time admin panel and browser health monitoring, ~270 automated tests.
- **Payment service** (Laravel, PayPal, Simplify, Braintree): order API for client systems, checkout with Google Pay / Apple Pay, server-side verification, webhooks with retries and manual resend.

## Projects you can read

| Project | What it shows |
|---|---|
| [nihongo-learning](https://github.com/nkhangg/nihongo-learning) | Japanese learning platform. NestJS modular monolith with 16 modules in Clean Architecture / DDD layers, Prisma, BullMQ, RBAC, domain events; React admin + Next.js client |
| [base-nestjs-reactjs](https://github.com/nkhangg/base-nestjs-reactjs) | Reusable starter extracted from the project above: auth, RBAC, media, notifications, admin shell |
| [servervault](https://github.com/nkhangg/servervault) | Terminal UI (React Ink) for managing SSH servers; passwords kept in the OS keychain, one-key SSH / VS Code Remote |
| [ktq-news-backend](https://github.com/nkhangg/ktq-news-backend) | NestJS + TypeORM + MySQL content platform API with auth, admin and media modules |
| [ktq-react-table](https://github.com/nkhangg/ktq-react-table) · [ktq-react-generate-form](https://github.com/nkhangg/ktq-react-generate-form) | React (Mantine) data-table and form-generator components, published on npm |

## Contact

phamnhatkhang.hgi1167@gmail.com
