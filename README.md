# Secure Network Architecture & Troubleshooting

**QuickStart / University of New Mexico Cybersecurity Bootcamp — Guided Career Simulation 1**

**Focus:** Virtual networking · Network services · DHCP/DNS troubleshooting · Nmap scanning · Wireshark traffic analysis

## Portfolio snapshot

| | |
| --- | --- |
| **Challenge** | Restore connectivity and assess a virtual small-business network in a guided training scenario. |
| **My documented work** | DHCP troubleshooting; DNS configuration review; Nmap service discovery; controlled FTP transfer and Wireshark traffic inspection. |
| **Observed result** | The recorded submission shows restored lab website access and a completed training FTP transfer. |
| **Security takeaway** | Verify configuration and exposed services, avoid unencrypted file transfers for sensitive data, reduce privileges and patch systems. |

**Also see:** [Linux Authentication Monitor](https://github.com/TechhyyBear/Linux-authentication-monitor) — a separately developed, independent Bash/journalctl lab.

## Project overview

This project documents a guided cybersecurity training scenario in which an organization needed a network upgrade with limited budget and physical space. Instead of adding physical hardware, the exercise used an Oracle VirtualBox environment with virtualized hosts and network services.

The submitted presentation records configuration and troubleshooting of a CEO workstation, router/firewall, DNS server and web server. The project also used Kali Linux tools to inspect exposed network services and captured a controlled FTP exchange in Wireshark.

**Scope:** An authorized instructional simulation. The scenario's organizational role and customer are fictional/training context; this was not an enterprise deployment or professional consulting engagement.

## Objectives

- Build and troubleshoot a multi-machine virtual network with relevant services.
- Restore workstation connectivity and demonstrate access to the lab website.
- Inspect DNS and host network configuration.
- Transfer a lab policy file using FTP and examine the associated traffic.
- Identify exposed services with Nmap and propose basic hardening steps.

## Lab environment

| Component | Purpose in the exercise |
| --- | --- |
| Oracle VirtualBox | Host the isolated virtual systems |
| Router/firewall VM | Provide lab network connectivity and segmentation functions |
| CEO workstation | Test host connectivity, web access, and file transfer |
| DNS server | Support name-resolution configuration and service inspection |
| Web server | Host the lab site and policy file for retrieval |
| Kali Linux | Run authorized scanning and packet-analysis tools |
| Nmap / Wireshark | Inspect open ports and captured network traffic |

The component map is a **high-level description of the lab roles**, not a verified cable-level topology or claim about exact firewall rules. See [Lab workflow and architecture](LAB_WORKFLOW.md).

## Documented activities

1. Reviewed host addressing with Linux network commands and investigated a connectivity failure involving the CEO workstation.
2. Changed the relevant workstation connection from a manually configured setting to automatic DHCP in the exercise and demonstrated access to the lab site (`seclab.net`).
3. Reviewed DNS resolver configuration, including `/etc/resolv.conf`.
4. Retrieved the **Social-Media-Security-Policy** training file from the web server using FTP.
5. Used Nmap to inspect DNS-server ports and Wireshark to review the FTP exchange.
6. Presented recommendations involving software updates, removal of unnecessary services, role-based permissions, and avoiding unnecessary executive administrative privileges.

These activities are documented in the submitted video. The project does **not** claim that every configuration step or firewall rule was independently tested after the presentation.

## Results and security observations

- The lab website was displayed after the connectivity troubleshooting exercise.
- A controlled FTP file transfer and related network-service examination were documented.
- The original Wireshark capture showed lab FTP credentials in plaintext. The credentials and capture are withheld; the example illustrates why unencrypted file-transfer protocols are unsuitable for sensitive information.
- The proposed hardening measures address exposed services, patching and privileged access at a foundational level.

## Evidence and publication controls

- [Evidence index](EVIDENCE_INDEX.md): source traceability, observed results and evidence limitations. This is intentionally a text-only portfolio.
- [Lab workflow and architecture](LAB_WORKFLOW.md): phase-by-phase account and a conceptual topology diagram.
- The original video remains in private project records and is not reproduced in this repository.
- Some original terminal screenshots contain usernames, FTP credentials or lab-specific material. **No raw video frames, packet captures, credentials or VM images are published here.**

**Portfolio presentation:** This repository intentionally uses source-grounded text documentation rather than published source media.

## Skills demonstrated

Virtual network configuration, network troubleshooting, DHCP/DNS fundamentals, Linux host-network inspection, Nmap service discovery, Wireshark packet inspection, documentation and security recommendations.

## Limitations

This is an educational, instructor-demonstrated then student-executed lab, not evidence of production network administration, advanced firewall engineering, or independent enterprise architecture. Some source details come from presentation commentary; no independent replay of the VMs was performed for this portfolio reconstruction. Findings are scoped to the submitted simulation.

**Original source:** the Career Simulation 1 submitted presentation video (approximately 10 minutes 24 seconds), retained privately. Its original filename and submission records are preserved outside GitHub.
