<!-- Organization profile README for github.com/syntaxroot-cc -->

<p align="center">
  <a href="https://syntaxroot.cc"><img src="https://github.com/syntaxroot-cc/.github/raw/main/profile/banner.jpg" alt="SyntaxRoot: ITSM and CMDB for lean IT teams and MSPs. A product of Thought Parameters LLC." width="100%"></a>
</p>

<h1 align="center">SyntaxRoot</h1>

<h3 align="center">ITSM &amp; CMDB without the enterprise price tag</h3>

<p align="center">
  A full IT service management and configuration management platform for <b>small-to-mid IT teams and MSPs</b><br>
  who are priced out of tools like ServiceNow. Running in days, not quarters.
</p>

<p align="center">
  <a href="https://syntaxroot.cc"><img src="https://img.shields.io/badge/Website-syntaxroot.cc-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="mailto:hello@syntaxroot.cc?subject=SyntaxRoot%20invitation%20request"><img src="https://img.shields.io/badge/Request_an_invite-hello@syntaxroot.cc-0F766E?style=for-the-badge&logo=maildotru&logoColor=white" alt="Request an invite"></a>
  <a href="https://thoughtparameters.com"><img src="https://img.shields.io/badge/By-Thought_Parameters_LLC-1D4ED8?style=for-the-badge" alt="A product of Thought Parameters LLC"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Invite--only_early_access-F59E0B?style=flat-square" alt="Status: invite-only early access">
  <img src="https://img.shields.io/badge/Built_for-IT_teams_·_MSPs-334155?style=flat-square" alt="Built for IT teams and MSPs">
  <img src="https://img.shields.io/badge/Architecture-Serverless_on_AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" alt="Serverless on AWS">
  <img src="https://img.shields.io/badge/Delivered_with-Terraform_·_GitHub_Actions-7B42BC?style=flat-square&logo=terraform&logoColor=white" alt="Terraform and GitHub Actions">
</p>

---

> [!IMPORTANT]
> **SyntaxRoot is invite-only right now.** There's no self-serve signup yet. Email **[hello@syntaxroot.cc](mailto:hello@syntaxroot.cc?subject=SyntaxRoot%20invitation%20request)** with your team size and what you track today, and we'll set up a walkthrough and send your organization an invitation.

---

## 📇 Contents

