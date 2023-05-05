[![crowdparlay-banner](https://user-images.githubusercontent.com/69521267/233804505-294d9e23-22b3-4400-9b65-e973439bc47c.png)](#)

## Architecture
- [`frontend`](https://github.com/crowdparlay/frontend) — common UI, client-side storage, SPA
- [`users`](https://github.com/crowdparlay/users) — authentication, preferences, actor-specific stuff
- `organizations` — roles, organization-specific stuff
- `profiles` — user & organization profiles (common functionality)
- `events` — event profiles, statuses, trigger scheduling, real-time statistics, notifications
- `moderation` — issues, reports, applications, trilateral arbitrage, automated analysis
- `feed` — event listing, trending, personal recommendations
- [`social`](https://github.com/crowdparlay/social) — chats, boards, event-centric discussions
- `finance` — wallets, payments, transactions
- `cdn` — content delivery (isolated media storage or third-party solution)
