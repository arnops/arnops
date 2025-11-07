# 👋 Hi, I'm **[arnops](https://arnops.omg.lol)**

I ❤️ to play with stuff and share.

Below is a quick snapshot of what lives here and how to get started.

---

## 🚀 Projects

### ✈️ IFO — Identified Flying Object
A blazing-fast Rust CLI to query **real-time aircraft** data around any location using the OpenSky Network API.
- **Highlights:** sub-5ms startup, coordinate or place-name queries, configurable radius & timeout
- **Install:** download a release or `cargo build --release`
- **Repo:** [arnops/ifo](https://github.com/arnops/ifo)

### 📡 Pulse — CLI Monitoring with Discord Notifs
A lightweight CLI that runs commands on an interval, detects changes, and sends rich **Discord webhook** notifications.
- **Highlights:** async execution, change tracking, multi-monitor config, tiny footprint
- **Install:** download a release or `cargo build --release`
- **Repo:** [arnops/pulse](https://github.com/arnops/pulse)

---

## 🧪 Quick starts

**IFO — query by place name**
```bash
ifo --place "San Francisco"
# or with a custom search radius (~degrees; 0.5° ≈ 55 km)
ifo --place "New York" --radius 1.0
```

**Pulse — monitor a command and notify Discord**
```bash
pulse run \
  --command "ifo --place 'NYC'" \
  --interval 60 \
  --webhook https://discord.com/api/webhooks/xxx/yyy
```

⸻

## 🤝 Contributing

Issues and PRs are welcome. If you have ideas for small, useful CLIs or workflow-friendly tooling, open an issue in the relevant repo.

⸻

## 📬 Contact

The easiest way to reach me is by opening an issue on any of the repositories above.  