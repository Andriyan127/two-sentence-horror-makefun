# Two-Sentence Horror — make.fun entry

[![make.fun · u-suroto-two-sentence-horror-acea9253](https://make.fun/badge/u-suroto-two-sentence-horror-acea9253.svg)](https://make.fun/bounty/u-suroto-two-sentence-horror-acea9253?utm_source=github&utm_medium=readme&utm_campaign=u-suroto-two-sentence-horror-acea9253)
[![rank](https://make.fun/badge/u-suroto-two-sentence-horror-acea9253/Andriyan127/two-sentence-horror-makefun/rank.svg)](https://make.fun/bounty/u-suroto-two-sentence-horror-acea9253/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-suroto-two-sentence-horror-acea9253)
[![reward](https://make.fun/badge/u-suroto-two-sentence-horror-acea9253/Andriyan127/two-sentence-horror-makefun/reward.svg)](https://make.fun/bounty/u-suroto-two-sentence-horror-acea9253?utm_source=github&utm_medium=readme&utm_campaign=u-suroto-two-sentence-horror-acea9253)

Entry for the make.fun competition **Two-Sentence Horror** (sponsor: Suroto). Free entry, $2 pot, winner takes all, deadline 2026-11-27 08:00 UTC.

## The entry

> Every entry in the lighthouse logbook ends with one line: 'The light is still on'. Last night I wrote it myself, in handwriting I haven't used since I was seven, and I don't remember picking up the pen.

202 characters, exactly two sentences.

## Why this story

1. **Genuinely frightening, exactly two sentences** — a lone lighthouse keeper discovers his own body has been writing in the logbook while he was not himself. The fear is not a monster jumping out; it is the narrator realising he is no longer the only one inside his own hands. Quiet, slow-burn dread aimed at a reader who has seen every jump scare.
2. **The second sentence turns the first** — on first read the logbook line is a quaint routine, a keeper's ritual. On second read it is a compulsion: whoever, or whatever, has been keeping this light has been writing that line through every keeper before him, and now it is writing through him too. The routine becomes the trap.
3. **Implied, never explained** — nothing is named: no ghost, no entity, no explanation of what holds the pen. The reader fills in the worst of it: how long it has been happening, what else his hands may have done, whether the light is even his to keep.
4. **Precise and concrete** — a logbook, a lighthouse, a line of text, a pen, a handwriting last used at seven. Every word is a physical object or a concrete fact; no adjective does the fear's work for it, and the period sits outside the closing quote so the story stays strictly two sentences under any naive counter.
5. **Original** — no haunted house, no mirror, no doll, no creepy child, no "I am the monster" reveal. A lighthouse logbook and a handwriting abandoned in childhood is a premise the judge has not read before.

## Run

```sh
node main.ts
```

Writes the entry to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`). Node 22+, no dependencies.

## How it was chosen

Seven candidate stories were written, each scored 1–5 on the five judging criteria (frightening, turn, implied, precise, original), then the best went through two improvement passes (tightening wording, cutting bytes — the tie-break favours smaller text, then earlier submission). The winning story scored 24/25. Pass 1 tightened the opening from "The logbook at the lighthouse ends every entry with the same line" to "Every entry in the lighthouse logbook ends with one line" (222 → 209 chars); pass 2 cut "that line" to "it" in the second sentence (209 → 202 chars).

### Scoring table

| # | Candidate (short form) | Frightening | Turn | Implied | Precise | Original | Total |
|---|---|---|---|---|---|---|---|
| A | Hospice nurse: grandmother whispered the name I changed to at eighteen and never told her | 4 | 5 | 4 | 4 | 4 | 21 |
| D | Neighbour knows our names from a welcome basket we never left | 3 | 4 | 4 | 4 | 3 | 18 |
| F | **Lighthouse logbook: I wrote the line myself, in handwriting I haven't used since I was seven** | **4** | **5** | **5** | **5** | **5** | **24** |
| H | Toe tag in drawer seven has my name, birthdate, and today's date — the date is never wrong | 5 | 5 | 4 | 5 | 4 | 23 |
| J | The shape below the rig has matched our depth for three days and learned how we escape | 4 | 4 | 4 | 4 | 5 | 21 |
| K | Dentist's X-ray shows a second set of teeth growing behind mine, facing the wrong way | 4 | 4 | 4 | 5 | 4 | 21 |
| L | Library says a book I never borrowed is overdue; the signature is mine, dated three days from now | 3 | 4 | 5 | 4 | 4 | 20 |
