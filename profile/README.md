<div align="center">
  <img src="../docs/assets/galdo-labs-logo.png" alt="galdo labs logo" width="200"/>
  <h1>galdo labs</h1>
  <p><em>Infrastructure as Code, Automation & Systems Engineering</em></p>
</div>

---

Welcome to the **galdo labs** central repository. This space unifies the management, provisioning, and configuration of infrastructure through code, ensuring reproducible, modular, and stable environments.

## 🏗️ Core Repositories

Infrastructure management is functionally divided to separate the provisioning lifecycle of base resources from operating system configuration:

*   [**`provisioning`**](../provisioning): Definition and deployment of virtual machines, containers, and base resources. Operated via **Terraform**.
*   [**`configuration`**](../configuration): State management, service orchestration, and systems automation. Operated via **Ansible**.

## ⚙️ Technology Stack

The laboratory and production ecosystem relies on the following software and systems pillars:

*   **Operating Systems:** RHEL, Debian, Ubuntu.
*   **Virtualization & Compute:** Proxmox VE.
*   **Storage:** TrueNAS.
*   **Containerization:** Docker, Podman.

## 📚 Documentation

> **Note:** Technical infrastructure documentation is currently under development.

Coming soon, the `docs/` directory of this repository will centralize:
*   Network topology diagrams.
*   Platform architecture decisions.
*   Disaster recovery and operational maintenance procedures.
