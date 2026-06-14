<div align="center">

# vllnt

**Freedom is the goal.**

Open infrastructure that helps people and businesses stay sovereign in a world
reshaped by AI — yours to run, inspect, and walk away from.

---

[![npm](https://img.shields.io/badge/npm-@vllnt-cb0000)](https://www.npmjs.com/org/vllnt)
[![GitHub](https://img.shields.io/badge/built%20by-@bntvllnt-000)](https://github.com/bntvllnt)

</div>

## Packages

| Package | npm | What it does |
|---------|-----|-------------|
| [@vllnt/eslint-config](https://github.com/vllnt/eslint-config) | [![npm](https://img.shields.io/npm/v/@vllnt/eslint-config)](https://www.npmjs.com/package/@vllnt/eslint-config) | Strict ESLint flat config for TypeScript — every rule enforces error. Next.js, React, Node.js, Convex presets |
| [@vllnt/typescript](https://github.com/vllnt/typescript) | [![npm](https://img.shields.io/npm/v/@vllnt/typescript)](https://www.npmjs.com/package/@vllnt/typescript) | Shared TypeScript configurations — Next.js, React, Node.js, Node library presets |
| [@vllnt/analytics](https://github.com/vllnt/analytics) | [![npm](https://img.shields.io/npm/v/@vllnt/analytics)](https://www.npmjs.com/package/@vllnt/analytics) | Lightweight privacy-first analytics with consent management, DNT detection, and React hooks |
| [@vllnt/logger](https://github.com/vllnt/logger) | [![npm](https://img.shields.io/npm/v/@vllnt/logger)](https://www.npmjs.com/package/@vllnt/logger) | Structured JSON logging — zero deps, tree-shakeable, multi-runtime (Node, Convex, browser, edge) |
| [@vllnt/ui](https://github.com/vllnt/ui) | [![npm](https://img.shields.io/npm/v/@vllnt/ui)](https://www.npmjs.com/package/@vllnt/ui) | Modular UI component library — React, TypeScript, Tailwind |

## Convex Components

Sandboxed, `app.use()`-mountable components for any Convex backend — each owns its own data sandbox, stays domain-neutral, and is typed end to end. Currently shipping `canary` builds.

| Package | npm | What it does |
|---------|-----|-------------|
| [@vllnt/convex-api-keys](https://github.com/vllnt/convex-api-keys) | [![npm](https://img.shields.io/npm/v/@vllnt/convex-api-keys)](https://www.npmjs.com/package/@vllnt/convex-api-keys) | Secure API key management — create, validate, revoke, rotate, rate-limit, track usage |
| [@vllnt/convex-async-operations](https://github.com/vllnt/convex-async-operations) | [![npm](https://img.shields.io/npm/v/@vllnt/convex-async-operations)](https://www.npmjs.com/package/@vllnt/convex-async-operations) | 202-Accepted envelope for long-running operations — record, transition, and poll async work |
| [@vllnt/convex-comments](https://github.com/vllnt/convex-comments) | [![npm](https://img.shields.io/npm/v/@vllnt/convex-comments)](https://www.npmjs.com/package/@vllnt/convex-comments) | Threaded comments / annotations on any resource — post, reply, edit, resolve, soft-delete |
| [@vllnt/convex-consent](https://github.com/vllnt/convex-consent) | [![npm](https://img.shields.io/npm/v/@vllnt/convex-consent)](https://www.npmjs.com/package/@vllnt/convex-consent) | Append-only consent ledger (GDPR Art. 6/7) — record, withdraw, and gate consent per subject + purpose |
| [@vllnt/convex-email](https://github.com/vllnt/convex-email) | [![npm](https://img.shields.io/npm/v/@vllnt/convex-email)](https://www.npmjs.com/package/@vllnt/convex-email) | Durable, transport-agnostic transactional email queue — enqueue, retry, idempotent send, delivery status |
| [@vllnt/convex-events](https://github.com/vllnt/convex-events) | [![npm](https://img.shields.io/npm/v/@vllnt/convex-events)](https://www.npmjs.com/package/@vllnt/convex-events) | Append-only per-subject activity feed and event ledger |
| [@vllnt/convex-flags](https://github.com/vllnt/convex-flags) | [![npm](https://img.shields.io/npm/v/@vllnt/convex-flags)](https://www.npmjs.com/package/@vllnt/convex-flags) | Feature flags — boolean & multivariate, % rollout, attribute targeting, evaluated server-side and streamed live |
| [@vllnt/convex-idempotency](https://github.com/vllnt/convex-idempotency) | [![npm](https://img.shields.io/npm/v/@vllnt/convex-idempotency)](https://www.npmjs.com/package/@vllnt/convex-idempotency) | Exactly-once idempotency key ledger for retried operations |
| [@vllnt/convex-invitations](https://github.com/vllnt/convex-invitations) | [![npm](https://img.shields.io/npm/v/@vllnt/convex-invitations)](https://www.npmjs.com/package/@vllnt/convex-invitations) | Invite → accept → expire — single-use, expiring invitations to a resource |
| [@vllnt/convex-memberships](https://github.com/vllnt/convex-memberships) | [![npm](https://img.shields.io/npm/v/@vllnt/convex-memberships)](https://www.npmjs.com/package/@vllnt/convex-memberships) | Auth-agnostic membership and relationship graph (ReBAC tuples) |
| [@vllnt/convex-notifications](https://github.com/vllnt/convex-notifications) | [![npm](https://img.shields.io/npm/v/@vllnt/convex-notifications)](https://www.npmjs.com/package/@vllnt/convex-notifications) | Per-subject directed inbox — read/unread state and fan-out |
| [@vllnt/convex-permissions](https://github.com/vllnt/convex-permissions) | [![npm](https://img.shields.io/npm/v/@vllnt/convex-permissions)](https://www.npmjs.com/package/@vllnt/convex-permissions) | Typed authorization — roles and policies, type-safe guards (require/check/can) |
| [@vllnt/convex-reactions](https://github.com/vllnt/convex-reactions) | [![npm](https://img.shields.io/npm/v/@vllnt/convex-reactions)](https://www.npmjs.com/package/@vllnt/convex-reactions) | Reactions, votes, and likes on any resource — toggle, count by kind, list reactors |
| [@vllnt/convex-slugs](https://github.com/vllnt/convex-slugs) | [![npm](https://img.shields.io/npm/v/@vllnt/convex-slugs)](https://www.npmjs.com/package/@vllnt/convex-slugs) | Unique slug and handle registry with rename redirects |
| [@vllnt/convex-suppression](https://github.com/vllnt/convex-suppression) | [![npm](https://img.shields.io/npm/v/@vllnt/convex-suppression)](https://www.npmjs.com/package/@vllnt/convex-suppression) | Do-not-contact suppression list + opt-in proof (GDPR/CAN-SPAM), hash-keyed and channel-aware |
| [@vllnt/convex-tokens](https://github.com/vllnt/convex-tokens) | [![npm](https://img.shields.io/npm/v/@vllnt/convex-tokens)](https://www.npmjs.com/package/@vllnt/convex-tokens) | Hashed-secret token primitive — mint-once, TTL, revoke, scope |
| [@vllnt/convex-wallet](https://github.com/vllnt/convex-wallet) | [![npm](https://img.shields.io/npm/v/@vllnt/convex-wallet)](https://www.npmjs.com/package/@vllnt/convex-wallet) | Consumable balances and economy ledger — atomic spend, lazy regen |

### Convex tooling

| Package | npm | What it does |
|---------|-----|-------------|
| [@vllnt/convex-helpers](https://github.com/vllnt/convex-helpers) | [![npm](https://img.shields.io/npm/v/@vllnt/convex-helpers)](https://www.npmjs.com/package/@vllnt/convex-helpers) | Typed host-side helpers for Convex backends — builders, errors, validators, relationships, pagination, HTTP, env, observability |
| [@vllnt/convex-mcp](https://github.com/vllnt/convex-mcp) | [![npm](https://img.shields.io/npm/v/@vllnt/convex-mcp)](https://www.npmjs.com/package/@vllnt/convex-mcp) | Expose Convex functions as MCP tools with zero boilerplate |

### Coming Soon

| Package | What it does |
|---------|-------------|
| @vllnt/convex-analytics | Convex component — API-first analytics engine with events, sessions, funnels, retention, and MCP tools |

## Why we build

**Freedom is the goal.** Four principles serve it:

- **Knowledge** — no black boxes. We explain what runs and why. See the territory, not just the map.
- **Privacy** — what's yours stays yours. Local and self-hostable by default; no telemetry without consent.
- **Sovereignty** — own your stack. Self-hostable over SaaS-only; you control your data, deploys, and keys.
- **Legacy** — built to last. Maintainable, documented, deletable code — no throwaway hacks aimed at an exit.

## How we build

- **Open by default** — everything ships as open source
- **Agent-ready** — built for AI-assisted and AI-driven development
- **Composable** — use what you need, override what you don't
- **Strict by default** — opinionated configs so correctness is the path of least resistance

---

<div align="center">

[![Website](https://img.shields.io/badge/vllnt.ai-000?style=flat)](https://vllnt.ai)
[![X](https://img.shields.io/badge/@bntvllnt-000?style=flat&logo=x)](https://bntvllnt.com/x)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat&logo=discord&logoColor=white)](https://bntvllnt.com/discord)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin)](https://bntvllnt.com/linkedin)

</div>
