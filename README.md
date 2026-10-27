# Itexus introduction presentation

A self-contained, offline company introduction built from the supplied **Itexus presentation.pdf**, using the existing proposal template. This branch contains 25 slides, retains every substantive block from the 18-page source, and includes the original repository's two fintech case studies.

Branch: `codex/intro-presentation`. The reusable 31-slide commercial proposal remains on `main`.

## Open the presentation

Open `index.html` in a browser. No installation or build step is needed. Fonts, logos, photographs and recognition artwork are embedded.

Use the presentation controls for navigation, overview, fullscreen, help and print/PDF. Content and branding sources are recorded in the presentation’s Help panel.

## Presentation options and PDFs

| Option | Editable HTML | PDF | Slides |
| --- | --- | --- | --- |
| General company introduction | [index.html](index.html) | [General introduction PDF](output/pdf/itexus-introduction.pdf) | 25 |
| Wealth management | [wealth-management.html](wealth-management.html) | [Wealth management PDF](output/pdf/itexus-wealth-management.pdf) | 27 |
| Enterprise | [enterprise.html](enterprise.html) | [Enterprise PDF](output/pdf/itexus-enterprise.pdf) | 27 |

The enterprise option is on the `codex/enterprise-presentation` branch. It focuses on native Windows and cloud .NET development, adds the Microsoft partnership and an "Integration expertise: Microsoft & Azure" slide, and replaces the fintech cases with three .NET enterprise cases from the Itexus portfolio. See [ENTERPRISE-VARIANT.md](ENTERPRISE-VARIANT.md) for changes and which wording needs confirmation.

The wealth option introduces investor and advisor capabilities, puts Orion Advisor in the integration experience, adds a published wealth-advisory platform case, and incorporates the user-supplied Orion integration detail in both existing cases. All company figures and the original delivery content remain. See [WEALTH-VARIANT.md](WEALTH-VARIANT.md) for changes and source provenance.

## Content

- Company overview, team, client figures, geography and partner ecosystem.
- All 12 fintech expertise domains and all 9 integration categories, including the named providers.
- Strengths, staff augmentation and project-based cooperation.
- Presales, discovery, development, testing, UAT and rollout deliverables.
- Discovery activities for the project manager, business analyst, architect and designer.
- Agile methodology, communication, coding standards, reporting, QA and support.
- Coinstar digital wallet and credit union onboarding case studies, with original product visuals and results.
- Website, project and partnership email, six social profiles and Clutch link.

Integration provider logos and collaboration app icons are embedded from the PDF. Strengths and reporting use matching line icons. The agile diagram closes the sprint loop; the quality slide presents three automated testing practices alongside manual product testing. Code tools have labelled icons, including official SonarQube, ESLint and Bandit artwork.

See [SOURCE-CONTENT.md](SOURCE-CONTENT.md) for the page-by-page content map and editing notes. Figures follow the supplied company presentation: **130+ specialists** and **170+ clients** are different measures. The source's historical provider names, collaboration tools and recognition are retained, with context in Help.

## Work on this presentation

```sh
git switch codex/intro-presentation
```

Edit `index.html` directly. Slides have readable HTML content, `data-title` labels and `data-source-pages` references. Add or remove slides as needed; navigation and displayed page numbers adapt automatically. Keep company introduction changes on this branch.

## Before sharing

- Review company figures and historical provider names before updating them.
- Preserve the source content map when adding or reorganizing content.
- Review every slide at 16:9 and check the browser's print/PDF output.

The deck has been checked in Chromium for all 25 slides, keyboard navigation, overview, Help, offline assets, phone and laptop viewport fit, and 25-page print output.

The wealth option has the same checks across 27 slides. Both saved PDFs were rendered and inspected, with one 16:9 slide per page and correct page numbering. PDF links remain interactive.

## Hosting

GitHub Pages currently serves the proposal template from `main`. This branch does not replace that live presentation. Open the local HTML to preview the introduction.

The repository is public, including all branches. Use a separate private repository for confidential customer proposals.

## Branding and source material

Company content, integration logos, collaboration icons, photographs and recognition artwork come from the supplied `Itexus presentation.pdf`; the branding, Inter fonts, controls, slide framework, specialist photograph and two case studies come from the existing HTML proposal template. Additional tool artwork and its provenance are documented in Help and [SOURCE-CONTENT.md](SOURCE-CONTENT.md). The source PDF is a local reference and is not required to open the deck. No additional license is granted for third-party assets by this repository.
