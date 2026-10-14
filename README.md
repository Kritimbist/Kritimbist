<div align="center">

<!-- Animated Header -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:090d16,50:0f172a,100:1e293b&height=220&section=header&text=Kritim%20Bista&fontSize=62&fontColor=38bdf8&fontAlignY=36&desc=DevSecOps%20Engineer%20%7C%20Cloud%20Security%20%7C%20CI%2FCD%20Architect&descAlignY=58&descColor=94a3b8&animation=fadeIn"/>

<!-- Typing Animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=650&lines=DevSecOps+Engineer+%F0%9F%9B%A1%EF%B8%8F;Automating+Shift-Left+Security+%F0%9F%94%92;Kubernetes+%26+Cloud+Native+Architect+%E2%98%B8%EF%B8%8F;Infrastructure+as+Code+Practitioner+%E2%98%81%EF%B8%8F;Zero-Trust+Pipeline+Hardener+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/>

<!-- Live Badges -->
<img src="https://komarev.com/ghpvc/?username=kritimbista&label=Shields%20Active%20(Views)&color=0284c7&style=flat-square" alt="profile views"/>
&nbsp;
<img src="https://img.shields.io/github/followers/kritimbista?label=Network&style=flat-square&color=0284c7" alt="followers"/>
&nbsp;
<img src="https://img.shields.io/badge/Security-Shift--Left-success?style=flat-square&logo=securityscorecard&logoColor=white" alt="Shift Left"/>
&nbsp;
<img src="https://img.shields.io/badge/Status-Securing%20Pipelines-blue?style=flat-square" alt="status"/>

</div>

---

## 🛡️ Pipeline Manifest (`devsecops.yml`)

```yaml
name: Kritim Bista
role: DevSecOps Engineer
focus: [ CI/CD Hardening, Shift-Left Security, Cloud Governance, GitOps ]

on:
  pipeline_lifecycle:
    branches: [ staging, production ]
    scans: [ SAST, DAST, SCA, Container-Audit ]

jobs:
  secure_and_deploy:
    runs-on: cloud-native
    environment: zero-trust
    steps:
      - name: Philosophy
        run: echo "Baking security directly into code and delivery pipelines, never as a roadblock."

      - name: Core Mission
        run: |
          - Enforcing automated vulnerability scanning & policy-as-code
          - Architecting resilient, self-healing Kubernetes infrastructure
          - Standardizing cloud resources with Immutable Infrastructure (IaC)
          - Maintaining 99.9% uptime with end-to-end telemetry and observability
