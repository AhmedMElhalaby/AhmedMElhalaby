### Ahmed M. Elhalaby

**Full-stack engineer & DevOps → platform builder.** 11 years shipping production
systems — Laravel/PHP, Go and Python backends, React/TypeScript frontends, Flutter
apps, and the infrastructure under all of it. Now building native macOS developer
tools in Swift, including **[Ainkrad](https://github.com/AhmedMElhalaby/Ainkrad)**,
an agentic workspace with its own plugin SDK, CLI, and marketplace.

🇵🇸 Palestine · Building in public · [ahmedm.elhalaby@gmail.com](mailto:ahmedm.elhalaby@gmail.com)

---

## Currently building

**[Ainkrad](https://github.com/AhmedMElhalaby/Ainkrad)** — a native macOS AI agentic
workspace: a Jarvis-style floating-island HUD with tiled panes over one blurred
surface, a PTY-backed terminal, and a distraction-free Focus Mode. It ships as a
platform, not just an app — third-party plugins build against
**[AinkradAppKit](https://github.com/AhmedMElhalaby/AinkradAppKit)**, an SDK with an
ABI-frozen host contract; they are scaffolded, validated and published with the
**[`ainkrad` CLI](https://github.com/AhmedMElhalaby/AinkradKit)** distributed over a
[Homebrew tap](https://github.com/AhmedMElhalaby/homebrew-tap); and the host resolves
them from a [live catalog](https://github.com/AhmedMElhalaby/AinkradCatalog), so new
apps ship without a host release.
[![Release](https://img.shields.io/github/v/release/AhmedMElhalaby/Ainkrad?sort=semver&label=release)](https://github.com/AhmedMElhalaby/Ainkrad/releases)

**Workan.Space** — a multi-tenant workspace SaaS: bookings, check-ins, balanced
financial ledgers, and hotspot network provisioning, behind a subdomain-based
tenant router. The [front-end control room](https://github.com/AhmedMElhalaby/FE-Workan.space)
is public; the API is not.

**ULYNK** *(private)* — a self-hosted personal cloud appliance in Go, for people who
would rather own the hardware their data lives on.

---

## Selected work

| Project | What it is | Stack |
| --- | --- | --- |
| [Ainkrad](https://github.com/AhmedMElhalaby/Ainkrad) | Native macOS agentic workspace and tiling HUD shell | Swift 6, SwiftUI, AppKit |
| [AinkradAppKit](https://github.com/AhmedMElhalaby/AinkradAppKit) | Plugin SDK with an ABI-frozen host contract | Swift, SwiftPM |
| [AinkradKit](https://github.com/AhmedMElhalaby/AinkradKit) | Developer CLI for scaffolding and publishing plugins | Swift, Homebrew |
| [FE-Workan.space](https://github.com/AhmedMElhalaby/FE-Workan.space) | Multi-tenant workspace SaaS control-room portal | Next.js 15, TypeScript |
| [CORD-engine](https://github.com/CORD-LLC/CORD-engine) · [kit-builder](https://github.com/CORD-LLC/cord-aeo-kit-builder) | Engine and kit builder for the CORD-AEO protocol — validated envelope generation from a YAML intake | Python, FastAPI, Pydantic |
| [Elasticsearch](https://github.com/AhmedMElhalaby/Elasticsearch) · [Meilisearch](https://github.com/AhmedMElhalaby/Meilisearch) | Laravel Scout search-engine integrations | PHP, Laravel Scout |

**Beyond these repos** — most of my output lives in private codebases: roughly
**1,200 commits and 645 pull requests** authored outside my own account. The work
itself: multi-tenant SaaS platforms, POS and sales systems, service-marketplace and
delivery apps with provider and customer clients, real-estate portals, coworking and
booking platforms, insurance and healthcare backends, and the Flutter apps and admin
dashboards on top of them — plus the CI, containerisation and deployment around them.

---

## Stack

**Backend** — PHP/Laravel (Passport, Sanctum, Scout, Horizon, Cashier), Go, Python (FastAPI, Pydantic), Node.js, MySQL, PostgreSQL, Redis, Elasticsearch, Meilisearch
**Frontend** — TypeScript, React, Next.js, Redux Toolkit, TanStack Query, Zustand, Tailwind, Radix, Vite, Zod, Blade
**Native & mobile** — Swift 6, SwiftUI, AppKit, SwiftData, Dart/Flutter (GetX, Dio, Firebase, Google Maps)
**DevOps** — Docker & Compose, GitHub Actions, Nginx, Linux, Laravel Sail, Homebrew distribution
