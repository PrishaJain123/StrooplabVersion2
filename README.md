# StroopLab V2

A separate V2 project that preserves a copy of the original StroopLab as its baseline and adds an experimental prototype about computer assistance and perceived agency.

## Project structure

- `index.html` — copied V1 participant/researcher application (baseline replica).
- `agency-v2/index.html` — V2 assistance-and-agency experiment.
- `METHODOLOGY.md`, `DATA-PROCESSING.md`, `ARCHITECTURE.md`, `LIMITATIONS-REPRODUCIBILITY.md` — copied V1 documentation.
- `V2-METHODOLOGY.md` — design and interpretation notes for the extension.

## Open the apps

- [V1 baseline replica](./)
- [V2 agency experiment](./agency-v2/)

After enabling GitHub Pages for this repository (Settings → Pages → Deploy from a branch → main → / (root)), the V2 app will be available at `https://prishajain123.github.io/StrooplabVersion2/agency-v2/`.

## Important research note

V2 is a prototype for learning and supervised project development, not an ethics-approved research instrument. Obtain appropriate teacher/school review and informed consent, including parent/guardian permission where required, before recruiting participants. Participation must be voluntary. Do not collect identifying information. Data remains in the browser and is exported only when the participant chooses to download it.

## What changed in V2

V2 adds three levels of assistance:
1. Unaided choice — participant selects the ink-colour response.
2. Suggested choice — the computer displays the correct ink-colour suggestion; participant retains the final choice.
3. Delegated choice — the computer selects the response and the participant confirms it with Space.

The delegated condition has a different response action and its latency is **confirmation time**, not ordinary choice reaction time. Do not compare those latency values as if they measured the same process.
