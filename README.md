# Carl Jassian Balaria

**AI Application Engineer · Full-Stack Developer**

I build software that puts large language models to work inside real products: schema-validated model outputs, evaluation harnesses that catch regressions before release, and the TypeScript and PostgreSQL backends around them. Recent BS Information Technology graduate (Magna Cum Laude, 2026), based in the Philippines.

[clerune.com](https://www.clerune.com) · [LinkedIn](https://www.linkedin.com/in/jassian-balaria/) · carlbalaria@gmail.com

**Stack:** TypeScript · JavaScript · React · Next.js · Node.js (Express, Fastify) · PostgreSQL · Drizzle ORM · Redis / BullMQ · Anthropic Claude API · Deepgram · Docker · GitHub Actions · Vercel · Railway

## Featured projects

### [Clerune](https://www.clerune.com) — production AI meeting and work assistant

Turns meeting transcripts into summaries, decisions and action items with schema-validated Claude outputs, plus Deepgram transcription, usage metering, controlled AI error handling and privacy-safe AI telemetry. Prompt changes are evaluated against a reproducible 15-case dataset (noisy transcripts, prompt injection, date grounding) with predefined regression guardrails; on that fixed set the current version scored 10/10 on meeting-date grounding, 57/57 on deadlines, with 0/25 relative-date guardrail violations.

React · Express · PostgreSQL · Anthropic · Deepgram · Vercel / Railway — live product; source is private.

### [LifeInbox](https://github.com/JassianAzi/lifeinbox) — document intelligence app *(In Development)*

Upload, extract and review pipeline that turns bills, receipts and everyday documents into structured information and tasks. OCR and analysis sit behind provider adapters (Google Document AI, Anthropic), with explicit consent before any document leaves the app, prompt-injection-safe review states, retry-safe extraction, reminders, and account export and deletion.

Next.js 16 · React 19 · PostgreSQL / Drizzle · 239 automated tests against in-process PostgreSQL (PGlite) · GitHub Actions CI.

### [OpsFlow](https://github.com/JassianAzi/opsflow) — workflow automation backend *(In Development)*

Multi-tenant workflow platform focused on reliable execution: transactional outbox, immutable execution snapshots, fenced leases with `FOR UPDATE SKIP LOCKED`, idempotent processing, optimistic concurrency and crash recovery. The step engine itself is not built yet; executions currently end deliberately with `EXECUTION_ENGINE_NOT_IMPLEMENTED`.

Fastify · React / Vite · PostgreSQL / Drizzle · Redis / BullMQ · integration tests against real PostgreSQL and Redis in GitHub Actions.

### [Bayaw's Grill](https://bayawsgrill.com) — client restaurant website

Production website for a local restaurant: responsive Astro site with SEO and structured data, deployed on Vercel with a custom domain.

## Education and certifications

BS Information Technology, Magna Cum Laude — Nueva Ecija University of Science and Technology (2026) · Cisco: Operating Systems Support · Cisco: Cyber Threat Management · Certiport IT Specialist: HTML and CSS · Civil Service Eligibility
