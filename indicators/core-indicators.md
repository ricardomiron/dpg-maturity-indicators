# Core Indicators

This document defines the maturity indicators used by the DPG Maturity Model. Each indicator is assessed across three levels and tagged with applicable product types and primary audiences.

## Maturity Levels

| Level | Label | What it signals |
|-------|-------|-----------------|
| 1 | **Emerging** | The product is functional but key practices are informal or absent. Suitable for early adopters willing to invest in adaptation. |
| 2 | **Growing** | Core practices are in place and documented. The product can be adopted with moderate effort and has a visible trajectory of improvement. |
| 3 | **Mature** | Practices are well-established, community-driven, and independently verifiable. The product is ready for adoption at scale with confidence. |

Every level is valid. "Emerging" is not a failure — it reflects an early-stage product with room to grow. The model is meant to guide improvement, not gatekeep.

### Audience Tags

- 🔧 **Maintainers** — product owners and core development teams
- 🏗️ **Implementers** — organizations deploying the product in a specific context
- 💰 **Funders** — donors, investors, and grant-making organizations
- 🤝 **Contributors** — developers, designers, translators, and other community members

---

## Pillar 1: Governance & Community

*How the project is led, how decisions are made, and how the community participates.*

### 1.1 Governance Model

**Applies to:** Software, Data, Content, AI · **Audiences:** 💰🔧🤝

How transparent and structured is the decision-making process?

| Emerging | Growing | Mature |
|----------|---------|--------|
| Decisions are made informally by a small group or single organization. No public governance documentation exists. | A governance model is documented and publicly available. Roles, responsibilities, and decision-making processes are defined. | Governance is community-driven with clear pathways for external stakeholders to influence direction. Decision-making is transparent and may involve a steering committee, advisory board, or similar multi-stakeholder structure. |

### 1.2 Community Contribution

**Applies to:** Software, Data, Content, AI · **Audiences:** 🤝🔧💰

How easy is it for others to contribute, and how diverse is the contributor base?

| Emerging | Growing | Mature |
|----------|---------|--------|
| Contributions are accepted but there are no formal guidelines or onboarding materials for new contributors. | Contribution guidelines exist (e.g., CONTRIBUTING.md, code of conduct). The project labels good-first-issues and has a documented review process for external contributions. | The project actively lowers barriers to contribution: onboarding documentation, mentorship practices, responsive review processes, and recognition of community work. Contribution guidelines are maintained for multiple contribution types (code, content, translation, testing). |

### 1.3 Product Roadmap

**Applies to:** Software, Data, Content, AI · **Audiences:** 💰🏗️🔧

Is there a visible plan for where the product is heading?

| Emerging | Growing | Mature |
|----------|---------|--------|
| No public roadmap. Development priorities are managed internally. | A roadmap is publicly available and updated periodically. It reflects planned features, improvements, or content updates. | The roadmap is actively maintained with community input mechanisms. Priorities are informed by user feedback, implementer needs, and strategic goals. Release timelines are communicated. |

---

## Pillar 2: Technical Quality & Security

*How robust, secure, and well-engineered the product is.*

### 2.1 Quality Assurance

**Applies to:** Software, AI · **Audiences:** 🔧🏗️

What testing and quality practices are in place?

| Emerging | Growing | Mature |
|----------|---------|--------|
| Some testing exists but it is ad hoc. No documented QA strategy. | A documented testing strategy covers major functional areas. Automated tests exist and run via continuous integration. | Comprehensive QA practices cover functional, non-functional, and regression testing. CI/CD pipelines run automatically on every change. Test coverage is tracked, and test data and QA reports are available to the community. |

### 2.2 Security Practices

**Applies to:** Software, AI · **Audiences:** 🔧🏗️💰

How are security risks identified and managed?

| Emerging | Growing | Mature |
|----------|---------|--------|
| Security is addressed reactively. No formal vulnerability reporting channel exists. | A security policy is published (e.g., SECURITY.md) with a private reporting channel. Dependencies are monitored for known vulnerabilities. | Proactive security practices are in place: regular dependency scanning, static analysis, security audits or penetration testing, and a documented incident response process. The project may hold an OpenSSF Best Practices badge or equivalent. |

### 2.3 Architecture & Extensibility

**Applies to:** Software, AI · **Audiences:** 🔧🏗️

Is the product designed for adaptability and extension?

