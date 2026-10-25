# Home Lab Documentation

**Hands-on IT infrastructure, systems administration, hardware diagnostics and backup & recovery.**

Welcome to my home lab portfolio. This repository documents practical IT projects, technical investigations and lessons learned while building and maintaining my own computing environment.

My focus is on developing practical skills, understanding how systems work, troubleshooting problems methodically, and recording procedures and results in clear, reusable documentation.

## About This Portfolio

I use my home lab to complement my IT studies with practical experience across hardware, operating systems, storage, virtualisation, networking and data protection.

Rather than documenting only successful outcomes, I aim to record the reasoning behind technical decisions, the procedures followed, the evidence collected, and the lessons learned.

Projects are documented as work progresses. Test results and conclusions reflect what was actually observed in my environment.

## Home Lab Overview

My environment includes several systems with different roles:

| System or platform | Role |
|---|---|
| Proxmox VE | Server virtualisation and lab infrastructure |
| Debian and OpenMediaVault | NAS, storage and file services |
| Ubuntu Desktop | Linux administration, hardware testing and daily experimentation |
| Windows 11 | Desktop administration and backup & recovery testing |
| External and enterprise storage | Backup copies, drive diagnostics and storage experiments |

This environment provides opportunities to practise administration across Linux and Windows, investigate hardware behaviour, and explore reliable ways to store and protect data.

## Projects and Technical Work

### Hardware Diagnostics and Validation
Configure hardware, establish a baseline, run diagnostic tests and document the results.

Current work includes validating DDR4 memory at its rated transfer rate using XMP and PassMark MemTest86.

**Focus areas:** UEFI/BIOS configuration, memory compatibility, diagnostic testing and stability validation.

### Storage and NAS Administration
Evaluate storage devices before putting them into service and document storage design decisions.

Work includes enterprise hard-drive health checks, SMART diagnostics and planning storage for OpenMediaVault.

**Focus areas:** drive health, extended tests, storage organisation, monitoring and data integrity.

### Backup and Recovery
Document backup procedures and the measures used to protect data against hardware failure, accidental deletion and other incidents.

Work includes Windows system-image backups with Veeam Agent, recovery media preparation, offline backup copies, off-site cloud backups, and verification procedures.

**Focus areas:** backup planning, verification, recovery readiness and reducing exposure of backup copies.

### Linux and Systems Administration
Develop practical Linux skills through Ubuntu and Debian administration, Bash scripting, command-line exercises and troubleshooting.

**Focus areas:** shell commands, permissions, services, logs, system configuration and repeatable procedures.

### Virtualisation and Networking
Explore virtual machines, server configuration, network connectivity and infrastructure design through the home lab.

**Focus areas:** Proxmox VE, virtualisation concepts, network configuration and troubleshooting.

Detailed project reports and supporting evidence will be added as individual projects are completed.

## How I Document Projects

Where relevant, each project includes:

1. **Objective and scope** — the problem or task being addressed.
2. **Environment** — the relevant hardware, software and versions.
3. **Initial state** — the configuration before changes were made.
4. **Procedure** — the steps followed and the reasons for important decisions.
5. **Validation** — tests performed and evidence collected.
6. **Results** — observed outcomes, limitations and any outstanding issues.
7. **Lessons learned** — what worked, what did not, and what I would do differently.

Screenshots, command output, configuration examples and test reports are included where they help explain or substantiate the work.

## Approach

I aim to make technical changes carefully, validate the outcome, preserve recovery options where appropriate, and document the process so it can be understood and repeated.

This is a personal learning environment. The documentation describes practical experience with the specific systems tested; results are not presented as universal guarantees.

Sensitive information is excluded from public documentation.

---

*This portfolio is a work in progress and will evolve as I develop my technical skills and complete further home lab projects.*
