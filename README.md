# manzier

Builds things, mostly with data. By day, the technology infrastructure for a
public school district in Illinois; nights and weekends, whatever gets
measured next.

**Now:** [Peso RugScore](https://peso.manzier.com) — rug-risk scoring for
Solana developers. One number: how often this developer's launches take
buyers' money and die, measured over 367,839 resolved launches and
recalibrated every three hours. Sold as credits over an API, a web app and a
Telegram bot; payments are receive-only by construction.

**How I work**

- **Measure first.** Three "obviously good" signals were dropped from RugScore
  because the data said they didn't separate — after I'd weighted them at 45
  points in the first version.
- **Boring on purpose.** Guards that fail closed, payments that can't send,
  backups restored for real before anyone trusts them.
- **Keep it running.** Watchdogs, self-recalibration, a nightly diary. Uptime
  is part of the product.

**Stack:** Python · FastAPI · Postgres · React / TypeScript · Solana JSON-RPC ·
Telegram bots · Caddy · Ubuntu — on top of thirty years of Active Directory,
Cisco, VMware / Hyper-V and VoIP.

**Elsewhere:** [www.manzier.com](https://www.manzier.com) ·
[X @manzier3](https://x.com/manzier3) ·
[Discord](https://discord.gg/Ggt5tP8942)

Most of the code here is private for now. More to reference soon.