| Emerging | Growing | Mature |
|----------|---------|--------|
| The architecture is functional but tightly coupled or monolithic. Limited ability to configure or extend. | The architecture is modular with documented extension points or configuration options. Components can be adapted independently. | A well-documented, modular architecture supports diverse deployment scenarios. A plugin system or extension framework allows customization without modifying the core. The system is designed for horizontal scalability. |

---

## Pillar 3: Deployment & Usability

*How ready the product is for adoption in new contexts.*

### 3.1 Deployment Tooling

**Applies to:** Software, AI · **Audiences:** 🏗️🔧

How easy is it to install and run the product in a new environment?

| Emerging | Growing | Mature |
|----------|---------|--------|
| Installation requires significant manual effort. Instructions may be incomplete or assume deep technical knowledge. | Installation guides are available and reasonably complete. Container images or automated setup scripts exist. | Deployment is well-documented for multiple environments (cloud, on-premise, low-resource). Containerized deployments, infrastructure-as-code, and automated installation verification are available. Troubleshooting guides exist. |

### 3.2 Documentation Depth

**Applies to:** Software, Data, Content, AI · **Audiences:** 🏗️💰🔧🤝

Is documentation sufficient for different audiences to use the product effectively?

| Emerging | Growing | Mature |
|----------|---------|--------|
| Documentation exists but is limited in scope — it may cover only one audience or use case, and lacks depth for implementers or decision-makers. | Documentation is organized by audience: administrators, end users, developers, and decision-makers each have relevant materials. Implementation guides are available. | Comprehensive, versioned documentation covers all user types. It includes tutorials, API references, architectural overviews, and implementation guides. Documentation is actively maintained and community contributions are welcomed. |

### 3.3 Internationalization & Localization

**Applies to:** Software, Data, Content, AI · **Audiences:** 🏗️🤝

Can the product be adapted for use in different languages, regions, and cultural contexts?

| Emerging | Growing | Mature |
|----------|---------|--------|
| The product is available in one language only. No internationalization framework is in place. | An internationalization framework exists. The product is available in more than one language, or the content/data supports localization. Community translation contributions are possible. | The product supports multiple languages through a mature localization pipeline. Right-to-left languages, local date/number formats, and cultural adaptation are supported. A translation management process (e.g., via Transifex, Weblate) enables community-driven localization. |

### 3.4 Accessibility

**Applies to:** Software, Content, AI · **Audiences:** 🏗️🔧🤝

Can the product be used by people with diverse abilities, including those with disabilities?

| Emerging | Growing | Mature |
|----------|---------|--------|
| Accessibility has not been systematically addressed. The product may present barriers for users with disabilities or those using assistive technologies. | Basic accessibility practices are followed. The product owner has assessed the product against a recognized standard (e.g., WCAG 2.1 Level A) and addressed major barriers. Key user-facing interfaces are navigable with assistive technologies. | The product meets or exceeds WCAG 2.1 Level AA or an equivalent accessibility standard. Accessibility testing is part of the QA process. The product owner actively solicits feedback from users with disabilities and documents accessibility conformance. |

---

## Pillar 4: Interoperability & Standards

*How well the product works with other systems and adheres to open standards.*

### 4.1 Open Standards Adoption

**Applies to:** Software, Data, Content, AI · **Audiences:** 🏗️🔧

Does the product use recognized open standards for data exchange, APIs, and formats?

| Emerging | Growing | Mature |
|----------|---------|--------|
| The product uses custom formats or interfaces for key functions. Interoperability with other systems requires significant adaptation. | The product uses recognized open standards (e.g., REST, JSON, OpenAPI, FHIR, CSV, RDF) for key interfaces and data exchange. Standards choices are documented. | The product fully embraces open standards across its interfaces. APIs are documented using standard specifications (e.g., OpenAPI, AsyncAPI). Data models align with domain-specific standards where applicable. Conformance is tested and documented. |

### 4.2 Integration Readiness

**Applies to:** Software, AI · **Audiences:** 🏗️🔧

Can the product be integrated into larger systems without modifying its core?

| Emerging | Growing | Mature |
|----------|---------|--------|
| Integration requires direct modification of the codebase. No APIs or hooks are exposed for external systems. | APIs or webhooks are available for key functions. Basic integration documentation exists. The product has been successfully integrated with at least one external system. | A well-documented API layer supports integration with third-party systems. The product can participate in a broader ecosystem of building blocks or digital public infrastructure without requiring core modifications. Integration patterns and examples are published. |

---

## Pillar 5: Sustainability & Support

*How viable the product is for the long term and how well product owners support its users.*

### 5.1 Funding & Business Model

