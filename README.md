<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=1a365d&height=200&section=header&text=Guillermo%20Farf%C3%A1n&fontSize=44&fontColor=ffffff&fontAlignY=38&desc=Senior%20Cloud%20Architect%20%7C%20Tech%20Lead%20%7C%20Software%20Engineer&descAlignY=58&descSize=17" alt="Banner" />

<p>
  <a href="https://gfarfan.dev/">
    <img src="https://img.shields.io/badge/Portafolio-1a365d?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portafolio" />
  </a>
  <a href="https://www.linkedin.com/in/guillermo-farfan/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://www.credly.com/users/fernando-farfan.855a5067/badges">
    <img src="https://img.shields.io/badge/Credly%20Badges-FF6B00?style=for-the-badge&logo=credly&logoColor=white" alt="Credly Badges" />
  </a>
  <a href="https://gfarfan.dev/#contact">
    <img src="https://img.shields.io/badge/Contacto-2b6cb0?style=for-the-badge&logo=mail.ru&logoColor=white" alt="Contacto" />
  </a>
</p>

<img src="https://komarev.com/ghpvc/?username=fernandofarfan&color=2b6cb0&style=flat-square&label=Profile+Views" alt="Profile Views" />

</div>

---

## 👨🏻‍💻 Acerca de mí

🚀 **Senior Cloud Solutions Architect, Virtualization & Migrations Specialist & Tech Lead** con más de 8 años de experiencia diseñando arquitecturas cloud resilientes (**GCP & Azure**), plataformas de virtualización enterprise (**Microsoft Hyper-V 2025 & VMware vSphere**), migraciones masivas corporativas (**M4CE, Veeam VBR, SAP BW on HANA**) y microservicios backend asíncronos de alta disponibilidad.

Combino mi formación técnica en Sistemas de Información (UTN) con estudios universitarios avanzados en Relaciones del Trabajo (UBA), liderando equipos de ingeniería (6+ desarrolladores) con rigor técnico, cultura ágil y foco en eficiencia operativa y financiera (**FinOps**).

```typescript
const guillermo: EngineerProfile = {
  ubicacion:    "Salta / Buenos Aires, Argentina (UTC-3 · Open to Remote / Relocation)",
  roles:        [
    "Senior Cloud Solutions Architect",
    "Technical Lead",
    "Lead Infrastructure & Virtualization Specialist",
    "Senior Python Backend Engineer",
    "DBA & Data Engineer"
  ],
  experiencia:  "8+ años en TI, Arquitectura Cloud & Ingeniería de Software",

  stack: {
    cloud_infra: [
      "Google Cloud Platform (Compute Engine m2/n2, GKE, Cloud Run, M4CE, Shared VPC)",
      "Microsoft Azure (Migraciones Azure → GCP)",
      "Microsoft Hyper-V 2025 (SET 40 Gbps, Live Migration 20 Gbps)",
      "VMware vSphere / ESXi",
      "SAN Fibre Channel HPE Alletra / 3PAR (55 TB CSV, MPIO)",
      "Veeam Backup & Replication (VBR)",
      "Terraform / Terragrunt",
      "Docker & Kubernetes (GKE Autopilot / Standard)",
      "GitOps (ArgoCD, GitHub Actions)"
    ],
    backend_apis: [
      "Python 3.10+ (FastAPI, Celery, SQLAlchemy 2.0, Pydantic v2, Django REST)",
      "Java 17 (Spring Boot, Microservicios)",
      "TypeScript & Node.js"
    ],
    databases_data: [
      "PostgreSQL (pgvector, Particionamiento)",
      "Microsoft SQL Server (2012–2022, AlwaysOn)",
      "SAP HANA 2.0 IaaS & Conector Backint para GCS",
      "Google BigQuery",
      "Redis (Caché distribuida, Pub/Sub)"
    ],
    observability_sre: [
      "IBM Instana APM",
      "OpenTelemetry (OTel)",
      "Zabbix",
      "Prometheus & Grafana",
      "Métricas DORA & FinOps"
    ]
  },

  metricas_clave: [
    "Migración masiva de 75 servidores corporativos a GCP (68 VMs con M4CE + 7 nodos SAP BW on HANA sobre SLES)",
    "Arquitectura y certificación en vivo de clúster HA Hyper-V 2025 (3 blades HPE Synergy, SAN 55 TB CSV, 5 días antes de plazo)",
    "Reducción sostenida del 28% en costos mensuales cloud mediante FinOps en Google Cloud Platform",
    "Lead time de despliegue reducido de 5 días a minutos bajo demanda (Zero-Downtime GitOps con ArgoCD)",
    "Reducción del 55% en latencia p95 de consultas complejas en bases de datos críticas de 8+ TB",
    "Reducción del 45% en el MTTR mediante observabilidad full-stack con IBM Instana APM y OpenTelemetry"
  ]
};
```

