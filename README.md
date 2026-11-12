# Awesome-Contract-Analytics-Intelligence-Engine

## Top Contract Analytics & Intelligence Engine Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Clause Extraction, Portfolio Risk Analytics & Obligation Intelligence*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Contract Analytics & Intelligence Engines**. These tools transform static contract repositories into queryable intelligence—extracting clauses, obligations, and metadata at scale, then surfacing risk exposure, revenue leakage, and compliance gaps across the entire portfolio.

**Examples** include Icertis Vera Analytics, Evisort (Workday), Kira Systems, Luminance, Lexion, SirionLabs, CobbleStone VISDOM, Agiloft, Ironclad Insights, and Seal Software (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted contract intelligence, open-source clause extraction, and community-driven legal analytics—ideal for organizations seeking data sovereignty and transparent model behavior over opaque enterprise APIs.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Icertis (Vera Analytics)](https://www.icertis.com/)** | AI-native contract intelligence platform with Vera Copilot, Engage (drafting/redlining), Operate (obligations), and Analyze (portfolio risk exposure). Analyzes contracts against business events to surface risk and optimize operations. Used by one-third of the Fortune 100 . | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Evisort (Workday)](https://www.evisort.com/)** | Contract intelligence and CLM acquired by Workday. Custom AI Model Library includes **120+ pre-built models** for clause identification, risk flagging, and term extraction across HR, finance, legal, and sales contracts. Customers can refine models with feedback—no coding required . | $30,000–$60,000/year (small teams); $60,000–$120,000/year (mid-market) | Free trial available; self-serve signup |
| **[Kira Systems](https://kirasystems.com/)** | Legal contract analysis with pre-trained models for clause extraction and due diligence. Users can train Kira on firm-specific provisions. Document comparison feature generates heat maps showing variations against a form document. Acquired by Litera . | Quote-only (enterprise; historically per-document bundles) | No free tier; demo via sales |
| **[Luminance](https://www.luminance.com/)** | Legal-Grade AI that grounds mark-ups in precedent from prior negotiations. Customizable dashboard surfaces portfolio insights across departments; analyzes document families (amendments, side letters) as a single evolving relationship. Every insight includes source-level citations . | Quote-only (enterprise contract) | No free tier; trial via sales |
| **[Lexion](https://www.lexion.ai/)** | AI contract management (acquired by Docusign for ~$165M) focused on obligation tracking and spend visibility. Automatically tags and files contracts, tracks renewals and termination notice deadlines, and reports on key terms like GDPR/CCPA compliance. Users praise extraction accuracy and intuitive interface . | Quote-only (enterprise contract) | No free trial; sales-led onboarding |
| **[SirionLabs](https://www.sirion.ai/)** | Contract analytics engine with DiscoverAI (ingest), ExtractAI (100s of metadata, obligations, clauses, SLs, pricing tables), and ActAI (push to downstream systems). Pre-trained industry-specific models handle multi-line, multi-column, multi-table, and multi-language documents. ML engine improves with each contract processed . | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[CobbleStone (VISDOM AI)](https://www.cobblestonesoftware.com/)** | CLM with native VISDOM AI for auto-redlining, clause replacement, risk summaries, and post-execution compliance tracking. Named MVP on QKS AI Maturity Matrix. Includes agentic chatbot querying, clause governance, and automated risk detection . | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Agiloft (AI Core)](https://www.agiloft.com/)** | No-code CLM with AI Core for clause extraction, risk detection, and obligation tracking. Auto-verifies contracts against internal playbooks, suggests fallback language, and generates redlines. 1,000+ integrations including SAP, NetSuite, Salesforce, and DocuSign . | Quote-only (enterprise; median ~$67,000/year) | No free tier; demo via sales |
| **[Ironclad Insights](https://ironcladapp.com/)** | Contract analytics tool within Ironclad for visualizing and analyzing contracting processes in real-time. Prebuilt charts answer operational questions (in-progress workflow statuses, bottleneck identification, time-to-execution trends). Drill-down into underlying workflows; export as image/PDF/CSV . | Included with Ironclad subscription (quote-only) | No separate free tier; requires Ironclad CLM |
| **[Seal Software (SAP Ariba)](https://www.seal-software.com/)** | AI-powered contract intelligence layer for SAP Ariba. Contract Discovery and Analysis for procurement teams: consolidated access to contracts and DocuSign envelopes, concept-based search, side-by-side comparisons, and risk scoring. Claims 80% reduction in time-to-information . | Quote-only (SAP Ariba integration) | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[draftLegal](https://github.com/AniketTati/draft-legal)** | [![Stars](https://img.shields.io/github/stars/AniketTati/draft-legal?style=social&color=white)](https://github.com/AniketTati/draft-legal/stargazers) | Self-hosted, AI-native CLM positioned as open-source alternative to Ironclad + Harvey. Portfolio intelligence via hybrid retrieval (pgvector + Elasticsearch + RRF) lets agents search across the whole portfolio for exposure, counterparties, auto-renewals, and notice deadlines. Extraction with clause-level citations; PDF citations open at source page. Bring-your-own model (Anthropic, OpenAI, Gemini). `docker compose up` deployment . |
| **[Hermes Legal Advisor](https://pypi.org/project/hermes-legal-advisor/)** | [![Stars](https://img.shields.io/github/stars/Lethe044/hermes-legal?style=social&color=white)](https://github.com/Lethe044/hermes-legal/stargazers) | Open-source contract analysis CLI with portfolio dashboard, batch processing, and deadline tracking. Aggregates risk distribution, most common red flags, and per-counterparty breakdown. Supports offline scanner, LLM providers (Groq, Gemini, OpenRouter, Ollama), custom firm playbooks via YAML, and Docker deployment . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[LiTiL Open Intelligence Models](https://huggingface.co/collections/litillabs/litil-open-intelligence-models)** | — | Collection of task-specific legal AI models: clause classifier (0.4B), clause tagger (4B), contract extractor (1.7B), contract playbook (3B), and financing review (9B). Open models for building custom contract analytics pipelines . |
| **[PAKTON](https://aclanthology.org/2025.emnlp-main.403/)** | — | Fully open-source multi-agent framework for question answering over long legal agreements. Uses collaborative agent workflows and RAG for privacy-preserving contract analysis. Outperforms general-purpose models on predictive accuracy, retrieval, and explainability . |
| **[Legal-Peace-7B](https://huggingface.co/olaverse/legal-peace-v1.0)** | — | Fine-tuned Mistral-7B for contract analysis and legal reasoning. SFT + DPO trained. Claims 32.6% faster contract analysis vs. base model. Apache 2.0; **beta/research model, not for production** . |

**Frameworks for building custom systems**: Combine **draftLegal** for portfolio-wide hybrid search and cited extraction, **Hermes Legal Advisor** for CLI-based batch analysis and deadline tracking, and **LiTiL models** for task-specific clause classification—all deployable via Docker with local LLM inference.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Contract analytics engines process legally sensitive documents; enforce strict access controls, encryption, and data residency compliance. AI-generated insights must be reviewed by qualified legal professionals before reliance.
- Commercial platforms are universally quote-only with no public pricing or free tiers. Open-source alternatives (draftLegal, Hermes) are emerging but lack the enterprise integrations (SAP, Salesforce, DocuSign) and validation at scale that established platforms offer. Kira's per-document pricing model has been criticized as creating disincentives to full utilization . Always validate extraction accuracy against your actual contract corpus before operational deployment.

---

**Made for legal ops teams, contract analysts, procurement professionals, and developers building contract intelligence infrastructure.**  
Let's make contract analytics more open, explainable, and audit-ready.
