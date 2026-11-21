# Evidence index — Career Simulation 1

**Publication format:** Documentation-only GitHub case study. No screenshots, original videos, packet captures, credentials, or VM images are published or required to complete this repository.

**Primary source:** The submitted QuickStart / University of New Mexico **Career Simulation 1 — Creating a Secure Network** presentation video (approximately 10 minutes 24 seconds). Original source and exact filename are preserved in private career records.

## Evidence classifications

- **Shown in original:** A frame, terminal image, or result visible in the submitted recording; it was not independently reenacted for this GitHub write-up.
- **Presented in original:** A result described in the student's submitted presentation.
- **Interpretation:** A security lesson inferred from the controlled lab; not proof of an enterprise deployment.

| Project phase | Evidence described in the original submission | Evidence type | Supported conclusion |
| --- | --- | --- | --- |
| Training scenario | Limited space and budget motivated using virtual machines | Presented | Educational virtual-network design scenario |
| Lab architecture | Router/firewall, CEO workstation, DNS and web servers, and Kali described | Presented | Multi-VM training environment |
| Connectivity | Interface/addressing troubleshooting, a switch to automatic DHCP, and later lab website display | Shown / presented | Workstation connectivity investigated and website access demonstrated |
| DNS | Linux resolver configuration, including `/etc/resolv.conf` | Shown | Name-resolution configuration reviewed |
| File transfer | Training security-policy file retrieved with FTP | Shown | Controlled file-transfer exercise |
| Port inspection | Nmap inspection of DNS host services | Shown | Basic network service discovery |
| Packet analysis | Wireshark capture associated with FTP exchange | Shown / presented | Foundational packet review |
| Recommendations | Patch software, reduce exposed services, use role-based access, limit unnecessary administrative privilege | Presented | Security improvement recommendations |

## Sensitive-source handling

The original FTP traffic view includes **lab login credentials**, and source video frames include a participant portrait. Those source materials have been intentionally excluded from GitHub. The instructional significance of plaintext FTP is described without displaying usernames or passwords. Original recordings and any derived image packages remain private and are not links for recruiters.

The source recording was previously reviewed by sampled frames and a source-linked career evidence ledger; it was not replayed as a complete fresh lab test for this documentation pass.

## Scope and limits

- Guided QuickStart/UNM educational simulation, not a production network or client engagement.
- The conceptual topology in `LAB_WORKFLOW.md` is not independently verified interface-to-subnet documentation.
- No performance metrics, production firewall rule changes, independent organizational network ownership, or continuous monitoring are asserted.
- A result visible in the submission is not proof that every intermediate command succeeded.
- The public-facing text remains a source-supported case study rather than a substitute for the original private recording.

## Decision: No screenshots

On November 20, 2026, the project operator chose a **text-only repository**. Earlier working notes considered screenshots; those are historical planning records kept in Drive/Git revision history, not outstanding portfolio requirements. **No screenshot sorting, image uploading, or lab rerun is needed to complete this documented-scope portfolio.** Any future release of source media would require a new review and decision.


## Portfolio presentation decision — optional visuals

**Current presentation choice (supersedes the November 20 'no screenshots' requirement):** Text-first case study is complete at its documented scope. Zero images are required. At most one optional, individually reviewed and redacted technical screenshot may be added later if it strengthens the explanation; do not publish the original credential-bearing FTP capture or participant portraits. This is a presentation enhancement, not a remaining test or operator task.
