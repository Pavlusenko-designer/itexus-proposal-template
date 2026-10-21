# Company presentation content map

Source: the supplied local `Itexus presentation.pdf` (18 pages), plus the two case studies from the original repository's `main` branch. Output: `index.html` (25 slides) on `codex/intro-presentation`.

The PDF supplies company introduction content; the existing HTML proposal supplies the visual template and the Coinstar and credit union case studies. All substantive source blocks are retained in their original sequence, with the two case studies before the closing contact slide. Dense blocks are split across slides so the deck remains readable. Each HTML slide also records its source page in `data-source-pages`; the case studies use `proposal:28` and `proposal:29`.

| PDF page | Source block | HTML slide(s) | Preserved content |
| --- | --- | --- | --- |
| 1 | Software Development & Consulting | 1 | Company positioning and presentation cover. |
| 2 | Itexus: Company Overview | 2 | First section divider. |
| 3 | Who we are | 3–4 | 300+ projects and 80+ fintech projects over ten years; 130+ specialists; 50+ senior developers; five industries; development, DevOps, QA, BA, PM and design roles; crypto, stock trading, capital management and neobanking; 94% retention; 75% referrals; 170+ clients in 23 countries; 140+ partners; startups/accelerators, payments, KYC, BAA and trading partners; AWS, Azure, Google Cloud, DigitalOcean and Heroku/PaaS; client geography 43% USA, 38% Europe, 19% other; original recognition badges and Clutch 39-review artwork. |
| 4 | Our Fintech expertise domains | 5 | Trading, digital banking, eWallets, digital lending, credit scoring, claims management systems, RegTech, personal finance management, InsurTech, online payments, banking process automation, wealth management and investment. |
| 5 | Integration Expertise | 6–7 | All nine categories and all provider names transcribed from the source logos: bank aggregation, trading, financial data, charting, KYC/AML, payments, email/SMS, speech recognition, maps/geocoding. |
| 6 | Our strengths | 8 | Ten years of high-load fintech delivery, experienced fintech BAs, end-to-end service design/QA/support, startup technology experience, flexible agile delivery. Original source photograph. |
| 7 | How We Work | 9 | Second section divider. |
| 8 | Staff Augmentation | 10 | Client control, integration with existing teams, hiring overhead, flexible scaling, part-time/full-time specialists. Original source photograph. |
| 9 | Project-based | 11 | All seven principles: agile flexibility, collaboration, cost efficiency and efficient-hour billing, budget control, weekly progress/cost reporting and approval, documentation, collective expertise. |
| 10 | Project Activities & Deliverables | 12–13 | All four phases. Presales: MVP/product scope, estimate, timeline, indicative cost. Discovery: vision, stories, architecture, services analysis, priorities, detailed estimate. Development/testing: deployed apps, CI/CD, requirements/stories/acceptance criteria, progress reports, release notes, complete test documentation. UAT/rollout: guides, handover, UAT results, stabilization backlog. |
| 11 | Discovery Phase Zoom-In | 14–15 | All four roles and all three stages (Assess / Analyze & elaborate / Finalize). Includes stakeholder interviews, plans/resources/schedule, risk register, requirements, provider analysis, WBS, prioritized backlog, next two sprints, nonfunctional requirements, data warehouse integration, integration risks, architecture, estimates, branding, personas, journeys, mockups, wireframes and clickable prototype. |
| 12 | Agile Delivery Methodology | 16 | Two-week sprint, daily scrum, product and sprint backlogs, planning, definition of done, review, retrospective, product owner/team/scrum master; transparent communication, adaptation, visible hypothesis testing, planning and forecasts/reporting. |
| 13 | Communication & Collaboration | 17 | Poland development center, shifted schedule with 4–5 hours of US overlap, onsite travel, daily standups, sprint reviews/retrospectives/demos; Skype, Google Hangouts, Gmail, Cisco Webex, Slack and Confluence transcribed from the source artwork. |
| 14 | Coding Standards | 18 | Formatting, naming, organization/comments, error handling/security; KISS/YAGNI/DRY; code review; technical debt, commits per day, duplication, unit coverage, security violations; SonarQube, ESLint, Flake8, Bandit; legal and security compliance. |
| 15 | Transparency & Reporting | 19 | Accessible status, costs, bottlenecks, risks, problems and solutions; daily status, at least weekly issues/improvements and project updates, at least monthly finances/forecasts and financial reports. |
| 16 | Quality first | 20–21 | Early testing/defect prevention, ISTQB professionals, ISO/IEC 25010, OWASP Top Ten; unit/service/UI test pyramid with manual testing; unit coverage, automated regression, manual QA and future automation, Jira defect tracking, tests on every CI/CD change. |
| 17 | Support and maintenance | 22 | Dedicated third-line capacity and immediate response, batches of tasks as mini-projects, pay as you go subject to resource availability, preferred cooperation by discussion. Original source photograph. |
| Original proposal, slide 28 | Coinstar digital wallet | 23 | Original business context, wallet/backend/bank-linking/crypto/identity/compliance capabilities, four-month first release, 6,500+ users in the first two months, original product visual and portfolio source link. |
| Original proposal, slide 29 | Credit union onboarding | 24 | Original US credit union/AS400 context, onboarding/KYC/KYB/funding/compliance capabilities, five days to 15 minutes for account opening, 5,000+ monthly applications, original product visual and portfolio source link. |
| 18 | Contact us | 25 | itexus.com, info@itexus.com, LinkedIn, Facebook, Twitter, Instagram, Dribbble, Behance and Clutch. URLs copied from the PDF link annotations. |