**Applies to:** Software, Data, Content, AI · **Audiences:** 💰🔧

Is there a plan for financial sustainability beyond the current funding cycle?

| Emerging | Growing | Mature |
|----------|---------|--------|
| Funding is project-based or dependent on a single source. No documented sustainability plan exists. | A sustainability strategy is documented, exploring multiple funding pathways (e.g., grants, service contracts, membership, SaaS). The product owner actively pursues diversification. | A diversified sustainability model is documented and operational, with funding from multiple independent sources. Financial transparency is practiced (e.g., public reporting or open budgets). The product owner demonstrates a track record of navigating funding transitions. |

### 5.2 Maintenance Activity

**Applies to:** Software, Data, Content, AI · **Audiences:** 💰🏗️🤝

Is the product actively maintained and evolving?

| Emerging | Growing | Mature |
|----------|---------|--------|
| Updates are infrequent or unpredictable. Release cadence is unclear. | Regular releases follow a predictable cadence. A changelog is maintained. Dependencies are periodically updated. | Active, predictable maintenance with semantic versioning, published release notes, a clear deprecation policy, and timely dependency updates. The project demonstrates sustained activity over multiple years. |

### 5.3 User & Implementer Support

**Applies to:** Software, Data, Content, AI · **Audiences:** 🏗️💰

How are users and implementers supported when they need help?

| Emerging | Growing | Mature |
|----------|---------|--------|
| Support is informal — primarily via email or individual contacts. No public support channels. | Public support channels exist (e.g., forum, mailing list, chat). Known issues are tracked publicly. Response times are reasonable but not guaranteed. | Multiple support tiers are available: community support channels, documented FAQ/knowledge base, and optionally commercial support. Issue tracking is public and actively triaged. Implementer onboarding resources are available. |

---

## Pillar 6 (Optional): Adoption & Ecosystem

*Evidence of real-world use, ecosystem strength, and cost transparency. This pillar is optional — it captures information that is highly valuable to funders and implementers but may be harder for early-stage projects to provide. Product owners are encouraged to complete it when they can, but it is not required for a maturity assessment.*

### 6.1 Total Cost of Ownership

**Applies to:** Software, Data, Content, AI · **Audiences:** 💰🏗️

Does the product owner provide transparent information about the costs of adopting and operating the product?

| Emerging | Growing | Mature |
|----------|---------|--------|
| No cost guidance is available. Implementers must estimate costs independently. | Basic cost information is published, covering major cost categories (e.g., hosting, staffing, customization, training). General guidance helps implementers plan budgets. | A comprehensive costing framework or TCO model is available, covering infrastructure, human resources, customization, training, and ongoing maintenance. The model is adaptable to different deployment contexts (e.g., cloud vs. on-premise, country income level). Real-world cost examples or case studies are shared. |

### 6.2 Vendor & Implementer Ecosystem

**Applies to:** Software, Data, Content, AI · **Audiences:** 💰🏗️

Are there multiple organizations that can implement, customize, or support the product?

| Emerging | Growing | Mature |
|----------|---------|--------|
| The founding organization is the only entity with deep implementation knowledge. No documented efforts to grow an implementer network. | The product owner actively supports ecosystem growth: implementation knowledge is documented and transferable, and at least one external organization has successfully implemented or customized the product. | A healthy ecosystem of vendors and implementers exists across multiple regions. The product owner maintains a partner directory or certification program. Implementation knowledge is fully externalized through documentation, training materials, and community support. |

### 6.3 Adoption Tracking

**Applies to:** Software, Data, Content, AI · **Audiences:** 💰🏗️🔧

Does the product owner track and publish where and how the product is being used?

| Emerging | Growing | Mature |
|----------|---------|--------|
| No public information about where the product is deployed or used. Adoption is known informally, if at all. | The product owner tracks deployments and publishes basic adoption data (e.g., number of known implementations, countries, sectors). | Adoption is systematically tracked and publicly reported, including country-level deployment data, sector coverage, and user reach where available. Case studies or implementation stories are published. The product owner actively engages with the implementer community to maintain accurate records. |

---

## How to Contribute

This model is a living document. We welcome contributions in the form of:

- **Indicator refinements** — clearer rubric language, better examples, edge case coverage
- **New indicators** — proposals for indicators that address gaps, particularly for data, content, and AI product types
- **Validation feedback** — experiences applying the model to real products, including where indicators felt unclear or misaligned
- **Translations** — localized versions of the indicators to support non-English-speaking product owners

Please open an issue or pull request in this repository to contribute.
