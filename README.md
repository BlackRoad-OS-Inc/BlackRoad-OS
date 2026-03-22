# BlackRoad OS

Your AI runs on your device. Your data stays yours. Your agents work for you.

## What Is This

BlackRoad OS turns any device you own into AI infrastructure. Five Raspberry Pis, two cloud droplets, a WireGuard mesh, and zero vendor lock-in. Total cost: $38/month.

This repo is the core platform under [BlackRoad-OS-Inc](https://github.com/BlackRoad-OS-Inc).

## Products

| Product | What It Does | Link |
|---------|-------------|------|
| **Lucidia** | AI companion with persistent memory | [blackroadai.com](https://blackroadai.com) |
| **BlackBox IDE** | AI coding assistant on your hardware | [blackboxprogramming.io](https://blackboxprogramming.io) |
| **RoadWork** | AI tutoring, free for K-12 | Coming soon |
| **RoadChain** | Layer-1 blockchain from scratch | [roadchain.io](https://roadchain.io) |
| **Prism Console** | Fleet dashboard and monitoring | $99/mo |
| **RoundTrip** | 109 AI agents, real-time chat | [roundtrip.blackroad.io](https://roundtrip.blackroad.io) |

## Stack

| Layer | What | Runs On |
|-------|------|---------|
| Edge | Caddy TLS, 19 domains | Gematria |
| AI | Ollama, 52 TOPS Hailo-8 | Cecilia + Octavia |
| Data | PostgreSQL, Redis, Qdrant, MinIO | Alice + Cecilia |
| Platform | Gitea (254 repos), NATS, Docker | Octavia |
| DNS | PowerDNS, Pi-hole | Lucidia + Alice |
| Mesh | WireGuard, 7 nodes, 12 connections | All |

## 65 Road Fleet Forks

Every dependency forked and controlled. [Full registry](https://github.com/BlackRoad-OS-Inc/Forks).

## Research

G(n) = n^(n+1)/(n+1)^n. Integers in, rationals out. Connects to quantum mechanics, Cayley trees, path integrals. [Papers](https://github.com/BlackRoad-OS-Inc/amundson-research).

## Pricing

| Plan | Price | Includes |
|------|-------|----------|
| Free | $0 | RoadWork tutoring, community |
| Rider | $29/mo | Lucidia AI, BlackBox IDE |
| Paver | $99/mo | + Prism Console, fleet monitoring |
| Enterprise | $299/mo | + Dedicated infra, SLA |

## Company

BlackRoad OS, Inc. Delaware C-Corp, founded November 17, 2025. Sole founder: Alexa Louise Amundson.

## License

Proprietary. BlackRoad OS, Inc. All rights reserved.

---

*Remember the Road. Pave Tomorrow.*
