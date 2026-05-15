# Maturity Assessment Questionnaire

This questionnaire is a self-assessment tool for product owners of open source solutions — including registered Digital Public Goods (DPGs), DPG candidates, and other open source projects — to evaluate their product's maturity across key dimensions.

It is aligned with the [DPG Maturity Model](./core-indicators.md) and organized into **6 pillars** containing **18 indicators** (15 core + 3 optional).

### How to Use This Questionnaire

For each indicator, the assessment involves a three-step process:

1. **Select the Maturity Level:** Choose the level (**Emerging**, **Growing**, or **Mature**) that most accurately describes the product's current practices for that indicator.
2. **Select Applicable Practices:** Check every practice that your product currently has in place. The practices are ordered progressively — the more you check, the higher the maturity. Your level is determined by the highest group of practices you can fully claim.
3. **Provide Context and Evidence:** Use the free-form text area to add context, links to public evidence, or explain any unique circumstances.

> **Note:** Every maturity level is valid. "Emerging" is not a failure — it reflects an early-stage product with room to grow. If none of the practices listed apply yet, that's okay — select Emerging and use the evidence section to describe your current state. This questionnaire is designed to guide improvement, not gatekeep.

---

## Pillar 1: Governance & Community

*How the project is led, how decisions are made, and how the community participates.*

### 1.1 Governance Model

> **What this measures:** How transparent and structured is the decision-making process?

**1. Select Your Project's Level:**