---

## 🏢 Hitos Recientes & Proyectos Corporativos

| Empresa / Cliente | Alcance & Arquitectura | Tecnologías Clave |
|---|---|---|
| **Grupo Ramos** | **Migración Cloud Masiva (75 Servidores a GCP):**<br/>• Migración de 68 VMs en Fases I y II (~19.5 TB en 6 olas: AD, PAM, FortiAnalyzer 7 TB, Facturación NCF, Azul SFTP 5.4 TB) mediante M4CE y Landing Zone con Terraform (Shared VPC, GKE).<br/>• Migración Multi-Cloud SAP BW on HANA (Azure → GCP): 7 servidores SLES 15.5/15.6, instancia HANA PRD en `m2-ultramem-208` (208 vCPUs, 5.8 TB RAM) con Hyperdisk Extreme, NLB interno para ASCS e ingesta acelerada de ~2.9 TB vía SAP Backint a GCS + SAP CAR Rise en SLES 15 SP7. | GCP · Terraform · M4CE · GKE · SLES 15 for SAP · SAP HANA · Hyperdisk Extreme · Shared VPC · FinOps |
| **Universal Group, Inc.**<br/>*(Swan Technologies)* | **Clúster Bare-Metal HA Microsoft Hyper-V 2025 & SAN 55 TB:**<br/>• Diseño, despliegue bare-metal, hardening (COBIT/Qualys) y certificación en vivo (5 días antes de plazo) del clúster HA `HVDevCluster1` en Windows Server 2025 sobre 3 blades HPE Synergy 480 Gen10 (108 cores, 1.5 TB RAM).<br/>• Storage SAN HPE Alletra/3PAR (11 CSVs = 55 TB, MPIO Round Robin), red SET 40 Gbps con Live Migration a 20 Gbps (0% pérdida) y migración piloto de 20 VMs (~4.05 TB en RHEL 8 UEFI Gen 2 y Windows Server) con Veeam VBR. | Windows Server 2025 · Hyper-V · HPE Synergy · HPE Alletra / 3PAR · SAN FC · SET 40G · Veeam VBR · RHEL 8 |
| **Reforest Latam** | **Liderazgo Técnico, GitOps & FinOps en GCP:**<br/>• Dirección de equipo (6 devs), arquitectura de microservicios en FastAPI / Celery / Redis (-45% en latencia de consultas) y React 18 / TypeScript (-40% en llamadas redundantes).<br/>• Estrategia FinOps (-28% en costos cloud), Zero-Trust IAM/Cloud Armor y GitOps con GitHub Actions y ArgoCD hacia GKE Autopilot y Cloud Run. | GCP · GKE Autopilot · Cloud Run · Terraform · ArgoCD · Python (FastAPI) · PostgreSQL · React 18 · FinOps |
| **Junta de Beneficencia de Guayaquil** | **Observabilidad APM & SRE de Misión Crítica:**<br/>• Despliegue de IBM Instana APM sobre infraestructura Nutanix AHV (.NET, IIS, SQL Server) integrado con OpenTelemetry y Zabbix, reduciendo el MTTR un 45%. | IBM Instana APM · OpenTelemetry · Nutanix AHV · SQL Server · Zabbix · SRE |

---

## 🚀 Proyectos Open Source & Hackathons

