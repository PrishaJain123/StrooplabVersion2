# StroopLab V2 — Methodology and design rationale

## Research question
How does the level of computer assistance relate to task performance and a participant's reported sense of control, action ownership, and trust?

## Design
A within-participant exploratory design with three blocks. Block order is randomized for each session. Each block contains 24 Stroop stimuli: 12 congruent and 12 incongruent. The task begins with 10 practice trials, which are not included in the main dataset.

### Conditions
- **Unaided:** participants identify the ink colour using R/G/B/Y.
- **Suggestion:** the correct ink-colour suggestion is displayed, but participants still choose and press R/G/B/Y.
- **Delegated:** the computer selects the response; participants press Space to confirm it.

The suggestion is intentionally accurate in this prototype. This isolates the presence of assistance from the separate question of whether an assistant is reliable. A future study could manipulate suggestion reliability, but that requires a preregistered design and careful debriefing.

## Outcomes
- Accuracy on participant-selected responses (unaided and suggestion).
- Choice reaction time on participant-selected responses (unaided and suggestion).
- Confirmation latency in the delegated condition.
- Three 1–7 retrospective ratings for each block: perceived control, action ownership, and trust.

**Important:** delegated confirmation latency is not the same dependent variable as choice reaction time. Delegated accuracy is determined by the computer's selection, so it is not directly comparable with participant accuracy. Interpret these measures separately.

## Stimuli and response mapping
The four words/ink colours are RED, GREEN, BLUE, and YELLOW. Keys R/G/B/Y map to the corresponding ink colour. Each main block balances congruent and incongruent trials equally. Trial order is randomized within blocks.

## Data handling
No name, email, or other direct identifier is requested. The application does not transmit data to a server. Trial data stays in the active browser session and is exported as a CSV only when the user chooses Download. Closing or reloading the page may lose unsaved session data.

## Participant protection
This prototype is not ethics-approved and should not be used to recruit participants without appropriate review. Obtain teacher/school approval and informed consent; obtain parent/guardian permission for participants under 18 where required by the school or applicable rules. Participation must be voluntary, and participants must be free to stop. Do not collect sensitive or identifying information. For a school project, follow the school's research and safeguarding requirements.

## Interpretation
This is an exploratory demonstration, not evidence that assistance universally reduces agency. Ratings are brief self-report measures created for this prototype, not validated psychometric scales. A single-session Stroop task cannot establish broad claims about agency in BCIs, robotics, or other real-world systems. Counterbalancing block order reduces one source of order bias but does not eliminate learning, fatigue, or demand characteristics.
