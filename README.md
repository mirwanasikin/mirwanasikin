# ❄️ Irwan Asikin

> **_Studied Animal Science. Ended up in Linux. Life is weird._**

It started because my laptop couldn't run Windows properly. Someone online said
try Linux. I did. Two months later I forgot I had Windows installed, wiped it,
put Arch on manually, and somehow that became my career direction.

Currently daily driving NixOS on hardware from 2010 (Intel Core i3 M380, still
alive, still compiling). Building AWS infra with Terraform, writing Ansible
playbooks, breaking k3s clusters for fun.

Open to Junior DevOps/Cloud/SRE roles. Preferably ones that let me stay in the
terminal.

## 🔧 Tools & Stack

```yaml
OS: NixOS (reproducible > convenient)
hardware: Toshiba Satellite A665 — Intel Core i3 M380, 8GB RAM (yes, still alive)
```

![Linux](https://img.shields.io/badge/Linux-white?style=for-the-badge&logo=linux&logoColor=black)
![NixOS](https://img.shields.io/badge/NixOS-white?style=for-the-badge&logo=nixos)
![Docker](https://img.shields.io/badge/Docker-white?style=for-the-badge&logo=docker&logoColor=2496ED)
![Podman](https://img.shields.io/badge/Podman-white?style=for-the-badge&logo=podman&logoColor=892CA0)
![Terraform](https://img.shields.io/badge/Terraform-white?style=for-the-badge&logo=terraform&logoColor=7B42BC)
![AWS](https://img.shields.io/badge/AWS-white?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900)
![Ansible](https://img.shields.io/badge/Ansible-white?style=for-the-badge&logo=ansible&logoColor=EE0000)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-white?style=for-the-badge&logo=githubactions&logoColor=2088FF)
![Kubernetes](https://img.shields.io/badge/k3s-white?style=for-the-badge&logo=kubernetes&logoColor=326CE5)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-white?style=for-the-badge&logo=gitlab&logoColor=FC6D26)

---

## 🚧 Featured Work

### 🏗️ [terraform-aws-web](https://github.com/mirwanasikin/terraform-aws-web)

> Full-stack AWS infrastructure — actually applied, not just planned.

Architecture: `CloudFront → ALB → EC2 → RDS`, with S3 serving the frontend.

What I focused on:

- **Modular structure** — each concern lives in its own module (`network`, `compute`, `load_balancer`, etc), separated by environment (dev/prod)
- **Remote state on S3** — because local state is a disaster waiting to happen
- **SSM-only access** — no SSH ports exposed, ever
- **IAM least privilege** — roles scoped to what they actually need

Still actively building out the prod environment.

---

### ❄️ [nixos-config](https://github.com/mirwanasikin/nixos-config)

> My entire system, declared in Nix. If it breaks, one command fixes it.

Running on a 2010 Toshiba (Intel Core i3 M380) — not as a flex,
just proof that a well-configured system beats raw hardware.

What's inside:

- **Full Home Manager integration** — userspace fully managed in Nix, no manual dotfile hunting
- **Dotfiles via `xdg.configFile`** — Niri, Noctalia Shell, Foot, all version-controlled
- **Modular structure** — `hosts/`, `home/modules/`, `dotfiles/` cleanly separated
- 92 commits and counting — this is my daily driver, not a demo

---

## 📬 Open to Work

Looking for a **Junior DevOps / Cloud / SRE** role — ideally one where Linux
isn't an afterthought.

Comfortable with: infrastructure provisioning, cloud architecture, CI/CD pipelines,
and debugging things at 2am because something in prod decided to be interesting.

<div align=left>
<a href="https://www.linkedin.com/in/mirwanasikin"><img title="mirwanasikin" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linkedin/linkedin-original.svg"  height=35px width=35px/>
</a>
</div>
