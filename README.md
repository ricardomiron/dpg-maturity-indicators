<div align="center">

<a href="https://digitalpublicgoods.net/registry" target="_blank" rel="no opener noreferrer"><img src="https://github.com/DPGAlliance/dpg-resources/blob/main/docs/assets/dpg-badge/dpg-badge.png?raw=true" width="70" alt="Digital Public Goods Badge"></a>

# DPG Maturity Model

This model helps product owners of open source solutions — including registered Digital Public Goods (DPGs), DPG candidates, and other open source projects — understand where their product stands today and what to improve next. It is designed to be useful to four audiences: **maintainers** making development decisions, **implementers** evaluating deployment readiness, **funders** assessing investment worthiness, and **contributors** deciding where to engage.

![Static Badge](https://img.shields.io/badge/status-active-blue) 
![GitHub License](https://img.shields.io/github/license/DPGAlliance/dpg-maturity-indicators)
![GitHub Release](https://img.shields.io/github/v/release/DPGAlliance/dpg-maturity-indicators)

</div>

---
## How it works

For registered DPGs, the model assumes that the product already meets the [DPG Standard](https://www.digitalpublicgoods.net/standard) as a baseline. Everything here builds beyond that foundation — it does not re-assess open licensing, SDG relevance, do-no-harm safeguards, or privacy compliance, which are already covered by the Standard. Non-DPG open source projects can use the model independently of the DPG Standard.

> [!IMPORTANT]
>
> The scope is limited to what is within the product owner's control. External factors like an adopting organization's technical readiness to deploy, or the policy environment in a given country, are out of scope.

### Applicability across product types

This model applies to open source software, data, content, and AI models. Where an indicator is not relevant to a particular type, it is marked accordingly. Product owners should assess only the indicators applicable to their product type.

### Audience tags

Each indicator notes which audiences find it most relevant:

- 🔧 **Maintainers** — product owners and core development teams
- 🏗️ **Implementers** — organizations deploying the product in a specific context
- 💰 **Funders** — donors, investors, and grant-making organizations
- 🤝 **Contributors** — developers, designers, translators, and other community members

The model is organized into **5 core pillars** containing **15 indicators**, plus **1 optional pillar** with **3 additional indicators** for projects that want to surface adoption and ecosystem information.

### Summary Table

| Pillar | # | Indicator | Software | Data | Content | AI |
|--------|---|-----------|:--------:|:----:|:-------:|:--:|
| Governance & Community | 1.1 | Governance Model | ✓ | ✓ | ✓ | ✓ |
| | 1.2 | Community Contribution | ✓ | ✓ | ✓ | ✓ |
| | 1.3 | Product Roadmap | ✓ | ✓ | ✓ | ✓ |
| Technical Quality & Security | 2.1 | Quality Assurance | ✓ | | | ✓ |
| | 2.2 | Security Practices | ✓ | | | ✓ |
| | 2.3 | Architecture & Extensibility | ✓ | | | ✓ |
| Deployment & Usability | 3.1 | Deployment Tooling | ✓ | | | ✓ |
| | 3.2 | Documentation Depth | ✓ | ✓ | ✓ | ✓ |
| | 3.3 | Internationalization & Localization | ✓ | ✓ | ✓ | ✓ |
| | 3.4 | Accessibility | ✓ | | ✓ | ✓ |
| Interoperability & Standards | 4.1 | Open Standards Adoption | ✓ | ✓ | ✓ | ✓ |
| | 4.2 | Integration Readiness | ✓ | | | ✓ |
| Sustainability & Support | 5.1 | Funding & Business Model | ✓ | ✓ | ✓ | ✓ |
| | 5.2 | Maintenance Activity | ✓ | ✓ | ✓ | ✓ |
| | 5.3 | User & Implementer Support | ✓ | ✓ | ✓ | ✓ |
| **Adoption & Ecosystem (Optional)** | 6.1 | Total Cost of Ownership | ✓ | ✓ | ✓ | ✓ |
| | 6.2 | Vendor & Implementer Ecosystem | ✓ | ✓ | ✓ | ✓ |
| | 6.3 | Adoption Tracking | ✓ | ✓ | ✓ | ✓ |

---

## How to use this model

**Product owners** should self-assess their product against each applicable indicator and identify 2–3 areas to prioritize for improvement. Not every product needs to be "Mature" across all indicators — the right maturity profile depends on the product's stage, strategy, and user base.

**Implementers** can use the model to evaluate whether a product meets their deployment requirements and to understand what support to expect at each maturity level.

**Funders** can use the model to assess investment readiness, identify where targeted funding would have the most impact, and track progress over time.

**Contributors** can identify projects where their skills are most needed — Emerging-level indicators often represent the best opportunities for high-impact contributions.

---

## Relationship to the DPG Standard

This maturity model is designed as a complement to the [DPG Standard](https://github.com/DPGAlliance/dpg-standard). The DPG Standard defines the baseline requirements for a digital solution to be recognized as a Digital Public Good. This model goes further: it assesses how well-established, sustainable, and deployment-ready a DPG is beyond that baseline.

> [!IMPORTANT]
>
>Compliance with the DPG Standard is highly encouraged. A DPG that does not meet the Standard should focus on meeting it before using this maturity model.

---

## Known Limitations & Future Iterations

This v0.1 model is intentionally concise. The following areas have been identified for potential expansion in future versions:

- **Data and content products** have fewer applicable indicators in Pillar 2 (Technical Quality). Future iterations may add indicators for data quality, schema documentation, update freshness, and provenance — areas that are critical for data-type products but require different rubric language.
- **AI model transparency** — model cards, bias documentation, training data provenance, and explainability are increasingly important for AI-type products. As AI governance frameworks mature, dedicated indicators may be warranted.


---

## How to Get Involved

We welcome all contributions! Here are some ways you can participate:

1. **Join the Discussions**: Share ideas, ask questions, and collaborate in our [GitHub Discussions](https://github.com/CoP-Maturity-Indicators/discussions).
2. **Report Issues**: Use the [Issues tab](https://github.com/CoP-Maturity-Indicators/issues) to report bugs, propose features, or ask questions.
3. **Contribute Code or Content**: Submit your improvements via [Pull Requests](https://github.com/CoP-Maturity-Indicators/pulls).
4. **Participate in Meetings**: Check our [Meeting Notes](docs/meeting-notes/) for updates and upcoming sessions.

### Repository Structure

```
root/
├── README.md                # Overview of the project
├── CONTRIBUTING.md          # Guidelines for contributors
├── LICENSE                  # Licensing details
├── docs/                    # Documentation
│   ├── meeting-notes/       # Meeting notes and agendas
│   ├── guides/              # Contribution and usage guides
│   └── templates/           # Templates for issues and pull requests
├── indicators/              # Indicator development
│   ├── core-indicators/     # Universal indicators
│   └── sector-specific/     # Domain-specific indicators
├── tools/                   # Tools and resources
│   ├── maturity-assessment-tool/ # Assessment tools
│   └── resources/           # Supporting materials
└── .github/                 # GitHub-specific configurations
    ├── ISSUE_TEMPLATE.md    # Template for issues
    └── PULL_REQUEST_TEMPLATE.md  # Template for pull requests
```


## Acknowledgements

This initiative is collaboratively led by **UNICEF**, **Digital Square at PATH**, **FAO**, **GitHub**, and the **Digital Public Goods Alliance (DPGA) Secretariat** and advised by  Fabro Steibel (ITS Rio), Saurav Bhattarai (GIZ), Sabbir Mahbub (A2i), Pamod Amarakoon (DHIS2), Pete Herlihy (AWS). 

This model was informed by a review of 17 established maturity frameworks spanning the DPG ecosystem, the open source community, and the broader software industry. The most significant influences include:

1. The **Digital Square Global Goods Maturity Model (GGMM)** and its companion **Shelf-Readiness Matrix** provided the foundation for how DPG-specific maturity is structured. The GGMM's three-pillar approach (Global Utility, Community Support, Software Maturity) and its use of self-assessment directly shaped this model's pillar structure and assessment philosophy. The Shelf-Readiness Matrix's detailed rubrics for deployment tooling, QA, and documentation for multiple audience types (decision-makers, implementers, operations, developers) were particularly influential in shaping Pillars 2 and 3.

2. The **UNICEF Djenga** tool and the **DPGA's own Standards, Best Practices & Maturity Categorization** work provided the ecosystem context — particularly the six-pillar indicator structure (Governance & Sustainability, Product Strategy, Data Protection & Security, Scalability & Interoperability, Legal/Source Code Accessibility, Total Cost of Ownership) which this model consolidates and refines.

3. From the open source ecosystem, the **Apache Software Foundation Project Maturity Model** shaped the governance and community indicators, particularly around community diversity and consensus-based decision-making. The **CNCF's tiered maturity levels** (Sandbox → Incubating → Graduated) validated the three-level approach and the principle that maturity signals adoption readiness. The **OpenSSF Scorecard** informed the security practices indicator with its emphasis on automatable, verifiable checks. **CHAOSS metrics** influenced the contributor-focused aspects of community health, and the **DIAL Digital Impact Exchange** contributed the idea of combining self-assessed and automated metrics.

4. The **CMMI** five-level maturity model provided the conceptual vocabulary for progressive maturity — the principle that maturity levels describe increasingly defined, managed, and optimized practices. The **GovStack Building Blocks framework** informed the interoperability and integration indicators, particularly the idea that open source products should be composable within larger digital public infrastructure.

### What was excluded and why

Several elements from the source models were intentionally left out. 
- **Process-level assessments** from CMMI and ISO/IEC 33000 (SPICE) — which evaluate how an organization manages its software development processes — were excluded because they assess organizational capability rather than product maturity, and would impose a compliance burden disproportionate to the value they add for most product owners.
- **License compliance frameworks** like OpenChain/ISO 5230 and the FINOS OSMM focus on how organizations govern their use of open source internally; since the DPG Standard already requires open licensing, adding organizational compliance indicators would duplicate rather than extend the baseline.
- The **TODO Group OSPO Maturity Model** was excluded for similar reasons — it measures how mature an organization's open source program office is, not the maturity of a specific product.
- Finally, **country-level digital readiness assessments** from GovStack and UNDP were not incorporated as indicators because they measure the adopting environment rather than the product itself, falling outside the product owner's scope of responsibility.

## Resources
- [Meeting Notes](docs/meeting-notes/)
- [Guides and Best Practices](docs/guides/)
- [Assessment Tools](tools/maturity-assessment-tool/)

## License
This repository is licensed under the [Creative Commons Zero v1.0 Universal (CC0 1.0)](LICENSE). Contributions are welcome under the same license.

[![CC0 1.0][cc0-image]](https://creativecommons.org/publicdomain/zero/1.0/)

> This is a human-readable summary of (and not a substitute for) the [CC0 1.0 Universal Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work. This work is published from a global context.
>
> You are free to:
> * **Copy, modify, distribute, and perform the work** — even for commercial purposes — without asking permission.
>
> There are no conditions. No attribution required. No share-alike required.
>
> The person who associated a work with this deed has dedicated the work to the public domain by waiving all of their rights to the work worldwide under copyright law, including all related and neighboring rights, to the extent allowed by law.
>
> You can copy, modify, distribute, and perform the work, even for commercial purposes, all without asking permission.
>
> No warranties are given. See the full legal text for details.

[cc0-image]: https://licensebuttons.net/l/zero/1.0/88x31.png