- ![Emerging](https://img.shields.io/badge/Emerging-blue) — Decisions are made informally by a small group or single organization. No public governance documentation exists.
- ![Growing](https://img.shields.io/badge/Growing-yellow) — A governance model is documented and publicly available. Roles, responsibilities, and decision-making processes are defined.
- ![Mature](https://img.shields.io/badge/Mature-green) — Governance is community-driven with clear pathways for external stakeholders to influence direction. Decision-making is transparent and may involve a steering committee, advisory board, or similar multi-stakeholder structure.

**2. Select the Practices That Apply:**

- [ ] A governance document (e.g., `GOVERNANCE.md`) is publicly available.
- [ ] Roles and responsibilities within the governance structure are defined and documented.
- [ ] Decision-making processes are documented and communicated publicly.
- [ ] External stakeholders (outside the founding organization) can formally participate in decision-making.
- [ ] A steering committee, advisory board, or similar multi-stakeholder body exists.
- [ ] Governance decisions and outcomes are published transparently (e.g., meeting notes, decision logs).

**3. Evidence and Context:**

_Provide a link to your governance documentation or describe your decision-making process._

> 💡 **Tip:** Think about how someone new would understand who runs the project. Is there a `GOVERNANCE.md` file? Are decisions announced publicly?

| Field | Recommended input |
|-------|------------------|
| Governance document URL | `URL field` |
| Additional context | `Text area` |

---

### 1.2 Community Contribution

> **What this measures:** How easy is it for others to contribute, and how diverse is the contributor base?

**1. Select Your Project's Level:**

- ![Emerging](https://img.shields.io/badge/Emerging-blue) — Contributions are accepted but there are no formal guidelines or onboarding materials for new contributors.
- ![Growing](https://img.shields.io/badge/Growing-yellow) — Contribution guidelines exist (e.g., CONTRIBUTING.md, code of conduct). The project labels good-first-issues and has a documented review process for external contributions.
- ![Mature](https://img.shields.io/badge/Mature-green) — The project actively lowers barriers to contribution: onboarding documentation, mentorship practices, responsive review processes, and recognition of community work. Contribution guidelines are maintained for multiple contribution types (code, content, translation, testing).

**2. Select the Practices That Apply:**

- [ ] A `CONTRIBUTING.md` file exists with guidelines for submitting issues and pull requests.
- [ ] A code of conduct is published and enforced.
- [ ] Issues are labeled for newcomers (e.g., `good-first-issue`, `help-wanted`).
- [ ] A documented review process exists for external contributions.
- [ ] Onboarding documentation or mentorship practices help new contributors get started.
- [ ] Contribution guidelines cover multiple types (code, content, translation, testing, design).
- [ ] Community contributions are publicly recognized (e.g., contributor lists, shout-outs in release notes).

**3. Evidence and Context:**

_Link to your contributing guidelines, code of conduct, or describe how you onboard new contributors._

> 💡 **Tip:** A `CONTRIBUTING.md` is a strong starting signal. Beyond that, look at whether newcomers can actually find something to work on and get a review in a reasonable time.

| Field | Recommended input |
|-------|------------------|
| Contributing guidelines URL | `URL field` |
| Code of conduct URL | `URL field` |
| Additional context | `Text area` |

---

### 1.3 Product Roadmap

> **What this measures:** Is there a visible plan for where the product is heading?

**1. Select Your Project's Level:**

- ![Emerging](https://img.shields.io/badge/Emerging-blue) — No public roadmap. Development priorities are managed internally.
- ![Growing](https://img.shields.io/badge/Growing-yellow) — A roadmap is publicly available and updated periodically. It reflects planned features, improvements, or content updates.
- ![Mature](https://img.shields.io/badge/Mature-green) — The roadmap is actively maintained with community input mechanisms. Priorities are informed by user feedback, implementer needs, and strategic goals. Release timelines are communicated.

**2. Select the Practices That Apply:**

- [ ] A public roadmap exists (e.g., GitHub Projects, `ROADMAP.md`, wiki page).
- [ ] The roadmap is updated at least once per release cycle.
- [ ] Community members can suggest or vote on roadmap items.
- [ ] A clear prioritization process exists for new features.
- [ ] Release timelines or version milestones are communicated publicly.

**3. Evidence and Context:**

_Link to your public roadmap or describe how you communicate product direction._

> 💡 **Tip:** A simple `ROADMAP.md` or a GitHub Projects board can be a good start. The key is whether users and implementers can see where the product is heading.

| Field | Recommended input |
|-------|------------------|
| Roadmap URL | `URL field` |
| Additional context | `Text area` |

---

## Pillar 2: Technical Quality & Security

*How robust, secure, and well-engineered the product is.*

### 2.1 Quality Assurance

> **What this measures:** What testing and quality practices are in place?

**1. Select Your Project's Level:**

- ![Emerging](https://img.shields.io/badge/Emerging-blue) — Some testing exists but it is ad hoc. No documented QA strategy.
- ![Growing](https://img.shields.io/badge/Growing-yellow) — A documented testing strategy covers major functional areas. Automated tests exist and run via continuous integration.
- ![Mature](https://img.shields.io/badge/Mature-green) — Comprehensive QA practices cover functional, non-functional, and regression testing. CI/CD pipelines run automatically on every change. Test coverage is tracked, and test data and QA reports are available to the community.

**2. Select the Practices That Apply:**

- [ ] A testing strategy is documented and covers major functional areas.
- [ ] Automated tests run via a continuous integration (CI) system.
- [ ] CI/CD pipelines run automatically on every code change (e.g., on pull requests).
- [ ] Test coverage is tracked and reported.
- [ ] Testing covers functional, non-functional, and regression scenarios.
- [ ] Test data and/or QA reports are available to the community.

**3. Evidence and Context:**

_Link to your CI/CD pipeline, testing documentation, or describe your QA process._

> 💡 **Tip:** Even a basic CI pipeline running unit tests on pull requests is a strong signal. Tools like GitHub Actions, GitLab CI, or Jenkins are commonly used.

| Field | Recommended input |
|-------|------------------|
| CI/CD pipeline URL | `URL field` |
| Testing documentation URL | `URL field` |
| Additional context | `Text area` |

---

### 2.2 Security Practices

> **What this measures:** How are security risks identified and managed?

**1. Select Your Project's Level:**

- ![Emerging](https://img.shields.io/badge/Emerging-blue) — Security is addressed reactively. No formal vulnerability reporting channel exists.
- ![Growing](https://img.shields.io/badge/Growing-yellow) — A security policy is published (e.g., SECURITY.md) with a private reporting channel. Dependencies are monitored for known vulnerabilities.
- ![Mature](https://img.shields.io/badge/Mature-green) — Proactive security practices are in place: regular dependency scanning, static analysis, security audits or penetration testing, and a documented incident response process. The project may hold an OpenSSF Best Practices badge or equivalent.

**2. Select the Practices That Apply:**

- [ ] A security policy (e.g., `SECURITY.md`) is published with a private reporting channel.
- [ ] Dependencies are monitored for known vulnerabilities (e.g., Dependabot, Snyk, Renovate).
- [ ] Static analysis or code scanning tools are part of the development process.
- [ ] A security audit or penetration test has been conducted.
- [ ] A documented incident response process exists.
- [ ] The project holds an OpenSSF Best Practices badge or equivalent certification.

**3. Evidence and Context:**

_Link to your security policy, most recent audit, or describe your security practices._

> 💡 **Tip:** A `SECURITY.md` file with instructions for private vulnerability reporting is a critical first step. Automated dependency scanning (e.g., Dependabot) is lightweight and high-impact.

| Field | Recommended input |
|-------|------------------|
| Security policy URL | `URL field` |
| Last security audit date | `Date field` |
| OpenSSF badge URL | `URL field` |
| Additional context | `Text area` |

---

### 2.3 Architecture & Extensibility

> **What this measures:** Is the product designed for adaptability and extension?

**1. Select Your Project's Level:**

- ![Emerging](https://img.shields.io/badge/Emerging-blue) — The architecture is functional but tightly coupled or monolithic. Limited ability to configure or extend.
- ![Growing](https://img.shields.io/badge/Growing-yellow) — The architecture is modular with documented extension points or configuration options. Components can be adapted independently.
- ![Mature](https://img.shields.io/badge/Mature-green) — A well-documented, modular architecture supports diverse deployment scenarios. A plugin system or extension framework allows customization without modifying the core. The system is designed for horizontal scalability.

**2. Select the Practices That Apply:**

- [ ] The architecture is modular — components can be updated or replaced independently.
- [ ] Extension points or a configuration framework are documented.
- [ ] A plugin system, extension API, or similar mechanism allows adding functionality without forking.
- [ ] Architecture documentation exists and is publicly available.
- [ ] The system supports deployment at different scales (e.g., horizontal scalability).

**3. Evidence and Context:**

_Link to your architecture documentation or describe how the product can be extended._

> 💡 **Tip:** The key question is whether an implementer can adapt the product to their context without modifying the core codebase. Even well-documented configuration options count.

| Field | Recommended input |
|-------|------------------|
| Architecture documentation URL | `URL field` |
| Additional context | `Text area` |

---

## Pillar 3: Deployment & Usability

*How ready the product is for adoption in new contexts.*

### 3.1 Deployment Tooling

> **What this measures:** How easy is it to install and run the product in a new environment?

**1. Select Your Project's Level:**

- ![Emerging](https://img.shields.io/badge/Emerging-blue) — Installation requires significant manual effort. Instructions may be incomplete or assume deep technical knowledge.
- ![Growing](https://img.shields.io/badge/Growing-yellow) — Installation guides are available and reasonably complete. Container images or automated setup scripts exist.
- ![Mature](https://img.shields.io/badge/Mature-green) — Deployment is well-documented for multiple environments (cloud, on-premise, low-resource). Containerized deployments, infrastructure-as-code, and automated installation verification are available. Troubleshooting guides exist.

**2. Select the Practices That Apply:**

- [ ] Installation guides are available and reasonably complete.
- [ ] Container images (e.g., Docker) or automated setup scripts are provided.
- [ ] Deployment is documented for multiple environments (cloud, on-premise, low-resource).
- [ ] Infrastructure-as-code templates are available (e.g., Terraform, Ansible, Helm charts).
- [ ] Automated installation verification or health checks exist.
- [ ] Troubleshooting guides are available for common deployment issues.

**3. Evidence and Context:**

_Link to your installation documentation, Docker Hub images, or describe your deployment options._

> 💡 **Tip:** Can a new implementer go from zero to a running instance by following your documentation? Container images dramatically lower the barrier.

| Field | Recommended input |
|-------|------------------|
| Installation guide URL | `URL field` |
| Docker Hub / container registry URL | `URL field` |
| Additional context | `Text area` |

---

### 3.2 Documentation Depth

> **What this measures:** Is documentation sufficient for different audiences to use the product effectively?

**1. Select Your Project's Level:**

- ![Emerging](https://img.shields.io/badge/Emerging-blue) — Documentation exists but is limited in scope — it may cover only one audience or use case, and lacks depth for implementers or decision-makers.
- ![Growing](https://img.shields.io/badge/Growing-yellow) — Documentation is organized by audience: administrators, end users, developers, and decision-makers each have relevant materials. Implementation guides are available.
- ![Mature](https://img.shields.io/badge/Mature-green) — Comprehensive, versioned documentation covers all user types. It includes tutorials, API references, architectural overviews, and implementation guides. Documentation is actively maintained and community contributions are welcomed.

**2. Select the Practices That Apply:**

- [ ] Separate documentation exists for different audiences (administrators, end users, developers, decision-makers).
- [ ] Implementation guides are available for deploying organizations.
- [ ] Documentation is versioned alongside the product.
- [ ] Tutorials, API references, and architectural overviews are available.
- [ ] Community contributions to documentation are welcomed and reviewed.

**3. Evidence and Context:**

_Link to your documentation site or describe how documentation is organized._

> 💡 **Tip:** Think about the four audiences: a developer who wants to contribute, an administrator deploying the product, an end user, and a decision-maker evaluating it. Does each have what they need?

| Field | Recommended input |
|-------|------------------|
| Documentation site URL | `URL field` |
| Additional context | `Text area` |

---

### 3.3 Internationalization & Localization

> **What this measures:** Can the product be adapted for use in different languages, regions, and cultural contexts?

**1. Select Your Project's Level:**

- ![Emerging](https://img.shields.io/badge/Emerging-blue) — The product is available in one language only. No internationalization framework is in place.
- ![Growing](https://img.shields.io/badge/Growing-yellow) — An internationalization framework exists. The product is available in more than one language, or the content/data supports localization. Community translation contributions are possible.
- ![Mature](https://img.shields.io/badge/Mature-green) — The product supports multiple languages through a mature localization pipeline. Right-to-left languages, local date/number formats, and cultural adaptation are supported. A translation management process enables community-driven localization.

**2. Select the Practices That Apply:**

- [ ] An i18n framework is implemented (e.g., gettext, i18next, ICU).
- [ ] The product is available in more than one language.
- [ ] Community members can contribute translations.
- [ ] Right-to-left (RTL) language support exists.
- [ ] Local date, number, and currency formats are supported.
- [ ] A translation management platform is used (e.g., Transifex, Weblate, Crowdin).

**3. Evidence and Context:**

_List supported languages or link to your translation platform._

> 💡 **Tip:** Even if your product is currently in one language, having an i18n framework in place shows readiness for localization. Translation platforms like Transifex or Weblate lower the barrier for community translators.

| Field | Recommended input |
|-------|------------------|
| Number of supported languages | `Number field` |
| Translation platform URL | `URL field` |
| Additional context | `Text area` |

---

### 3.4 Accessibility

> **What this measures:** Can the product be used by people with diverse abilities, including those with disabilities?

**1. Select Your Project's Level:**

- ![Emerging](https://img.shields.io/badge/Emerging-blue) — Accessibility has not been systematically addressed. The product may present barriers for users with disabilities or those using assistive technologies.
- ![Growing](https://img.shields.io/badge/Growing-yellow) — Basic accessibility practices are followed. The product owner has assessed the product against a recognized standard (e.g., WCAG 2.1 Level A) and addressed major barriers. Key user-facing interfaces are navigable with assistive technologies.
- ![Mature](https://img.shields.io/badge/Mature-green) — The product meets or exceeds WCAG 2.1 Level AA or an equivalent standard. Accessibility testing is part of the QA process. The product owner actively solicits feedback from users with disabilities and documents accessibility conformance.

**2. Select the Practices That Apply:**

- [ ] Basic accessibility practices are followed (e.g., alt text on images, keyboard navigation).
- [ ] The product has been assessed against WCAG 2.1 Level A or equivalent.
- [ ] Major accessibility barriers have been identified and addressed.
- [ ] Key interfaces are navigable with assistive technologies (screen readers, keyboard-only).
- [ ] The product meets WCAG 2.1 Level AA or equivalent.
- [ ] Accessibility testing is integrated into the QA process.
- [ ] An accessibility conformance report or VPAT is published.

**3. Evidence and Context:**

_Link to an accessibility audit, conformance report, or describe your accessibility practices._

> 💡 **Tip:** Start by running a basic accessibility audit (e.g., using Lighthouse, axe, or WAVE). Even identifying and documenting known barriers shows awareness and intent to improve.

| Field | Recommended input |
|-------|------------------|
| Accessibility audit/report URL | `URL field` |
| WCAG conformance level claimed | `Select: None / Level A / Level AA / Level AAA` |
| Additional context | `Text area` |

---

## Pillar 4: Interoperability & Standards

*How well the product works with other systems and adheres to open standards.*

### 4.1 Open Standards Adoption

> **What this measures:** Does the product use recognized open standards for data exchange, APIs, and formats?

**1. Select Your Project's Level:**

- ![Emerging](https://img.shields.io/badge/Emerging-blue) — The product uses custom formats or interfaces for key functions. Interoperability with other systems requires significant adaptation.
- ![Growing](https://img.shields.io/badge/Growing-yellow) — The product uses recognized open standards (e.g., REST, JSON, OpenAPI, FHIR, CSV, RDF) for key interfaces and data exchange. Standards choices are documented.
- ![Mature](https://img.shields.io/badge/Mature-green) — The product fully embraces open standards across its interfaces. APIs are documented using standard specifications (e.g., OpenAPI, AsyncAPI). Data models align with domain-specific standards where applicable. Conformance is tested and documented.

**2. Select the Practices That Apply:**

- [ ] The product uses recognized open standards for key interfaces (e.g., REST, JSON, CSV).
- [ ] Standards choices are documented.
- [ ] APIs are documented using standard specifications (e.g., OpenAPI/Swagger, AsyncAPI).
- [ ] Data models align with domain-specific standards (e.g., FHIR, CKAN, Dublin Core, RDF).
- [ ] Standards conformance is tested and documented.

**3. Evidence and Context:**

_Link to your API documentation or list the open standards your product supports._

> 💡 **Tip:** Can another application easily pull data from your product via an API? Is that API documented with something like OpenAPI/Swagger? List the specific standards you support.

| Field | Recommended input |
|-------|------------------|
| API documentation URL | `URL field` |
| Open standards used | `Text field (comma-separated)` |
| Additional context | `Text area` |

---

### 4.2 Integration Readiness

> **What this measures:** Can the product be integrated into larger systems without modifying its core?

**1. Select Your Project's Level:**

- ![Emerging](https://img.shields.io/badge/Emerging-blue) — Integration requires direct modification of the codebase. No APIs or hooks are exposed for external systems.
- ![Growing](https://img.shields.io/badge/Growing-yellow) — APIs or webhooks are available for key functions. Basic integration documentation exists. The product has been successfully integrated with at least one external system.
- ![Mature](https://img.shields.io/badge/Mature-green) — A well-documented API layer supports integration with third-party systems. The product can participate in a broader ecosystem of building blocks or digital public infrastructure without requiring core modifications. Integration patterns and examples are published.

**2. Select the Practices That Apply:**

- [ ] APIs or webhooks are available for key functions.
- [ ] Basic integration documentation exists.
- [ ] The product has been successfully integrated with at least one external system.
- [ ] Integration patterns and code examples are published.
- [ ] The product can participate in a broader ecosystem without core modifications.

**3. Evidence and Context:**

_Link to your integration documentation or describe known integrations._

> 💡 **Tip:** Name specific systems you've integrated with. If you have integration guides or code examples, link to them here.

| Field | Recommended input |
|-------|------------------|
| Integration documentation URL | `URL field` |
| Known integrations | `Text field (list systems)` |
| Additional context | `Text area` |

---

## Pillar 5: Sustainability & Support

*How viable the product is for the long term and how well product owners support its users.*

### 5.1 Funding & Business Model

> **What this measures:** Is there a plan for financial sustainability beyond the current funding cycle?

**1. Select Your Project's Level:**

- ![Emerging](https://img.shields.io/badge/Emerging-blue) — Funding is project-based or dependent on a single source. No documented sustainability plan exists.
- ![Growing](https://img.shields.io/badge/Growing-yellow) — A sustainability strategy is documented, exploring multiple funding pathways (e.g., grants, service contracts, membership, SaaS). The product owner actively pursues diversification.
- ![Mature](https://img.shields.io/badge/Mature-green) — A diversified sustainability model is documented and operational, with funding from multiple independent sources. Financial transparency is practiced (e.g., public reporting or open budgets). The product owner demonstrates a track record of navigating funding transitions.

**2. Select the Practices That Apply:**

- [ ] A sustainability strategy is documented.
- [ ] Multiple funding pathways are being explored (e.g., grants, service contracts, membership, SaaS).
- [ ] Funding comes from multiple independent sources.
- [ ] Financial information is shared publicly (e.g., annual reports, open budgets).
- [ ] The product has successfully navigated at least one major funding transition.

**3. Evidence and Context:**

_Describe your sustainability strategy or link to relevant public documents._

> 💡 **Tip:** Even an early-stage product can document its sustainability plan. Funders look for evidence that the product won't disappear when the current grant ends.

| Field | Recommended input |
|-------|------------------|
| Sustainability plan URL | `URL field` |
| Number of independent funding sources | `Number field` |
| Additional context | `Text area` |

---

### 5.2 Maintenance Activity

> **What this measures:** Is the product actively maintained and evolving?

**1. Select Your Project's Level:**

- ![Emerging](https://img.shields.io/badge/Emerging-blue) — Updates are infrequent or unpredictable. Release cadence is unclear.
- ![Growing](https://img.shields.io/badge/Growing-yellow) — Regular releases follow a predictable cadence. A changelog is maintained. Dependencies are periodically updated.
- ![Mature](https://img.shields.io/badge/Mature-green) — Active, predictable maintenance with semantic versioning, published release notes, a clear deprecation policy, and timely dependency updates. The project demonstrates sustained activity over multiple years.

**2. Select the Practices That Apply:**

- [ ] Regular releases follow a predictable schedule.
- [ ] A changelog (e.g., `CHANGELOG.md`) is maintained.
- [ ] Dependencies are periodically updated.
- [ ] Semantic versioning is used.
- [ ] Release notes are published for each release.
- [ ] A deprecation policy exists for features and APIs.
- [ ] The project has demonstrated sustained maintenance activity over 2+ years.

**3. Evidence and Context:**

_Link to your releases page, changelog, or describe your release cadence._

> 💡 **Tip:** A consistent release cadence — even if infrequent — signals project health. A `CHANGELOG.md` or GitHub Releases page is easy to set up and highly informative.

| Field | Recommended input |
|-------|------------------|
| Releases / changelog URL | `URL field` |
| Approximate release cadence | `Select: Weekly / Monthly / Quarterly / Biannually / Annually / Irregular` |
| Additional context | `Text area` |

---

### 5.3 User & Implementer Support

> **What this measures:** How are users and implementers supported when they need help?

**1. Select Your Project's Level:**

- ![Emerging](https://img.shields.io/badge/Emerging-blue) — Support is informal — primarily via email or individual contacts. No public support channels.
- ![Growing](https://img.shields.io/badge/Growing-yellow) — Public support channels exist (e.g., forum, mailing list, chat). Known issues are tracked publicly. Response times are reasonable but not guaranteed.
- ![Mature](https://img.shields.io/badge/Mature-green) — Multiple support tiers are available: community support channels, documented FAQ/knowledge base, and optionally commercial support. Issue tracking is public and actively triaged. Implementer onboarding resources are available.

**2. Select the Practices That Apply:**

- [ ] Public support channels exist (e.g., forum, mailing list, Slack/Discord, GitHub Discussions).
- [ ] Known issues are tracked publicly (e.g., GitHub Issues).
- [ ] A FAQ or knowledge base is maintained.
- [ ] Commercial or paid support options are available.
- [ ] Issue tracking is actively triaged with labels and priorities.
- [ ] Implementer onboarding resources (guides, workshops, starter kits) are available.

**3. Evidence and Context:**

_Link to your support channels, issue tracker, or describe how you support users._

> 💡 **Tip:** A public issue tracker where users can see known bugs and request features is one of the most impactful things you can provide. Consider GitHub Discussions or a community forum for broader support.

| Field | Recommended input |
|-------|------------------|
| Community support channel URL | `URL field` |
| Issue tracker URL | `URL field` |
| Knowledge base / FAQ URL | `URL field` |
| Additional context | `Text area` |

---

## Pillar 6 (Optional): Adoption & Ecosystem

*Evidence of real-world use, ecosystem strength, and cost transparency. This pillar is optional — it captures information that is highly valuable to funders and implementers but may be harder for early-stage projects to provide. Product owners are encouraged to complete it when they can.*

### 6.1 Total Cost of Ownership

> **What this measures:** Does the product owner provide transparent information about the costs of adopting and operating the product?

**1. Select Your Project's Level:**

- ![Emerging](https://img.shields.io/badge/Emerging-blue) — No cost guidance is available. Implementers must estimate costs independently.
- ![Growing](https://img.shields.io/badge/Growing-yellow) — Basic cost information is published, covering major cost categories (e.g., hosting, staffing, customization, training). General guidance helps implementers plan budgets.
- ![Mature](https://img.shields.io/badge/Mature-green) — A comprehensive costing framework or TCO model is available, covering infrastructure, human resources, customization, training, and ongoing maintenance. The model is adaptable to different deployment contexts. Real-world cost examples or case studies are shared.

**2. Select the Practices That Apply:**

- [ ] Basic cost categories are documented (e.g., hosting, staffing, training).
- [ ] Budget planning guidance is available for implementers.
- [ ] A comprehensive TCO model or costing framework exists.
- [ ] The TCO model is adaptable to different contexts (e.g., cloud vs. on-premise, country income level).
- [ ] Real-world cost examples or case studies are published.

**3. Evidence and Context:**

_Link to your TCO documentation, costing guides, or describe what cost information you provide._

> 💡 **Tip:** Even rough cost categories (hosting, staffing, customization, training) help implementers plan. If you have real deployment data, sharing anonymized cost ranges is extremely valuable.

| Field | Recommended input |
|-------|------------------|
| TCO documentation URL | `URL field` |
| Additional context | `Text area` |

---

### 6.2 Vendor & Implementer Ecosystem

> **What this measures:** Are there multiple organizations that can implement, customize, or support the product?

**1. Select Your Project's Level:**

- ![Emerging](https://img.shields.io/badge/Emerging-blue) — The founding organization is the only entity with deep implementation knowledge. No documented efforts to grow an implementer network.
- ![Growing](https://img.shields.io/badge/Growing-yellow) — The product owner actively supports ecosystem growth: implementation knowledge is documented and transferable, and at least one external organization has successfully implemented or customized the product.
- ![Mature](https://img.shields.io/badge/Mature-green) — A healthy ecosystem of vendors and implementers exists across multiple regions. The product owner maintains a partner directory or certification program. Implementation knowledge is fully externalized through documentation, training materials, and community support.

**2. Select the Practices That Apply:**

- [ ] Implementation knowledge is documented and transferable.
- [ ] At least one external organization has successfully implemented or customized the product.
- [ ] Multiple implementers exist across different regions.
- [ ] A partner directory, vendor listing, or certification program is maintained.
- [ ] Training materials or implementation toolkits are available for third-party implementers.

**3. Evidence and Context:**

_List known implementers or link to your partner directory._

> 💡 **Tip:** Even naming two or three organizations that have implemented the product is a powerful signal. If you've developed training materials for implementers, link to them.

| Field | Recommended input |
|-------|------------------|
| Partner directory / vendor listing URL | `URL field` |
| Number of known external implementers | `Number field` |
| Additional context | `Text area` |

---

### 6.3 Adoption Tracking

> **What this measures:** Does the product owner track and publish where and how the product is being used?

**1. Select Your Project's Level:**

- ![Emerging](https://img.shields.io/badge/Emerging-blue) — No public information about where the product is deployed or used. Adoption is known informally, if at all.
- ![Growing](https://img.shields.io/badge/Growing-yellow) — The product owner tracks deployments and publishes basic adoption data (e.g., number of known implementations, countries, sectors).
- ![Mature](https://img.shields.io/badge/Mature-green) — Adoption is systematically tracked and publicly reported, including country-level deployment data, sector coverage, and user reach where available. Case studies or implementation stories are published. The product owner actively engages with the implementer community to maintain accurate records.

**2. Select the Practices That Apply:**

- [ ] Basic adoption data is tracked (number of implementations, countries, sectors).
- [ ] Adoption data is published publicly (e.g., on the website or in reports).
- [ ] Country-level deployment data is available.
- [ ] Case studies or implementation stories are published.
- [ ] The product owner actively surveys or engages with implementers to maintain adoption records.

**3. Evidence and Context:**

_Link to your adoption map, deployment data, or published case studies._

> 💡 **Tip:** A simple map or table of known deployments on your website goes a long way. Case studies help funders and implementers understand real-world impact.

| Field | Recommended input |
|-------|------------------|
| Adoption data / deployment map URL | `URL field` |
| Number of known country deployments | `Number field` |
| Case studies URL | `URL field` |
| Additional context | `Text area` |

---

## How to Contribute

We welcome contributions to improve this questionnaire. Please submit a **pull request** to propose changes, improvements, or additional insights.

### Steps to Contribute:

1. **Fork this repository** and create a new branch.
2. **Make changes** to the `questionnaire.md` file.
3. **Submit a pull request** for review.
4. The Community of Practice will review contributions and finalize updates.
