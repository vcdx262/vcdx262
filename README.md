# Steven Slocum — VCDX #262

**Virtualization Solutions Architect.** I design and automate software-defined datacenters
and the platforms that run on them — across VMware, Microsoft, and Nutanix — with
infrastructure-as-code, repeatable runbooks, and validation you can reproduce.

VMware Certified Design Expert (**VCDX #262**) · SANS/GIAC-certified · 10+ years across
enterprise virtualization, cloud, and solutions architecture.

## Portfolio

| Repo | What's inside |
|---|---|
| **[VMware](https://github.com/vcdx262/VMware)** | PowerCLI toolkit — nested-ESXi deploy, broad host verification, VDS/portgroup automation, CSV-driven VM provisioning, VCSA deploy specs, iDRAC/UCS audits — plus **Terraform IaC** for a VMware Cloud Foundation / OCVS SDDC |
| **[MicroSoft](https://github.com/vcdx262/MicroSoft)** | **Hyper-V** build-out (install, switch/VM provisioning, inventory/capacity/replication, standalone + failover-cluster runbooks), Active Directory build & audit, **Azure AVD** (Bicep IaC, decision records, security design), and Excel test plans |
| **[Nutanix](https://github.com/vcdx262/Nutanix)** | **Prism Central v4 REST** reference toolkit — connection helper, AHV estate inventory, alert reporting |
| **[OffSec](https://github.com/vcdx262/OffSec)** | Security research lab — native Windows controls vs. WinRM lateral movement (SANS Master's white paper; Bicep lab + reproducible, zero-drift test harness) |

## Focus

`vSphere / VCF` · `NSX` · `vSAN` · `HCX` · `PowerCLI` · `Azure / AVD` · `Hyper-V` ·
`Nutanix AHV` · `Terraform` · `Bicep` · `IaC & automation`

## How these repos are built

- Every PowerShell script carries comment-based help; mutating scripts support `-WhatIf`.
- Consistent reporting pattern (`[pscustomobject]` → `Export-Csv`) and CSV-driven inputs.
- Deployment runbooks and phase-by-phase Excel validation test plans accompany the code.
- Lab values and placeholder secrets throughout — `PSScriptAnalyzer` clean.

---

*VCDX #262 — VMware Certified Design Expert.*
