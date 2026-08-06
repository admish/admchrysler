---
title: Résumé (CV)
layout: page
---

*Updated July 2026. Full CV with contact details available on request via [LinkedIn](https://www.linkedin.com/in/adium/).*

**Infrastructure and Platform Engineer** · Upstate New York · [LinkedIn](https://www.linkedin.com/in/adium/) · [GitHub](https://github.com/admish)

Infrastructure and platform engineer with 20+ years running production systems end to end. Eight years as sole IT owner of a Cornell University research institute serving roughly 200 users: 900 TB of RAID6 storage, seven GPU compute nodes, and 35 production web properties with zero data-loss incidents. Currently design and operate a heterogeneous 20-host platform running 110+ services behind SSO, a CrowdSec IDS edge, self-hosted GitLab CI, and Prometheus observability.

## Employment

### Systems Administrator | Plan First Technologies | 2024 to 2026 | Cortland, NY
* Tier 2 escalation across Windows, macOS, and Linux for a regional MSP supporting 100+ managed client organizations.
* Built and maintained the firm's Windows provisioning tooling: a self-elevating PowerShell configuration script delivered through a one-line bootstrap, applied to every new and remediated system.
* Authored the Microsoft 365 account-compromise incident response playbook: Entra ID sign-in analysis, session and MFA revocation sequencing, and blast-radius assessment.
* Hardened Microsoft 365 tenants with Conditional Access policies, MFA enforcement, and Huntress EDR/ITDR. Deployed BitLocker fleet-wide with NinjaOne recovery-key escrow.
* Root-caused an office-wide Windows Update failure scoped for 12 machine rebuilds to a single SonicWall Gateway AV setting stripping BITS byte-range headers. Resolved in under two hours.
* Built a 900+ document technical knowledge base spanning 100+ client environments on personal initiative.

### IT Manager | Cornell University, Weill Institute for Cell and Molecular Biology | 2014 to 2022 | Ithaca, NY
* Sole IT staff for a research institute of roughly 200 users. Owned the entire stack: infrastructure, security, procurement, and end-user support.
* Maintained 900 TB of RAID6 network-attached storage across eight years with zero data-loss incidents.
* Built and administered seven GPU compute nodes for machine learning, image analysis, and computational biology workloads.
* Operated 35 production web properties on Apache and NGINX with Python, PHP, SQL, and Flask backends.
* Administered JupyterHub environments with reproducible per-group Conda deployments; MySQL and PostgreSQL administration and tuning.
* Supported a mixed macOS and Windows fleet of about 300 devices alongside Linux computational servers.

### Technology Consultant | Cornell University, The Cornell Store | 2013 to 2014 | Ithaca, NY
* Campus-wide volume software licensing and primary contact for Apple hardware procurement across the university.

### Web Designer and Developer | Self-Employed | 2005 to 2012 | Martinez, CA
* Built and maintained client websites, intranet portals, and database-driven web applications on LAMP/LEMP stacks.
* Independently built and operated a community website reaching 500,000 unique visitors per month, including capacity scaling, DDoS mitigation, and defense against fraudulent DMCA claims.

### Communications Sergeant, MOS 25Q | United States Army | 2003 to 2007 | Fort Campbell, KY
* Established secure tactical communications networks over TROPO satellite, CX cable, CODEM, and UHF line-of-sight.
* Company-level COMSEC custodian accountable for classified encryption keys and over $11 million in communications equipment.
* Lead instructor for a 14-module advanced operator course on the Defense Advanced GPS Receiver (DAGR).
* Held a Secret security clearance for the duration of service.

## Platform Engineering

Designed, built, and operate a production internal developer platform across roughly 20 physical hosts: a 14-node Proxmox VE cluster running about 110 services (LXC and Docker), Ceph distributed storage, self-hosted GitLab CE with CI runners on Linux and Windows, Prometheus/Alertmanager/Grafana/Graylog observability, CrowdSec IDS at the NGINX ingress, Authentik/Authelia SSO with OIDC, an internal certificate authority, and n8n workflow automation. Documented in a 468-page self-hosted MediaWiki.

## Skills

**Linux and OS:** Debian, Ubuntu, RHEL/CentOS, Windows Server, macOS · **Virtualization:** Proxmox VE, KVM/QEMU, Hyper-V, VMware ESXi, LXC, Docker · **Networking:** DNS (split-horizon), VLAN segmentation, Ubiquiti UniFi, WireGuard, Cloudflare Tunnel, NGINX · **Security:** CrowdSec, ModSecurity/OWASP CRS, OIDC SSO, PKI, Vaultwarden, Conditional Access, incident response · **Observability:** Prometheus, Alertmanager, Grafana, InfluxDB, Graylog · **Platform:** GitLab CE and CI, SonarQube, n8n, Elasticsearch · **Data:** ZFS, Ceph, MySQL/MariaDB, PostgreSQL · **Scripting:** Bash, Python, PowerShell

## Education

Associate of Arts, Digital Media and Web Design, Diablo Valley College, 2012 · U.S. Army technical training (25U), 2003 to 2006
