# Enterprise presentation option

Editable source: `enterprise.html`. Saved PDF: `output/pdf/itexus-enterprise.pdf`. Branch: `codex/enterprise-presentation`. Both files are separate from the 25-slide general introduction and the wealth option.

## Content changes

- Enterprise software development positioning on the cover, overview divider and "Who we are" slide, with emphasis on native Windows and cloud .NET development.
- Microsoft partnership added to the technology partners on slide 4.
- A dedicated enterprise experience slide (5): native Windows applications, enterprise web platforms, process automation, document and data management, IoT and operations monitoring, and legacy modernization.
- Slide 6, "Our enterprise expertise domains", replaces the 12 fintech domains with 12 enterprise domains: back-office automation, document management, energy and utilities, IoT and industrial systems, construction, HR and workforce, healthcare operations, insurance, legal and case management, retail and e-commerce, enterprise AI and productivity, and business intelligence. Each maps to published Itexus portfolio projects (for example the billing, energy, document management, claims management, legal case migration to .NET, HR platform and AI database navigator cases). Icons are from [Lucide](https://lucide.dev/) (lucide-static 0.460.0, ISC license), matching the deck’s existing line icons.
- A new integration slide (7), "Integration expertise: Microsoft & Azure", with the Microsoft partnership and Azure services for cloud hosting, data, identity and messaging, DevOps and AI. All nine original integration categories remain on slides 8–9.
- The first and fourth strengths are reframed as "Enterprise-grade delivery" and "Microsoft technology depth".
- Three enterprise case studies (slides 25–27) replace the Coinstar and credit union fintech cases, followed by contacts on slide 28.
- Apart from the fintech domain list, all original delivery, discovery, cooperation, communication, engineering, reporting, QA and support content retained.

## Claim provenance

The cases come from the Enterprise filter of the [Itexus portfolio](https://itexus.com/portfolio/#enterprise), inspected on 27 October 2026. All three are .NET projects:

| Slide | Case | Published facts used |
| --- | --- | --- |
| 25 | [Autonomous B2B Billing & Payments Platform](https://itexus.com/portfolio/autonomous-b2b-billing-payments-platform-for-a-global-fintech-provider/) | .NET 6, Angular, Azure, Clean Architecture and CQRS, KYB, Xero and QuickBooks; 100,000+ invoices per month; $10M+ monthly payment volume |
| 26 | [Energy Resources Consumption Management System](https://itexus.com/portfolio/enegry-resources-consumption-management-system/) | .NET, MS SQL Server, Azure; BI, 3D visualization and administration modules; up to 100,000 devices; hundreds of millions of records; two years; 1 PM, 1 BA, 1 QA, 4 developers |
| 27 | [Document Management System](https://itexus.com/portfolio/document-management-system/) | .NET with iOS/Android apps; access from each work station; classification, version control, notifications; daily backups of revisions; PDF viewer and map-based search |

Each case uses its original published visual.

**User-directed adjustments.** The user required every case to mention native Windows .NET development and allowed adjustments. The public case pages list .NET but do not say "Windows". The following wording is therefore an adaptation, not a published fact. Confirm it with the delivery team before sending the deck to a client:

- Billing: "Native Windows .NET services for billing runs and reconciliation."
- Energy: "Native Windows .NET desktop modules for BI, 3D views and admin."
- Document management: "Native Windows .NET workstation client plus a web dashboard", and the "3 channels: Windows workstation, web and tablet" metric.

**Microsoft partnership.** The Microsoft partnership was supplied by the user for this option. The itexus.com technologies page lists .NET, Microsoft SQL Server and Microsoft Azure but does not state a partner status or tier. The deck says "Microsoft partner" without naming a program level.

**Azure services.** The services on slide 7 are representative Azure capabilities, not services traced to specific projects. Remove or adjust any the team does not want to claim.

Microsoft Azure, .NET and SQL Server artwork is embedded from itexus.com (`/images/uploads/2021/04/microsoft-azure-color.svg`, `/images/uploads/2023/01/ico-MicrosoftNET.svg`, `/images/uploads/2023/01/ico-MicrosoftSQLserver.svg`).

## Regenerating

`enterprise.html` was generated from `index.html` by string replacement, so later changes to the general introduction are not picked up automatically. Edit `enterprise.html` directly. Re-export the PDF through the Print/PDF control after edits so the saved PDF stays in sync.

## Validation

- 28 slides with correct numbering; no images failed to load.
- Every slide checked in Chromium for content overflowing the slide or crossing the footer. Case slides keep the same footer clearance as the original cases.
- PDF: 28 pages at the same 16:9 page size as the other options.