## Editorial changes

- Lightly rewrote sentences for concise presentation English without changing the substantive offer or metrics.
- Split company overview, integrations, phase deliverables, discovery roles and quality content across multiple slides.
- Generalized the discovery example's customer name “Coinme” to “existing application.” It is an example customer, not an Itexus company credential.
- Corrected apparent source spelling: “ESlist” to “ESLint,” “Flake 8” to “Flake8,” and “Bulks of tasks” to “Batches of tasks.” Expanded GC to Google Cloud. The unexplained source acronym BAA is retained as written.
- Retained historical provider and tool names as supplied, including TD Ameritrade, SynapseFI, Sendinblue, Skype and Google Hangouts. These are source experience details, not a new assessment of provider availability.
- Preserved the original recognition and 39-review artwork rather than importing different credentials or review counts from the proposal template.
- Kept 130+ specialists separate from 170+ clients. Neither the figures nor the ten-year source timeframe have been recast as newly verified current data.
- Replaced the proposal's sample client, project scope, estimates and prices with company introduction content. The original two fintech case studies are included as relevant experience. No new commercial quotation is implied.

## Visual asset sources and refinements

- All nine integration logo rows are rendered from the supplied PDF's original provider artwork. Accessible image descriptions retain every provider name. Original provider identities are preserved.
- Skype, Google Hangouts, Gmail, Cisco Webex, Slack and Confluence icons are recovered from the original collaboration artwork on PDF page 13.
- SonarQube uses the official mark from the product logo archive linked by the [Sonar press kit](https://www.sonarsource.com/company/press-kit/).
- ESLint uses the isolated logomark from the official SVG on the [ESLint branding page](https://eslint.org/branding/).
- Bandit uses the project's [official logomark](https://github.com/PyCQA/bandit/tree/main/logo). Flake8 uses a labelled code-check symbol in the presentation's line icon style.
- Strengths and daily/weekly/monthly reporting use semantic line icons matching the existing template.
- The agile diagram now connects sprint review back to the product backlog, showing feedback and retrospective outcomes shaping the next sprint.
- The quality diagram is an SVG triangle with aligned outer slopes, three automated testing levels, and a rounded manual-testing cloud resting directly on the peak, following the supplied visual reference.
- Case studies retain their original repository text, metrics, images and links: [Coinstar wallet](https://itexus.com/portfolio/digital-wallet-and-app-ecosystem-for-coinstar-a-2-2b-global-fintech-firm/) and [credit union onboarding](https://itexus.com/portfolio/digital-onboarding-platform-for-a-credit-union/). Results are company-reported claims from those existing case slides, not newly measured outcomes.

## Template retained

The 1600×900 canvas, charcoal/green palette, Inter fonts, italic uppercase titles, white/green logo, geometric brand motifs, footer numbering, presentation controls, keyboard/touch navigation, overview, fullscreen, Help and print styles come from the existing HTML template. New layouts are scoped to the company introduction. All required assets are embedded for offline use.
