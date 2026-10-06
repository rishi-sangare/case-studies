# Case studies · Rishi Sangare

Most of my engineering lives in private client repositories. These write-ups explain **what I built, the decisions behind it, and what I measured**, without client code or confidential data. Product names are used where the product is public; clients are described generically.

| Case study | One line | Highlights |
|---|---|---|
| [LLM matching & evals](llm-matching-evals.md) | Candidate ↔ job matching for a large Japanese recruiting database | recall@10 0.19 → 0.57 · bad questions 85% → 0% · honest reranker trial |
| [RefineCV](refinecv.md) | B2B CV-formatting SaaS for recruitment agencies | 435 commits · 203 PRs in 5 months · cross-tenant authz fix |
| [Recruiter Copilot](recruiter-copilot.md) | AI candidate scoring on LinkedIn, Chrome Web Store | 11 releases · 400+ installs · 847 tests |
| [CRM migration](crm-migration.md) | 18 GB keyless SQL Server → REST-only SaaS CRM | 253,541 activities · 0 missing · 99.97% exact reconciliation |

All numbers come from git history, test runs and production reconciliation reports. Where a number was revised (for example, a reranker gain I first over-estimated), the write-up says so.

**Contact:** [sangarerishi@gmail.com](mailto:sangarerishi@gmail.com) · [LinkedIn](https://www.linkedin.com/in/rishi-sangare) · [GitHub](https://github.com/rishi-sangare)
