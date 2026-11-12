# Contributing to WAF Cost Optimization — Deep Dive

Thanks for helping keep these notes accurate. They're a companion to the **Cost Optimization pillar of the Azure Well-Architected Framework**, written for Cloud Solution Architects working on WAF reviews and cost conversations. Azure pricing, purchase options, tools and the framework's own guidance change often, so a page can fall out of date between one update and the next. Reports from people using the notes are the best way to catch that.

> [!IMPORTANT]
> **This repo accepts issues, not pull requests.** Pull requests are turned off: I write every change myself and check it against the official documentation, so the notes keep one voice and stay consistent from page to page. If you know exactly how something should read, put your proposed wording in the issue. It's just as useful.

---

## Contents

- [Ways to Help](#-ways-to-help)
- [Before You Open an Issue](#-before-you-open-an-issue)
- [Opening an Issue](#-opening-an-issue)
- [Out of Scope](#-out-of-scope)
- [What Happens Next](#-what-happens-next)
- [Code of Conduct](#-code-of-conduct)
- [Security](#-security)

## 🙌 Ways to Help

Every report fits one of the five types in the issue template:

| Type | What it covers | For example |
| --- | --- | --- |
| 🐞 **Bug** | Something on the site is broken: a link, a diagram, search or navigation | A link to Microsoft Learn returns 404, a Mermaid diagram doesn't render, or search doesn't find a term that's on the page |
| ✏️ **Incorrect content** | A fact, a table, a diagram or an explanation is wrong, or there's a typo | A stacking rule in the Azure Hybrid Benefit section is wrong, or a checklist item is mapped to the wrong design area |
| 📅 **Outdated content** | Azure pricing, services or WAF guidance have changed since the page was written | A discount figure such as "up to 72%" has changed, a tool has been renamed, or a CO:01–CO:14 recommendation has been reworded |
| 📱 **Device issue** | Something looks wrong or doesn't work on a specific device, browser or screen size | The savings mechanism comparison table is cut off on a phone in portrait, or a diagram overflows in a narrow window |
| 💬 **Something else** | Anything that doesn't fit above, including suggestions | A topic that would read better as a decision table, a CSA tip worth adding, or a term missing from the FinOps glossary |

## 🔎 Before You Open an Issue

- **Search the existing issues**, [open and closed](https://github.com/marcogrimaldi29/waf-cost-opt/issues?q=is%3Aissue). If yours is already there, add a 👍 reaction or a comment with anything new rather than opening a duplicate.
- **Check the date.** The notes were written against the Microsoft documentation as it stood in **May 2026**. Microsoft Learn articles show a **Last updated on** date at the bottom of the page, so if the article you're comparing against has been updated since then, say so in the issue — it tells me which version to compare against.
- **Check the current docs.** A quick look at the [Cost Optimization pillar](https://learn.microsoft.com/en-us/azure/well-architected/cost-optimization/) usually confirms whether the guidance has changed, and gives you the link the issue asks for. For prices and discounts, the [Azure Pricing Calculator](https://azure.microsoft.com/pricing/calculator) and each service's pricing page are the source of truth.
- **One problem per issue.** Separate issues are easier to track, fix and close. Several typos on the same page can go in one issue.
- **For a site bug, hard-refresh first** (Ctrl+F5, or Cmd+Shift+R on a Mac) in case your browser is showing an older copy of the page.

## 📝 Opening an Issue

1. Open a new issue with the [🐞 Report a problem with the notes](https://github.com/marcogrimaldi29/waf-cost-opt/issues/new?template=ISSUE_TEMPLATE.md) template.
2. Give it a title that names the page and the problem, for example *"01 — Cost Optimization Deep Dive: CO:07 wording doesn't match the checklist"* rather than *"Mistake on page"*.
3. Fill in the template's sections. Leave out any that don't apply.

> [!TIP]
> To link straight to a section, click it in the page's **📑 Table of Contents**, or hover over its heading and click the link icon beside it, then copy the address from your browser.

### What Makes a Report Easy to Fix

- **A link to the exact section**, not just the page
- **The text as the notes have it**, quoted, so it can be found even if the page has moved on
- **An official source** for any content change — Microsoft Learn or an Azure pricing page is best, and for FinOps terms, the [FinOps Foundation](https://www.finops.org/). A report without one may take longer, because every change has to be checked against the documentation before it goes in
- **For bugs and device issues:** the steps to reproduce it, what you expected and what happened instead, the device, operating system and browser, and a screenshot if it shows the problem
- **Your proposed wording**, if you have it. With pull requests turned off, this is the closest thing to suggesting an edit directly

## 🚫 Out of Scope

To keep the notes accurate and the issue tracker useful, please don't open issues for:

- **Help with your own Azure environment.** I can't review your architecture, cost estimate or bill in an issue. For questions about your own subscription, workload or costs, ask on [Microsoft Q&A](https://learn.microsoft.com/en-us/answers/) or open an Azure support request.
- **Anything private.** Issues are public, so leave out customer names, subscription and tenant IDs, invoices, cost exports and negotiated prices, including in screenshots.
- **Unofficial sources.** Third-party blog posts, reseller price lists and AI chat answers aren't accepted as the source for a content change.
- **Promotion.** Links to courses, cost-management or FinOps tools and services, affiliate links and paid placements won't be added.
- **Security vulnerabilities.** Please [report these privately](https://github.com/marcogrimaldi29/waf-cost-opt/security/advisories/new), as described in the [security policy](SECURITY.md), not in a public issue.

## 🔄 What Happens Next

- I maintain the notes on my own, in my spare time, so replies are best effort and there's no fixed response time.
- I check each report against the official documentation. If something needs clarifying, I'll ask on the issue, so keep an eye on your GitHub notifications.
- When a fix goes in, the issue is closed with a note or a link to the change. The live site updates shortly after.
- If nothing changes, the issue is closed with the reason, such as out of scope, can't be verified, or working as intended.
- An issue waiting on a reply may be closed after a while. Comment with the missing details and it can be reopened.

## 🤝 Code of Conduct

By opening, commenting on or reacting to issues here, you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md). Comments that are abusive, spam or promotional may be hidden, edited or locked.

## 🔒 Security

Found a security problem with the site or this repo? Please don't report it in a public issue. Use [Report a vulnerability](https://github.com/marcogrimaldi29/waf-cost-opt/security/advisories/new) instead, so only you and I can see it. The [security policy](SECURITY.md) has the details.

---

If the notes helped you, the README's [💚 Support](https://github.com/marcogrimaldi29/waf-cost-opt#-support) section has a couple of ways to show it. Thanks for helping make them better for the next WAF review.
