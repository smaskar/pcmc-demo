# PCMC operational workflow mockups

[Open the live demo](https://smaskar.github.io/pcmc-demo/)

A focused, clickable concept demonstration prepared by Sarvaha Systems for discussion with Pimpri Chinchwad Municipal Corporation (PCMC).

All case names, records, quantities and statuses are fictional examples. This is not an official PCMC service or a statement about PCMC's current operational performance. The proposed workflows and responsibilities require departmental confirmation.

## Four independent application concepts

1. **Wastewater operations** — review an operational exception, its evidence, proposed owner and next action.
2. **Builder water commitments** — review an undertaking, supply evidence and departmental follow-up.
3. **Hospital collection reconciliation** — explain differences between collections, settlement records and deposits.
4. **Contractor bill verification** — check supporting references before the authorised review decision.

Each concept includes an overview and a case-detail view. Use the sidebar to change systems, filter the sample cases and select **View** to inspect a case.

## Prototype scope

- Sample case navigation, search and filters
- Evidence, proposed responsibility and review history
- A temporary draft review note, held only in the current browser tab
- No connection to PCMC systems, external APIs or databases
- No official approvals, payment execution, enforcement or notifications
- No costing or financial estimates

Refreshing the page clears any draft notes. Saving a note does not change the case status.

## Run

Open `index.html` in a browser. The prototype has no build step or dependency installation.

GitHub Pages publishes this repository from the root of the `gh-pages` branch. `.nojekyll` keeps the site as plain static files. To publish a reviewed update, merge `main` into `gh-pages` and push that branch.

JavaScript syntax check:

```sh
node --check app.js
```

## Files

- `index.html` — application shell and information dialog
- `styles.css` — responsive screen layouts
- `app.js` — fictional case data and browser-only interactions

Before defining production scope, confirm the existing workflow, responsible roles, evidence sources, integration availability and acceptance criteria with PCMC.
