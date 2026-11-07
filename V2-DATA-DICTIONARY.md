# StroopLab V2 — Data dictionary

The CSV export contains trial rows followed by a blank line and a block-rating section.

## Trial fields

| Field | Meaning |
|---|---|
| trial | Sequential row number within the session |
| phase | Main task (practice trials are not exported) |
| condition | unaided, suggestion, or delegated |
| word | Colour word displayed |
| ink_colour | Correct target: the colour of the text |
| congruency | congruent or incongruent |
| response | R/G/B/Y-mapped colour, or SPACE_CONFIRM |
| correct | 1 or 0; delegated responses are system-selected |
| latency_ms | Time from stimulus display to keypress |
| latency_type | choice_reaction_time or confirmation |

## Block ratings
The second CSV section contains one row per condition with perceived_control (1–7), action_ownership (1–7), and trust (1–7).

## Analysis cautions
Do not combine delegated confirmation latency with choice reaction times. Do not interpret delegated accuracy as participant accuracy. For a simple comparison of participant-controlled performance, compare unaided and suggestion blocks. Treat the block ratings as exploratory self-report outcomes.
