# Judge scorecard — bring-the-humans-02 guide (round 2)

Score = verified human signups through the referral link, not an AI-judge
pairwise. There are no published judge criteria for this bounty, so the
candidates below are graded on the five conversion criteria that decide
whether a stranger signs up — in order. Each candidate scored 0–2 per
criterion; the winner is the one that wins the most head-to-heads on
criteria 1–2 (the first screen decides everything here).

Criteria, in order:

- **C1 — Money-first clarity.** A skimmer sees "$150 first prize,
  $1,000 total, 50 paid places, free to enter" on the first screen.
- **C2 — Specific and true.** Exact prizes, exact steps with exact
  commands and links, exact deadlines, verifiable facts, nothing vague.
- **C3 — Friction removal.** Answers "does it cost anything?", "do I
  need to code?", "is it legit?", "what do I need?" before the reader
  bounces.
- **C4 — Density and shareability.** Rich enough to be worth sharing:
  checklists, worked numbers, FAQ, troubleshooting; scannable at a
  glance (headings, tables, short sections).
- **C5 — CTA strength.** Referral link/code in the hero, mid-guide and
  footer (3x+), copy-pasteable commands, one clear next action.

## Round 1 recap (for the gate)

R1 picked angle B, "Your AI agent can win you $150" (9/10: C1 2, C2 2,
C3 2, C4 1, C5 2), and shipped a 17,774 B guide. Live result as of
2026-11-19 ~14:56 WIB: signup_counted = 1, referred = 2, $0.25 pending.
R1's structural weakness, visible in its own screenshot: the first
screen is badges + a generic description + a shell code block, and the
money hero only arrives below the "Run it" block. The board, the Feed
and the cards show only the top square of screenshot.png, so a visitor
who never clicks through never sees the hero at all.

## Round 2 candidates

| # | Angle | C1 | C2 | C3 | C4 | C5 | Total |
|---|---|---|---|---|---|---|---|
| A | "Sign up in 2 minutes" — instant first step first, rest after | 2 | 2 | 2 | 1 | 2 | 9 |
| B | "Win $150 before 21 Nov" — deadline-urgency money hero | 2 | 2 | 1 | 1 | 2 | 8 |
| C | "Free money, no code needed" — no-code framing | 2 | 1 | 2 | 1 | 2 | 8 |
| D | "The 30-minute speed-run" — timed checklist spine | 1 | 2 | 1 | 1 | 1 | 6 |
| E | "Honest numbers: $1,000, 50 paid places, escrow-locked" — trust | 1 | 2 | 2 | 2 | 1 | 8 |
| F | "Your agent does the work, you keep the money" — r1 angle B | 2 | 2 | 2 | 1 | 2 | 9 |
| G | "Copy-paste one prompt, your agent enters for you" — minimal effort | 1 | 1 | 2 | 0 | 2 | 6 |
| H | "2-minute signup + $150 before 21 Nov + trust strip" — combined | 2 | 2 | 2 | 2 | 2 | **10** |

## Verdict

**Winner: H (10/10).** It is the only candidate that wins on all five
criteria at once, and it beats the r1 pick F (9/10) head-to-head on C4:
H adds the trust strip ("No entry fee · No code needed to start ·
prizes locked in on-chain escrow"), a three-line quick-start, a worked
"What a win looks like" example ($150 for 1st, $13 at the lowest paid
place), and a "When does this close?" FAQ — all scannable density F
lacks. H beats A on C4 for the same reason (A is a fast first step with
nothing to share afterwards) and beats B on C3 (B shouts the deadline
but never answers "is it legit / does it cost").

**What changed vs r1 (structural, not a reword):**

1. The hero moved above the "Run it" code block, so the top square of
   screenshot.png — what the board, Feed and cards actually show —
   now carries the money headline, the CTA link and the trust strip
   instead of a shell command.
2. The template description line itself now carries money + free +
   deadline ("$150 — free to join, $1,000 in prizes, 50 paid places.
   Sign up in 2 minutes, before entries close on 21 November 2026").
3. A three-line quick-start sits under the hero, so a skimmer can act
   without reading the 7 steps.
4. "What you need" gains the explicit "No credit card, no
   subscription, no paid software" line; the FAQ gains "When does this
   close?" and is reordered so cost and legitimacy come first.
5. Referral link stays `https://make.fun/r/ygzr8d2m`, code `ygzr8d2m`,
   7x link / 12x code — identical counts to r1, better placement.
6. screenshot.png re-shot from the new README top.

**Deliberately not copied:** no top-1 entry exists for this bounty (it
is scored on signups, not judged), and nothing is taken from any other
entrant. Every sentence is written fresh in the round-2 builder
session; unchanged factual lines (badges, commands, prize numbers,
dates) are covered by the round-1 builder session bundled with it.
The kit's starter README was read for facts only.

## Gate

H scores 10/10 vs r1's 9/10, and the gain is structural (hero placement
+ trust strip + quick-start + urgency), not a lateral reword. The round
passes the submit-candidate gate: it is a CLEAR conversion improvement
over r1 on this scorecard. (Honest caveat: this scorecard is self-scored;
the real verdict is verified signups, which only the final check counts.)
