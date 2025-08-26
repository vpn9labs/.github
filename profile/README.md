# VPN9 — True Privacy. Zero Logs. No Compromises.

**VPN9 Labs**

**Website:** [vpn9.com](https://vpn9.com)

Privacy is a fundamental human right. It protects your life, identity, and data.  
Free from surveillance and censorship. Free from business models that sell your behavior.  
Free from compromise.

---

## Start here

- **[Open‑source VPN client](https://github.com/vpn9labs/vpn9-app)** — desktop and mobile via Tauri + Rust. Kill‑switch, split tunneling, strict leak protection, zero connection logs.
- **[Rust WireGuard control plane](https://github.com/vpn9labs/vpn9-service)** — gRPC control plane and node agent. Session issuance, policy enforcement, node orchestration. Zero‑log by construction.
- **[Rails portal & public API](https://github.com/vpn9labs/vpn9-portal)** — website, admin, anonymous accounts, crypto payments, client bootstrap.
- **[DNS leak detection tool](https://github.com/vpn9labs/vpn9-dns-leak-tool)** — Rust + REST API for comprehensive DNS leak testing.

## Architecture & principles

- WireGuard at the core; Rust across control plane and client.
- Zero‑logs by design; no analytics or behavioral tracking.
- Defensive defaults: kill‑switch, split tunneling, strict DNS/IPv6/WebRTC leak protection.
- Anonymous accounts and crypto payments supported.

## Contributing

Issues and PRs are welcome in the repositories above. Priority areas: client UX, protocol hardening, telemetry‑free diagnostics, platform coverage.
