# Changers Network

A dedicated social network and collaborative ecosystem for student changemakers — a place to share ideas, find collaborators, and track real-world impact projects.

---

## Funding & Support

| | |
|---|---|
| **Funder** | American International School of Budapest (AISB) — grant funding |
| **Promotional partner** | Inspire Citizens — global outreach and community building |

The AISB grant supports the backend infrastructure, database hosting, and community deployment that keep the platform live and scaling. Inspire Citizens provides strategic promotional support, aligning the network with global citizenship education and youth action initiatives.

## Multi-Client Architecture

Changers ships as a single platform across four client surfaces:

| Client | Stack |
|---|---|
| **Web** | Next.js PWA — installable, responsive |
| **Mobile** | Expo — iOS and Android from one codebase |
| **Desktop** | Electron |
| **Backend** | Appwrite + Postgres |

### Backend responsibilities

- **Appwrite** — social feed, WebRTC video calls, chat rooms, direct messaging
- **Postgres** — media metadata, contact forms, audit trails

## Why it exists

Students with real projects often have no place to find each other. Changers gives changemakers a shared network to post projects, discover opportunities, form teams, and get feedback from peers and mentors.

## Links

- **Live platform** — https://changers-three.vercel.app/
- **Founder** — [@imredavid64-glitch](https://github.com/imredavid64-glitch)

## Status

Live and scaling, backed by AISB grant funding.

---

*Part of the [DSIndieAI](https://dsindieai.vercel.app) ecosystem.*
