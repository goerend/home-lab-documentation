# Home Lab Documentation

**Hands-on IT infrastructure, systems administration, hardware diagnostics, backup & recovery, and scripting using Bash and Python.**

Welcome to my home lab portfolio. This repository documents practical IT projects, technical investigations and lessons learned while building and maintaining my own computing environment.

My focus is on developing practical skills, understanding how systems work, troubleshooting problems methodically, and recording procedures and results in clear, reusable documentation.

## Featured Projects

### Desktop RAM Configuration and Validation

Configured Kingston DDR4 memory to operate at 3200 MT/s using XMP Profile 1 and validated the configuration with a four-pass PassMark MemTest86 test.

- **Environment:** ASRock B550M PG Riptide, AMD Ryzen 5 5600X, 32 GB Kingston DDR4.
- **Configuration:** DDR4-3200 MT/s, XMP Profile 1.
- **Validation:** Four passes completed, 48/48 tests passed, and zero reported memory errors.
- **Evidence:** Configuration details, test results and supporting screenshots.

[**View the full project report →**](desktop-ram-validation/README.md)

### Windows PC Backup to NAS Using Veeam

Configured daily whole-computer backups from Windows 11 Pro to a network share on a Debian/OpenMediaVault NAS.

The project documents storage-capacity issues, an unsuccessful backup-chain migration, the establishment of a new backup job, and verification of a file-level restore using matching SHA-256 checksums.

- **Environment:** Windows 11 Pro, Veeam Agent for Microsoft Windows, Debian and OpenMediaVault.
- **Skills demonstrated:** Backup configuration, NAS integration, troubleshooting, and data-integrity verification.
- **Validation:** A restored file was checked against its original SHA-256 checksum.
- **Known limitation:** Full-system recovery has not been tested.

[**View the full project report →**](veeam-windows-backup-to-nas/README.md)

## Home Lab Overview

I use my home lab to complement my IT studies with practical experience across hardware, operating systems, storage, virtualisation, networking and data protection.

My environment includes several systems with different roles:

| System or platform | Role |
|---|---|
| Proxmox VE | Server virtualisation and lab infrastructure |
| Debian and OpenMediaVault | NAS, storage and file services |
| Ubuntu Desktop | Linux administration, hardware testing and daily experimentation |
| Windows 11 | Desktop administration and backup & recovery testing |
| External and enterprise storage | Backup copies, drive diagnostics and storage experiments |

This environment provides opportunities to practise administration across Linux and Windows, investigate hardware behaviour, and explore reliable ways to store and protect data.

## Projects and Technical Development

### Hardware Diagnostics and Validation

Document hardware configuration changes, establish a baseline, run diagnostic tests, and evaluate the results.

**Completed project:** [Desktop RAM Configuration and Validation](desktop-ram-validation/README.md)

**Focus areas:** UEFI/BIOS configuration, memory compatibility, diagnostic testing and stability validation.

### Storage and NAS Administration

Evaluate storage devices before putting them into service and document storage design decisions.

Work includes enterprise hard-drive health checks, SMART diagnostics and planning storage for OpenMediaVault.

**Focus areas:** drive health, extended tests, storage organisation, monitoring and data integrity.

### Backup and Recovery

Document backup procedures and the measures used to protect data against hardware failure, accidental deletion and other incidents.

Work includes Windows system-image backups with Veeam Agent, recovery media preparation, offline backup copies, off-site cloud backups, and verification procedures.

**Completed project:** [Windows PC Backup to NAS Using Veeam](veeam-windows-backup-to-nas/README.md)

The project covers daily whole-computer backups from Windows 11 Pro to a network share on a Debian/OpenMediaVault NAS. It documents storage-capacity issues and an unsuccessful backup-chain migration, followed by the creation of a new backup job. A file-level restore was verified using matching SHA-256 checksums. Full-system recovery has not been tested.

**Focus areas:** backup planning, verification, recovery readiness and reducing exposure of backup copies.

### Linux and Systems Administration

Develop practical Linux skills through Ubuntu and Debian administration, Bash scripting, command-line exercises and troubleshooting.

**Focus areas:** shell commands, permissions, services, logs, system configuration and repeatable procedures.

### Virtualisation and Networking

Explore virtual machines, server configuration, network connectivity and infrastructure design through the home lab.

**Focus areas:** Proxmox VE, virtualisation concepts, network configuration and troubleshooting.

### Python Programming

Python programming is an area of ongoing development.

I am currently enrolled in a Python Junior Developer Track and plan to document practical exercises and small scripts as I complete and validate them.

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

Rather than documenting only successful outcomes, I also record problems, unsuccessful attempts and lessons learned. Project results and conclusions reflect what was actually observed in my environment.

This is a personal learning environment. The documentation describes practical experience with the specific systems tested; results are not presented as universal guarantees.

**Safety note:** This portfolio documents experiments in a personal learning environment. Hardware, storage, and system-configuration changes may cause data loss or service disruption if applied incorrectly. Review the instructions carefully, verify commands and device identifiers, and maintain appropriate backups before reproducing a procedure. **Proceed at your own risk!**

Sensitive information is excluded from public documentation.

---

*This portfolio is a work in progress and will evolve as I develop my technical skills and complete further home lab projects.*
