# Itexus proposal template

A self-contained, offline HTML presentation for medium and large software development proposals. The base deck contains 31 slides with Itexus branding and illustrative customer content.

## Open the presentation

Open `index.html` in a browser. No installation or build step is needed. Fonts, logos and case-study visuals are embedded.

Use the presentation controls for navigation, overview, fullscreen, help and print/PDF. Content and branding sources are recorded in the presentation’s Help panel.

## Create a client presentation

Keep `main` as the reusable template. Create a branch for each engagement:

```sh
git switch main
git pull --ff-only
git switch -c clients/customer-project
```

Edit `index.html` directly, replacing the example business case, scope, assumptions, phases, team, timeline, technology choices and commercial terms. Add or remove slides as needed; navigation and displayed page numbers adapt automatically.

```sh
git add index.html
git commit -m "Tailor proposal for customer project"
git push -u origin clients/customer-project
```

Client-specific content stays on its client branch. Merge only reusable template improvements back into `main`. A branch inherits the repository’s visibility; it does not provide separate access control. Use a separate private repository when a client proposal requires different access.

## Before sharing

- Replace all illustrative customer details, amounts and assumptions.
- Confirm that phase scope, outcomes, durations, staffing and prices agree throughout the deck.
- Distinguish fixed fees from indicative estimates and confirm payment terms.
- Review every slide at 16:9 and check the browser’s print/PDF output.
- Review the source notes before reusing company figures or case-study claims.

## Hosting

The presentation is a static file and can be hosted without a build step. If GitHub Pages is enabled, it serves the repository’s `main` branch; pushing a client branch does not replace the template site.

## Branding and source material

Itexus logos, embedded fonts, company information and portfolio visuals come from the supplied proposal and the company sources documented in the presentation. Customer examples and commercial figures are illustrative. No additional license is granted for third-party assets by this repository.
