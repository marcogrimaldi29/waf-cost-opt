# 💰 Azure Well-Architected Framework: Cost Optimization — Deep Dive

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?logo=github)](https://marcogrimaldi29.com/waf-cost-opt/)
[![marcogrimaldi29.com](https://img.shields.io/badge/Blog-marcogrimaldi29.com-blue?logo=rss)](https://marcogrimaldi29.com)

> - 🎯 **Goal:** Companion notes covering architectures' best practices and Cost Optimization strategies
> - 📅 **Notes Version:** 2026 (updated as the framework evolves)
> - 🌐 **Published site:** [Azure Well-Architected Framework: Cost Optimization — Deep Dive](https://marcogrimaldi29.com/waf-cost-opt/)
> - ✍️ **Author:** [Marco Grimaldi](https://www.linkedin.com/in/marco-grimaldi29/)

---

## 📌 What Is This?

These notes are a **practical companion** to the official [Azure Well-Architected Framework — Cost Optimization pillar](https://learn.microsoft.com/en-us/azure/well-architected/cost-optimization/) documentation. They are designed for **Cloud Solution Architects** working with customers on WAF reviews, cost governance, and financial optimization on Azure.

The content covers design principles, savings mechanisms, tools, governance practices, and FinOps terminology — everything a CSA needs for structured Cost Optimization conversations.

---

## 🗂️ Repository Structure

```
waf-cost-opt/
├── README.md                         ← 📍 You are here
├── index.md                          ← Site home page (Just the Docs)
├── 00-waf-overview.md                ← WAF overview, pillars, assessment
├── 01-cost-optimization-deep-dive.md ← Design principles, checklist, tradeoffs
├── 02-savings-opportunities.md       ← Reservations, Savings Plans, AHB, Spot
├── 03-tools.md                       ← Pricing Calculator, Cost Management, Advisor
├── 04-governance-automation.md       ← Budgets, tagging, policies, automation
└── 05-appendix-finops.md             ← FinOps framework, glossary, acronyms
```

---

## 📋 Contents at a Glance

| # | File | Topics |
|---|------|--------|
| 🏗️ | [00 — WAF Overview](./00-waf-overview.md) | Well-Architected Framework, five pillars, WAF reviews, assessment tool |
| 📐 | [01 — Cost Optimization Deep Dive](./01-cost-optimization-deep-dive.md) | Design principles, CO:01–CO:14 checklist, tradeoffs, maturity model |
| 💵 | [02 — Savings Opportunities](./02-savings-opportunities.md) | Reservations, Savings Plans, Azure Hybrid Benefit, Spot VMs, Dev/Test |
| 🔧 | [03 — Tools & Calculators](./03-tools.md) | Pricing Calculator, TCO Calculator, Cost Management, Advisor |
| 🛡️ | [04 — Governance & Automation](./04-governance-automation.md) | Budgets, guardrails, tagging, Azure Policy, cost automation |
| 📘 | [05 — FinOps Appendix](./05-appendix-finops.md) | FinOps framework, glossary, acronyms, key terms |

---

## 🔑 Key Topics Covered

- **Well-Architected Framework** — all five pillars and how Cost Optimization interacts with them
- **Cost Optimization design principles** — the five principles driving financial responsibility
- **Official checklist (CO:01–CO:14)** — every recommendation with practical context
- **Rate optimization** — Reservations, Savings Plans, Azure Hybrid Benefit, Spot VMs, Dev/Test pricing
- **Tools** — Azure Pricing Calculator, TCO Calculator, Microsoft Cost Management, Azure Advisor
- **Governance** — budgets, spending guardrails, tagging, Azure Policy, automation
- **FinOps** — framework overview, maturity model, glossary for CSA conversations

---

## 📄 Official Resources

| Resource | Link |
|----------|------|
| 🏗️ Azure Well-Architected Framework | [learn.microsoft.com/azure/well-architected](https://learn.microsoft.com/en-us/azure/well-architected/) |
| 💰 Cost Optimization Pillar | [learn.microsoft.com/.../cost-optimization](https://learn.microsoft.com/en-us/azure/well-architected/cost-optimization/) |
| 📋 WAF Assessment Tool | [Azure Well-Architected Review](https://learn.microsoft.com/en-us/assessments/azure-architecture-review/) |
| 🔧 Microsoft Cost Management | [Cost Management docs](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/cost-mgt-best-practices) |
| 🧮 Azure Pricing Calculator | [azure.microsoft.com/pricing/calculator](https://azure.microsoft.com/pricing/calculator) |

---

## 🐞 Spotted a Mistake?

Azure pricing and the Well-Architected Framework change often, so if something here is wrong or out of date, please [report an issue](https://github.com/marcogrimaldi29/waf-cost-opt/issues).

---

## 💚 Support

If you found these notes useful for your WAF reviews or Cost Optimization conversations, there are a couple of ways to show it: ⭐ star this repo on GitHub so other architects can find it, or 🤝 connect with me on LinkedIn.

<p>
  <a href="https://github.com/marcogrimaldi29/waf-cost-opt"><img src="https://img.shields.io/badge/Star_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="Star on GitHub" /></a>
  <a href="https://www.linkedin.com/in/marco-grimaldi29/"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2EyLjA2MiAyLjA2MiAwIDAgMS0yLjA2My0yLjA2NSAyLjA2NCAyLjA2NCAwIDEgMSAyLjA2MyAyLjA2NXptMS43ODIgMTMuMDE5SDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyNSAweiIvPjwvc3ZnPg%3D%3D" alt="Connect on LinkedIn" /></a>
</p>

---

## ✍️ About the Author

Maintained by **[Marco Grimaldi](https://www.linkedin.com/in/marco-grimaldi29/)** — Cloud Solution Architect.

Find more notes and content at **[🏠 marcogrimaldi29.com](https://marcogrimaldi29.com)**

---

## 📈 Analytics

This site uses **[Umami](https://umami.is/)** for privacy-friendly, cookieless analytics.

---

## ©️ Credits & Acknowledgements

The **[Just the Docs](https://github.com/just-the-docs/just-the-docs)** theme is used for the documentation layout. Licensed under [MIT](https://opensource.org/license/MIT).

Created with the help of AI. Model used: **[Claude Opus 4.6](https://www.anthropic.com/news/claude-model-card)**. Content reviewed and edited by the author. Always verify against the latest [Microsoft documentation](https://learn.microsoft.com/en-us/).

> *Not affiliated with or endorsed by Microsoft. Content for reference purposes only.*