[Why SyntaxRoot](#-why-syntaxroot) · [Capabilities](#-capabilities) · [Platform](#%EF%B8%8F-platform--security) · [Integrations](#-integrations) · [Architecture](#%EF%B8%8F-architecture) · [Getting Access](#-getting-access) · [Open Source](#-open-source) · [About](#-about-thought-parameters)

---

## 🎯 Why SyntaxRoot

If your team has outgrown spreadsheets and shared inboxes for tracking incidents and assets, but a ServiceNow-scale deployment is out of reach on budget, headcount, or timeline, SyntaxRoot is built for that gap.

| | Spreadsheets &amp; shared inboxes | Enterprise ITSM suites | **SyntaxRoot** |
| :-- | :--: | :--: | :--: |
| Incident, problem &amp; change workflows | ❌ | ✅ | ✅ |
| CMDB with relationship mapping | ❌ | ✅ | ✅ |
| Automated cloud discovery | ❌ | ✅ | ✅ (AWS) |
| SLA tracking with business hours | ❌ | ✅ | ✅ |
| Multi-tenant for MSPs | ❌ | Varies | ✅ built in |
| Time to value | Immediate, but doesn't scale | Quarters | **Days** |
| Price | Free, until it isn't | Six-figure procurement | **Sized for lean teams** |

---

## 🧩 Capabilities

<table>
  <tr>
    <td width="33%" valign="top">
      <h4>🚨 Incident Management</h4>
      Track incidents from first alert to resolution. Templates, routing rules, assignment groups, automatic escalation, and linking to root-cause problems.
    </td>
    <td width="33%" valign="top">
      <h4>🔍 Problem Management</h4>
      Find the causes behind repeat incidents and record workarounds in a <b>Known Error Database</b> so the next occurrence is solved in minutes.
    </td>
    <td width="33%" valign="top">
      <h4>🔁 Change Management</h4>
      Change requests and templates, an approval inbox, and <b>CAB meetings</b>, with a full audit trail of who approved what and when.
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <h4>🗂️ CMDB</h4>
      Configuration items, custom CI classes, and real relationship mapping, plus <b>automated AWS discovery</b> and staleness checks so the map stays accurate.
    </td>
    <td width="33%" valign="top">
      <h4>🛒 Service Catalog</h4>
      Publish orderable IT services, take service requests, and route them through approvers and approver groups automatically.
    </td>
    <td width="33%" valign="top">
      <h4>💼 Asset &amp; License Management</h4>
      Track hardware and software assets, allocate licenses, and flag compliance gaps before an audit does.
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <h4>⏱️ SLA Tracking</h4>
      Response and resolution targets applied automatically, measured against each team's business hours, with at-risk tickets surfaced early.
    </td>
    <td width="33%" valign="top">
      <h4>📚 Knowledge Base</h4>
      Capture fixes and runbooks once. Article health checks flag stale content so your knowledge stays trustworthy.
    </td>
    <td width="33%" valign="top">
      <h4>🔔 Notifications &amp; Reporting</h4>
      Real-time and email notifications with per-user preferences, dashboards, and exportable reports for stakeholders.
    </td>
  </tr>
</table>

> [!NOTE]
> 🔎 **Search all 39 capabilities** by module: **[`data/features.csv`](https://github.com/syntaxroot-cc/.github/blob/main/data/features.csv)**

---

## 🛡️ Platform &amp; Security

| | |
| :-- | :-- |
| **Multi-tenant by design** | Each organization's members and data are isolated, which is what MSPs need to serve multiple clients from one platform. |
| **Invite-only membership** | Users join an organization only by invitation from an admin. |
| **Single sign-on** | Sign in with Google; no new passwords to manage. |
| **Role-based access** | Roles and permissions control who can view, edit, and approve. |
| **Tamper-evident audit log** | Every change is recorded with integrity verification, so the audit trail holds up to scrutiny. |
| **API keys** | Scoped keys for automation and integrations, separate from user sign-in. |

---

## 🔌 Integrations

| Integration | What it does |
| :-- | :-- |
| **REST API** | Versioned `/api/v1` API with API-key authentication for tickets, CIs, and more |
| **Webhooks** | Push SyntaxRoot events to your own systems in real time |
| **AWS Config discovery** | Discovers and reconciles AWS resources into the CMDB automatically |
| **Ansible collection** (`syntaxroot.cmdb`) | Populate the CMDB from Ansible facts, use the CMDB as a dynamic inventory, and alert on configuration drift |

---

## ⚙️ Architecture

```mermaid
flowchart LR
    U([IT team / MSP]) -->|Google sign-in| W[Web app<br/>Gatsby + Tailwind<br/>Cloudflare]
    W -->|HTTPS| G[Amazon API Gateway]
    A([Ansible · scripts · webhooks]) -->|API key| G
    G --> L[FastAPI on AWS Lambda]
    L --> P[(Amazon RDS<br/>PostgreSQL)]
    L --> Q[Amazon SQS<br/>async jobs]
    L --> D[(DynamoDB)]
    L -->|discovery| C[AWS Config]
```

| Layer | Technology |
| :-- | :-- |
| Frontend | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Gatsby](https://img.shields.io/badge/Gatsby-663399?style=flat-square&logo=gatsby&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white) |
| API | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white) ![API Gateway](https://img.shields.io/badge/API_Gateway-FF4F8B?style=flat-square&logo=amazonapigateway&logoColor=white) |
| Data | ![PostgreSQL](https://img.shields.io/badge/RDS_PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white) ![SQS](https://img.shields.io/badge/SQS-FF4F8B?style=flat-square&logo=amazonsqs&logoColor=white) |
| Delivery | ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |

Serverless end to end: no servers to patch, and costs scale with use. Every environment is defined in Terraform and shipped through GitHub Actions.

---

## 🔑 Getting Access

<p align="center">
  <img src="https://images.unsplash.com/photo-1763771787035-99c6c28ec78e?ixlib=rb-4.1.0&w=1600&h=280&fit=crop&crop=center&q=80&fm=jpg" alt="Rows of blue-lit server hardware" width="100%">
</p>

SyntaxRoot is in **invite-only early access** while we onboard a small group of teams and shape the roadmap with them.

| Step | What happens |
| :--: | :-- |
| **1** | Email **[hello@syntaxroot.cc](mailto:hello@syntaxroot.cc?subject=SyntaxRoot%20invitation%20request)** or use **Request a Demo** on [syntaxroot.cc](https://syntaxroot.cc) |
| **2** | We run a walkthrough with your team, using your real incident, change, and asset workflows |
| **3** | We create your organization and send invitations to your admins |
| **4** | Your team signs in with Google at [syntaxroot.cc/login](https://syntaxroot.cc/login/) |

> [!NOTE]
> The SyntaxRoot product source code is private and proprietary. Membership in this GitHub organization is also by invitation only.

---

## 📦 Open Source

Alongside the product, we publish open-source Go tooling for infrastructure and release engineering:

| Repository | Description | License |
| :-- | :-- | :-- |
| **[gomnibus](https://github.com/syntaxroot-cc/gomnibus)** | A Go rewrite of Chef Omnibus: build self-contained, cross-platform installers (`.deb`, `.rpm`, `.pkg`, `.msi`) from a declarative YAML/HCL DSL | Apache-2.0 |
| **[gomnibus-software](https://github.com/syntaxroot-cc/gomnibus-software)** | Reusable software definitions for gomnibus | Apache-2.0 |
| **[gomnibus-gitlab](https://github.com/syntaxroot-cc/gomnibus-gitlab)** | A gomnibus port of omnibus-gitlab: build GitLab CE packages from YAML definitions | Apache-2.0 |
| **[grsync](https://github.com/syntaxroot-cc/grsync)** | A Go rewrite of rsync with delta transfer, SSH transport, daemon mode, and archive semantics | GPL-3.0 |

Found a security issue? Please follow our **[security policy](https://github.com/syntaxroot-cc/.github/blob/main/SECURITY.md)** instead of opening a public issue.

---

## 🏢 About Thought Parameters

<p>
  <a href="https://thoughtparameters.com"><img src="https://github.com/ThoughtParameters/.github/raw/main/profile/banner.jpg" alt="Thought Parameters: Where Ideas Meet Intelligent Systems" width="100%"></a>
</p>

SyntaxRoot is built and operated by **[Thought Parameters LLC](https://thoughtparameters.com)**, a remote-first software development and DevOps consultancy in Placentia, California.

| | |
| :-- | :-- |
| **Product lead** | [Jason Lee Miller](https://github.com/jasonmiller-cc), Founder &amp; CEO, Thought Parameters |
| **Engineering** | Oluwatobi Ogundimu |
| **Company** | [thoughtparameters.com](https://thoughtparameters.com) · [GitHub](https://github.com/ThoughtParameters) · 1 (888) 875-1399 |

> **Need a team that can design, build, and operate software like this?** Thought Parameters builds custom platforms for clients too. [Let's talk.](https://thoughtparameters.com)

<p>
  <a href="https://www.linkedin.com/company/thoughtparameters/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="Thought Parameters on LinkedIn"></a>
  <a href="https://www.facebook.com/thoughtparameters"><img src="https://img.shields.io/badge/Facebook-1877F2?style=flat-square&logo=facebook&logoColor=white" alt="Thought Parameters on Facebook"></a>
  <a href="https://x.com/thoughtparams"><img src="https://img.shields.io/badge/X-@thoughtparams-000000?style=flat-square&logo=x&logoColor=white" alt="Thought Parameters on X"></a>
  <a href="https://www.instagram.com/thoughtparametersllc/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white" alt="Thought Parameters on Instagram"></a>
  <a href="https://www.threads.com/@thoughtparametersllc"><img src="https://img.shields.io/badge/Threads-000000?style=flat-square&logo=threads&logoColor=white" alt="Thought Parameters on Threads"></a>
</p>

---

<p align="center">
  <sub>© 2026 Thought Parameters LLC · SyntaxRoot is a product of Thought Parameters LLC · <a href="https://syntaxroot.cc">syntaxroot.cc</a></sub><br>
  <sub>Images: <a href="https://unsplash.com/@winstonchen?utm_source=syntaxroot_github&utm_medium=referral">Winston Chen</a> and <a href="https://unsplash.com/@zoshuacolah?utm_source=syntaxroot_github&utm_medium=referral">Zoshua Colah</a> on <a href="https://unsplash.com/?utm_source=syntaxroot_github&utm_medium=referral">Unsplash</a></sub>
</p>
