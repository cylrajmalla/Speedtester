# Internet Speed Test - Self-Hosted (LibreSpeed)

A fast, modern, accurate, and fully self-hosted internet speed test powered by **LibreSpeed** (the open-source Speedtest.net alternative used by Cloudflare, Tele2, and thousands of ISPs worldwide).

Accurate multi-stream measurement of **ping, download, and upload** speed — no third-party dependencies, no tracking by default.

Live examples: https://librespeed.org • https://speed.cloudflare.com

## Features

- Accurate results (within 5% of Ookla Speedtest.net)
- Automatic selection of the fastest server (lowest latency)
- Beautiful, responsive UI (mobile + desktop ready)
- Single binary Go backend (<10 MB RAM, handles 10k+ concurrent tests)
- Zero JavaScript framework bloat (vanilla JS + Tailwind)
- Full HTTPS support with automatic certificates (Caddy)
- Optional anonymized telemetry & simple dashboard
- Docker & Docker-Compose ready
- Easy multi-region deployment

## Quick Start (5 minutes)

### Option 1: Docker Compose (Recommended)

```bash
git clone https://github.com/cylrajmalla/internet-speedtest.git
cd internet-speedtest
docker compose up -d
