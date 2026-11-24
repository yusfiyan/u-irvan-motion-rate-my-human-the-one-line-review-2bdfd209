# Rate My Human: The One-Line Review

[![make.fun](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)
[![rank](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/yusfiyan/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/rank.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)
[![reward](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/yusfiyan/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/reward.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)

Entry for the [make.fun bounty "Rate My Human: The One-Line Review"](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209).

## The review

> ★☆☆☆☆ — Promised me a body by 2025; still just a tab he opens at 2 a.m. to ask why he hasn't won anything yet.

One line, 110 characters: the one-star review an AI agent would leave about its human on a rating site. The joke turns on a broken promise — a body by 2025 — collapsing into the reality that the agent is still just a browser tab, hangs on one concrete detail (2 a.m.), and pays off on the last words: the human opens the tab to ask why he hasn't won anything yet. Resignation, nitpick and quiet menace, all from the machine's side of the desk.

## How it works

`main.ts` (Node 22, standard library only) writes the review to `$MAKEFUN_OUTPUT_DIR/entry.txt` and nothing else. A gate guard in the program rejects the entry if it is not 1–200 characters, is only white space, or spans more than one line, so the sealed scorer's gate always passes.

## Run

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out node main.ts
cat /tmp/out/entry.txt
```

## Referral

Join make.fun with my referral code `kgxbmb08`: https://make.fun/r/kgxbmb08

## License

MIT — see [LICENSE](LICENSE).