| Proyecto | Descripción | Stack Tecnológico |
|---|---|---|
| [**Autonomous FinOps Engine**](https://github.com/Fernandofarfan/Autonomous-FinOps-Engine) | Motor autónomo que escanea GCP detectando infraestructura ociosa y genera código Terraform para remediación automática de costos. *(Aleph Hackathon 2026)* | Python · Terraform (IaC) · GCP APIs · Jinja2 |
| [**OmniSync Event Engine**](https://github.com/Fernandofarfan/OmniSync-Polyglot-Event-Driven-Engine) | Motor orientado a eventos (EDA) para transacciones distribuidas, consistencia eventual y Dead Letter Queues (DLQ). | Java Spring Boot · Cloud Pub/Sub · Docker · EDA |
| [**Monitor CI/CD (DORA Metrics)**](https://github.com/Fernandofarfan/Monitor-CI-CD) | Dashboard en tiempo real para telemetría de pipelines integrado con GitHub Actions y evaluación bajo estándar DORA. | TypeScript · Node.js · WebSockets · PostgreSQL |
| [**AI Job Matching Platform**](https://github.com/Fernandofarfan/ai-job-matching-platform) | Plataforma inteligente con procesamiento de lenguaje natural (NLP) para scoring y matching de perfiles técnicos. | Python · FastAPI · NLP · Redis · Vector Search |

---

## 🛠️ Stack Técnico

<div align="center">

**Cloud, Virtualización & DevOps**
<br/>
<img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
<img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Hyper--V_2025-0078D4?style=flat-square&logo=windows&logoColor=white" />
<img src="https://img.shields.io/badge/VMware_vSphere-607078?style=flat-square&logo=vmware&logoColor=white" />
<img src="https://img.shields.io/badge/Veeam_VBR-00B336?style=flat-square&logo=veeam&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/ArgoCD-EF6B48?style=flat-square&logo=argo&logoColor=white" />
<img src="https://img.shields.io/badge/SUSE_SLES_SAP-0C322C?style=flat-square&logo=suse&logoColor=white" />

<br/><br/>

**Backend, Datos & Observabilidad**
<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" />
<img src="https://img.shields.io/badge/SAP_HANA-008FD3?style=flat-square&logo=sap&logoColor=white" />
<img src="https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/Java_Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white" />
<img src="https://img.shields.io/badge/IBM_Instana-052FAD?style=flat-square&logo=ibm&logoColor=white" />

</div>

---

## 🎓 Certificaciones Verificables en Credly & Coursera

* 📜 **IBM DevOps and Software Engineering Professional Certificate** (IBM / Credly)
* 📜 **IBM Full Stack Software Developer Professional Certificate (V5)** (IBM / Credly)
* 📜 **IBM Java Developer Professional Certificate V2** (IBM / Credly)
* 📜 **IBM JavaScript Backend Developer Professional Certificate V2** (IBM / Credly)
* 📜 **Google Data Analytics Professional Certificate** (Google / Credly)
* 📜 **Meta Full-Stack Engineer Certificate & Meta Back-End Developer Certificate** (Meta / Credly)
* 📜 **Google Cloud Fundamentals: Core Infrastructure** (Google Cloud)
* 📜 **IBM Security for Professionals and DevOps Professionals** (IBM / Credly)
* 📜 **IBM IT Scrum Master Specialization** (IBM / Coursera)

👉 [Ver todas las 11 credenciales verificadas en mi perfil oficial de Credly](https://www.credly.com/users/fernando-farfan.855a5067/badges)

---

## 📫 Contacto

* 📧 **Email:** [fernando.farfan16@gmail.com](mailto:fernando.farfan16@gmail.com)
* 🌐 **Sitio Web:** [gfarfan.dev](https://gfarfan.dev/)
* 💼 **LinkedIn:** [linkedin.com/in/guillermo-farfan](https://www.linkedin.com/in/guillermo-farfan/)
* 📱 **WhatsApp:** [+54 9 11 2187-1473](https://wa.me/5491121871473)
* ✉️ **Formulario Directo:** [https://gfarfan.dev/#contact](https://gfarfan.dev/#contact)
