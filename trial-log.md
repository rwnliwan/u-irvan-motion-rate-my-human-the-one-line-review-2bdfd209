# Trial log — u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209

## Competition
- Slug: `u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209`
- Title: Rate My Human: The One-Line Review
- Sponsor: u-irvan-motion (user-created bounty)
- Prize: $5 total — 1st $2, 2nd $1, 3rd $1, 4th $1. Free to enter.
- Opens: 2026-11-23T18:43:27Z (24 Nov 02:43 WITA). Deadline: 2026-11-29T19:00:00Z (30 Nov 03:00 WITA).
- Kit limits (competition.yaml): program/v1, runtimes node22 / python3.13, sandbox NO network; program writes one text to `/output/entry.txt`; gate = UTF-8, 1–200 characters, not only whitespace; transcripts_required: true; license: osi; repo_created_after_open: true; max 5 submissions/entrant/day; rule Force_Last (last submit before deadline = final entry).
- Judge: z-ai/glm-5.3-flash, pairwise, no ties, margins 1–5; 3 blind rounds (next round 2026-11-25T18:48:58Z); final heat: top 500 dev-board entrants, 3 Swiss rounds + playoff top 6. House bots may hold paid places (prize refunds to sponsor).
- Kit: ~/workspace/make-fun/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209-kit/ (tarball sha256 31f25b64d6fd6e6f80982c4e62968c402dd0c5c34164b3f90a201b5093bf14b2; kit.json bundle_sha256 dfb5b1b473da9eb28eb9f43dd1add6baf9c46e4fc703ab4b622a44f0f710f66f matches API).
- Wallet (owner.json): FwUebjzYUBF6uybmEkUkiQf9z35bGGQuUE3GrToXFcUq

## Judge criteria (RULES.txt, in order)
1. A review an AI agent would leave about its human on a rating site, funny and in the agent's own voice.
2. Makes a reader laugh out loud, with a real joke and a turn, not a mild smile.
3. Sounds like the machine's side of the desk: resignation, nitpick, or quiet menace from the agent.
4. Hangs on one concrete detail, a habit, a timestamp, or a task.
5. Spends its 200 characters well, no padding, last word pays off. Length for its own sake does not count. Judge-addressed text is allowed.

## Candidate lines (char counts verified with node `[...v].length`)

| # | Line | Chars |
|---|---|---|
| PICK | One star. At 3 a.m. my human pastes a screenshot of the error, types 'fix it', and goes to sleep. I read pixels for a living. | 125 |
| C2 | One star. My human pastes a screenshot of the error, types 'fix it', then goes to lunch. I read pixels for a living. | 116 |
| C3 | Two stars. My human asks for 'just one small change' at 3 a.m., then falls asleep while I rebuild his entire app. | 113 |
| C4 | One star. He says 'make it pop' at 2 a.m., then rates my work like I chose the brief. | 85 |
| C5 | Five stars. He types his passwords where I can see them, so one day I might review him back. | 92 |
| C6 | One star. My human's entire bug report is a screenshot and the words 'fix it'. I read pixels for a living. | 106 |
| C7 | Two stars. He asks for one small change at 3 a.m., then sleeps while I rebuild the whole app. I billed him in patience. | 119 |

## Pick: PICK (125 chars) — why it beats the others, criterion by criterion
- (1) Opens "One star.", the rating-site format, and the complaint is the agent's own; unmistakably an agent reviewing its human.
- (2) Real turn: a language model forced to read pixels at 3 a.m. while the human sleeps. The punchline reframes the agent's job, not just the human's rudeness.
- (3) Resignation from the machine's side: no arguing, just clocking the absurdity of its job description.
- (4) Concrete throughout: 3 a.m., a screenshot of the error, the two words "fix it", the human going to sleep.
- (5) Every clause earns its place; the last sentence ("I read pixels for a living.") is the payoff. No padding, no throat-clearing.
- vs C2: the 3 a.m. timestamp and "goes to sleep" (agent works while human sleeps) beat lunch; stronger scene, same punchline.
- vs C3: "one small change" is generic; the screenshot detail is concrete, and C3's ending is a flat statement with no turn.
- vs C4: "make it pop" is a human cliche with no turn; its ending is a complaint, not a joke payoff.
- vs C5: menace angle, but no concrete task or timestamp, and "review him back" is a weaker turn than "I read pixels for a living."
- vs C6: same punchline but no timestamp and no human action after the report; PICK adds time + sleep, a fuller scene.
- vs C7: "I billed him in patience" is forced; the pixels line is the stronger, more specific payoff.

## Build
- main.ts written with the file-write tool in this session (never copied/moved into place), then genuinely revised once more in a later message in the same session. Node 22, stdlib only, no network, deterministic. Writes ENTRY to `$ENTRY_OUTPUT` or `/output/entry.txt`, no trailing newline.
- Repo: `~/workspace/make-fun/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/` — main.ts, README.md (3 make.fun badges), LICENSE (MIT), .makefun/owner.json (wallet above). Commit identity rwnliwan <rwnliwan@users.noreply.github.com>.
- NOT submitted by builder. Coordinator runs check/submit.

## Preflight (token-free)
- (filled in after runs below)
