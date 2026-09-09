# Research Funding Opportunities

Opportunity-matched grant teams for NYU Grossman School of Medicine —
Cell Biology, Institute for Systems Genetics, Pathology, Biochemistry and
Molecular Pharmacology, and Microbiology.

**Live site:** https://ben-tenoever.github.io/grants

## Contents

| File | What it is |
|---|---|
| `index.html` | The current slate. Self-contained; no build step, no dependencies. |
| `data/opportunities_2026.json` | Curated open opportunities with agency, deadline, award size and source URL. |
| `data/teams_2026.json` | The submissions: title, tier, contact PI, team with roles, aims with named owners, rationale, gating next step. |

## 2026 slate

44 submissions — 11 large multi-project teams, 6 mid-scale,
7 focused pairs and 20 single-investigator proposals — across 21
opportunities from NIH, NSF, CDC, FDA, ARPA-H, DARPA, DoD and the Gates
Foundation. 157 aims, each with a named owner. Opportunities verified against
primary sources on 7 September 2026.

## Updating

`index.html` carries its data inline so the page works standalone. To refresh,
regenerate both the page and the JSON together, replace all three files, and
commit. Deadline countdowns compute in the browser against the current date, so
an un-refreshed page still shows honest "days left" figures and drops items whose
dates have passed.

Future cycles go in subdirectories (`/grants/2027`) so this URL never changes.

## Related sites

Part of the AI Grant and Collaboration Initiative:
https://ben-tenoever.github.io/grant-teams-hub/
