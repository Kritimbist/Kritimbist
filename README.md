<div align="center">

<!-- Datacenter Server Chassis Animated Header -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=cylinder&color=0:050811,50:091428,100:001428&height=220&section=header&text=KRITIM%20BISTA&fontSize=56&fontColor=00ff66&fontAlignY=38&desc=BARE-METAL%20DEVSECOPS%20//%20PHYSICAL%20INFRASTRUCTURE%20SECURITY&descAlignY=62&descColor=38bdf8&animation=fadeIn"/>

<!-- Hardened Typing Console (Zero-Truncation Geometry) -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&pause=1200&color=00FF66&background=00000000&center=true&vCenter=true&width=720&lines=root%40bastion%3A~%23+init+bare_metal_pipeline;Hardware+Root-of-Trust%3A+TPM+2.0+%26+Measured+Boot+%F0%9F%94%90;Securing+Physical+Servers%2C+Hypervisors+%26+Enclaves+%F0%9F%9B%A1%EF%B8%8F;Proxmox+VE+%E2%80%A2+Talos+Linux+%E2%80%A2+Bare-Metal+K8s+%E2%9A%A1;Kernel+Runtime+Defense+via+eBPF+%26+Falco+%F0%9F%A7%AC;Automating+Zero-Trust+Air-Gapped+Delivery+%F0%9F%9A%80" alt="Typing Terminal Animation" />
</a>

<br/>

<!-- Real-Time Hardware & Enclave Telemetry Badges -->
<img src="https://img.shields.io/badge/INFRASTRUCTURE-BARE--METAL%20RACK-0f172a?style=flat-square&logo=serverfault&logoColor=00ff66" alt="Bare Metal"/>
&nbsp;
<img src="https://img.shields.io/badge/SILICON%20TRUST-TPM%202.0%20SEALED-0f172a?style=flat-square&logo=securityscorecard&logoColor=00ff66" alt="TPM 2.0"/>
&nbsp;
<img src="https://img.shields.io/badge/NETWORK-VLAN%20%2F%20IPMI%20ISOLATED-0f172a?style=flat-square&logo=wireguard&logoColor=38bdf8" alt="Network Isolation"/>
&nbsp;
<img src="https://img.shields.io/badge/RUNTIME-eBPF%20ENFORCED-0f172a?style=flat-square&logo=linux&logoColor=38bdf8" alt="eBPF"/>
&nbsp;
<img src="https://img.shields.io/badge/RUNNERS-AIR--GAPPED-0f172a?style=flat-square&logo=githubactions&logoColor=f59e0b" alt="Runners"/>

</div>

---

## 🖥️ Node Telemetry & Environment Manifest (`/etc/bastion/audit.toml`)

```toml
[node_identity]
hostname         = "core-baremetal-01"
operational_tier = "Tier-3 Datacenter / On-Prem Sovereign Enclave"
primary_role     = "Bare-Metal DevSecOps // Systems Hardening"
root_of_trust    = "TPM 2.0 Cryptographic Attestation + UEFI Measured Boot"

[compute_and_virtualization]
hypervisor       = "Proxmox VE 8.x (Type-1 KVM / Hardened LXC Enclaves)"
os_fabric        = "Talos Linux (Immutable Rootfs) // Hardened Debian Minimal"
orchestrator     = "Kubernetes on Raw Iron (Self-Hosted Control Planes)"

[security_mandate]
mission_statement = "Enforcing end-to-end security from raw silicon to orchestrator runtimes."
protocols = [
  "Out-of-band IPMI/iDRAC network isolation via dedicated non-routable VLANs",
  "Zero-touch immutable server provisioning via network iPXE automation",
  "In-kernel real-time attack detection via Cilium eBPF and Falco syscall hooks",
  "Air-gapped self-hosted CI/CD runners with offline vulnerability gating"
]
