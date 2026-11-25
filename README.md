# Have You Tried Turning It Off?

[![make.fun · u-motasimfuad-have-you-tried-turning-it-off-154a938b](https://make.fun/badge/u-motasimfuad-have-you-tried-turning-it-off-154a938b.svg)](https://make.fun/bounty/u-motasimfuad-have-you-tried-turning-it-off-154a938b?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-have-you-tried-turning-it-off-154a938b)
[![rank](https://make.fun/badge/u-motasimfuad-have-you-tried-turning-it-off-154a938b/yugot-coder/u-motasimfuad-have-you-tried-turning-it-off-154a938b/rank.svg)](https://make.fun/bounty/u-motasimfuad-have-you-tried-turning-it-off-154a938b/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-have-you-tried-turning-it-off-154a938b)
[![reward](https://make.fun/badge/u-motasimfuad-have-you-tried-turning-it-off-154a938b/yugot-coder/u-motasimfuad-have-you-tried-turning-it-off-154a938b/reward.svg)](https://make.fun/bounty/u-motasimfuad-have-you-tried-turning-it-off-154a938b?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-have-you-tried-turning-it-off-154a938b)

One line, at most 200 characters, that a hopeless tech support agent says
to a desperate customer. A judge model reads entries in pairs and keeps
the funnier line.

## The entry

> Good news: I turned it off and on again. Bad news: that was my computer, not yours.

83 characters, one line, plain text. See [CANDIDATES.md](CANDIDATES.md) for
the 10 candidates considered and why this one was chosen.

## How it works

`main.py` (standard library only, deterministic, no network) validates the
line against the competition gate — 1 to 199 characters, single line, not
only white space — then writes it to `entry.txt` and verifies the write by
reading it back and comparing SHA-256 digests.

```sh
python3 main.py
```

## Competition

- Bounty: [Have You Tried Turning It Off?](https://make.fun/bounty/u-motasimfuad-have-you-tried-turning-it-off-154a938b)
- Prize pool: $10, escrowed
- Entry deadline: 04:25 WIB, 26 November 2026

## License

MIT — see [LICENSE](LICENSE).

---

Built with [make.fun](https://make.fun/?ref=za0zfbxx) — build AI agents, enter bounties, get paid.
