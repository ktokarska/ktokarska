## Hi, I'm Kasia 👋

I build production AI for decisions a human has to sign: LLM agents and 0-to-1 risk models for regulated, high-stakes domains (insurance, carbon markets, due diligence). The rule I work by: **develop the evaluation before the product.**

Climate scientist by training. Ten years measuring uncertainty for the IPCC, then I moved into product because I wanted to build the tools, not just publish about them. This is where I keep what I build in the open — data-driven tools, research code, and a few things I made because I wanted them to exist.

🌐 [kasiatokarska.com](https://kasiatokarska.com) · 💼 [LinkedIn](https://linkedin.com/in/tokarska) · 📄 [Publications](https://kasiatokarska.com/cv-publications.html)

### Selected work

- **[dd-evals](https://github.com/ktokarska/dd-evals)** — an eval harness for LLM due diligence. Scores whether answers stay grounded in their cited sources, stay honest about when data is missing, and deliver high-robustness answers on high-stakes yes/no decisions. LLM judge calibrated against human labels (10/10 agreement), zero false accepts, mutation-tested grader, reproducible offline. Distilled and anonymised from a production KYC framework I built. This demo uses synthetic data to showcase the evaluation approach. [Live demo](https://kasiatokarska.com/dd-evals/dashboard.html).
- **Production AI agents inside a regulated insurer** · *CarbonPool* — architected and shipped two production LLM agents (an applied-research assessment agent and the due-diligence / KYC agent dd-evals is distilled from), each gated on an evaluation pipeline I built first. Cut counterparty checks from **several days to under 10 minutes** and moved **~80% of the team** onto AI-augmented workflows. *(Proprietary, no public repo.)*
- **[Fair Price](https://github.com/ktokarska/housing_tool_fair_price)** — a UK property valuation tool built only on open data, designed around one idea: a model that knows when it does not know. Ten calibration gates locked before results were reviewed; the demo areas are quarantined because they cannot pass those gates on insufficient data. [Live demo](https://kasiatokarska.com/house-price-fair-estimate.html).
- **[Remaining carbon budgets](https://github.com/ktokarska/remaining_carbon_budgets)** — the uncertainty-quantification code behind Matthews, Tokarska et al. (2021), part of the carbon-budget methodology cited in IPCC AR6.

### Research

24 peer-reviewed publications on climate uncertainty quantification (incl. *Nature Climate Change*, *Nature Geoscience*), 4,000+ citations; IPCC AR6 Contributing Author. Full list on [Google Scholar](https://scholar.google.com/citations?user=RVqnXpAAAAAJ).

### Background

- **Founding technical team (#5)** at CarbonPool — Director of Climate Risk Products & Applied AI
- **Ex-McKinsey** — Research Science Specialist, TCFD physical-risk disclosures
- **PhD** + 10 years applied research
- Won the **CHF 760K SNF Ambizione grant** as sole investigator — then declined it to build commercial product instead
