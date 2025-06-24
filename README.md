# Zenth OS

**Zenth OS** is a lightweight, secure, and fully open-source operating system tailored for the Zenth Cloud ecosystem, developed by Sky Genesis Enterprise. It is built on Alpine Linux and optimized for containerization, cloud-native workloads, and sovereignty-focused deployments.

## 🧩 Features

- ✅ Minimal and hardened Linux base (Alpine-based)
- ✅ Fully container-ready (Docker, LXC, KVM, K8s)
- ✅ Integrated with Zenth Cloud components and tooling
- ✅ Preconfigured security modules (iptables, fail2ban, hardened kernel)
- ✅ Cloud-init and provisioning ready
- ✅ Native support for `api-server`, `ldap-server`, and more
- ✅ Built-in CLI utilities for managing services and networking
- ✅ Fast boot and low memory footprint

## 📦 Designed For

Zenth OS is the default base layer powering all other Zenth servers and services:

- `mail-server`, `sip-server`, `dns-server`, etc.
- `firewall-server` and `vpn-server` with hardened networking
- `panel-server` UI deployments
- `api-server` with native CLI and sys integration
- Compatible with `Proxmox`, `Docker`, and bare-metal installations

## 🛠️ Technology Stack

- Base: **Alpine Linux**
- Init system: OpenRC or systemd (optional fork)
- Zenth CLI tools included
- Prebuilt with hardened kernels and optional AppArmor/SELinux
- Optimized for CI/CD and IaC workflows

## 📖 Documentation

Installation, system layout, kernel tuning, and deployment guides can be found in `/docs` or on [Documentations](https://docs.zenthcloud.com).

## 🔐 Security First

- Minimal attack surface (no unnecessary packages)
- Secure default config (SSH hardening, sudo lockdown)
- Rootless container compatibility
- Signed updates and package integrity checks

## 🛡️ License

Zenth OS is released under the **GNU Affero General Public License v3 (AGPLv3)**. See the `LICENSE` file for legal terms.

---

For contributions, issues, or discussions, visit [github.com/zenthcloud](https://github.com/zenthcloud).
