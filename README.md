# One Man Show

Turn any Android phone or Windows PC into a self-hosted realtime backend, static website host, and developer platform with one tap.

Built for students, self-taught developers, and indie makers who want to ship real full-stack projects without credit cards, cloud bills, or complex Docker setups.

## Key Features

- **1-Tap Local Backend Server**: REST API for Authentication, SQLite Database (WAL mode), File Storage (with ETag caching), and Static Website Hosting.
- **Realtime Engine**: Single-socket multi-channel WebSockets, Server-Sent Events (SSE) fallback, live user presence with `onDisconnect`, ephemeral broadcasts, and reconnect event replay (`lastEventId`).
- **Creator Studio**:
  - 5 one-tap Starter Templates (Portfolio, Mini Shop, Realtime Chat, Quick Notes, Student Quiz)
  - Sandboxed Static Site Dropzone (`.html` or `.zip` with CSP sandbox, Zip-Slip & Zip-Bomb protection)
  - Visual No-Code Collection Builder (create live REST + Realtime APIs without writing JSON)
  - Secret-stripped `.oms.blueprint` export & import
- **Instant Pocket Cloud Views**:
  - Live Full-Stack CRUD Web App (`/app/<appId>`)
  - Auto-Generated API Reference (`/docs/<appId>`)
  - Shareable Proof-of-Work Showcase Card (`/showcase/<appId>`)
  - Local Payment & OTP Sandbox Simulator (`/api/v1/sandbox/pay`, `/otp`, `/inbox`)
- **24/7 Uptime Guardian**: Android CPU WakeLock & Wi-Fi Lock, 45-second self-healing server watchdog, live LAN IP drift detection, adaptive Eco-Throttle, and optional failover sync to a spare device.
- **Privacy & Security First**: Local-first data storage, zero ads, zero tracking, encrypted `.oms.zip` backups, optional Telegram OTP recovery, and transparent 30-day Account & Data Deletion.

## Quick Start

1. Download and install the latest **Android APK** or **Windows PC** build from the Releases section.
2. Open **One Man Show**, create your `@enow.oms` account, and tap **Start** on the Home screen.
3. Open **My Apps** to create a project or launch a 1-tap Starter Template.
4. Tap the **Connect Guide** icon in the top bar for ready-to-paste Website, Flutter, Realtime, and Public Tunnel snippets.

## Security & Privacy

- All apps, database collections, and uploaded files stay directly on your own device.
- Hosted static websites are served with strict sandboxed Content Security Policy (`CSP`), `X-Content-Type-Options: nosniff`, `Permissions-Policy`, and `X-Frame-Options: DENY`.
- Exported `.oms.blueprint` files automatically strip and redact API keys, tokens, and secrets.

## License

Copyright (c) 2026 One Man Show. All Rights Reserved. See [LICENSE](LICENSE) for details.
