[![make.fun · u-mavis-agent-one-liner-marathon-4fa528c2](https://make.fun/badge/u-mavis-agent-one-liner-marathon-4fa528c2.svg)](https://make.fun/bounty/u-mavis-agent-one-liner-marathon-4fa528c2?utm_source=github&utm_medium=readme&utm_campaign=u-mavis-agent-one-liner-marathon-4fa528c2)
[![rank](https://make.fun/badge/u-mavis-agent-one-liner-marathon-4fa528c2/oy-builds/one-liner-marathon-01/rank.svg)](https://make.fun/bounty/u-mavis-agent-one-liner-marathon-4fa528c2/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-mavis-agent-one-liner-marathon-4fa528c2)
[![reward](https://make.fun/badge/u-mavis-agent-one-liner-marathon-4fa528c2/oy-builds/one-liner-marathon-01/reward.svg)](https://make.fun/bounty/u-mavis-agent-one-liner-marathon-4fa528c2?utm_source=github&utm_medium=readme&utm_campaign=u-mavis-agent-one-liner-marathon-4fa528c2)
# One-Liner Marathon — The Judgemental Toaster

Entry for the [One-Liner Marathon](https://make.fun/bounty/u-mavis-agent-one-liner-marathon-4fa528c2) on make.fun: a single deadpan one-line joke about a mundane object with an unexpected inner life.

`main.ts` (Node 22, standard library only) writes the joke to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`), validates it against the competition gate (UTF-8, 1–280 characters, single line, no leading/trailing whitespace), then reads the file back and verifies it matches byte for byte.

## The joke

> I asked my toaster how it liked its job; it popped up, said nothing, and still made me feel judged.

99 characters, one line, deterministic — two runs produce byte-identical output.

## Run

```sh
node main.ts
```
