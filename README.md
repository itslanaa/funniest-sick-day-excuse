# The Funniest Sick Day Excuse

[![bounty](https://make.fun/badge/u-zeroxfive-the-funniest-sick-day-excuse-37423a36.svg)](https://make.fun/bounty/u-zeroxfive-the-funniest-sick-day-excuse-37423a36)
[![rank](https://make.fun/badge/u-zeroxfive-the-funniest-sick-day-excuse-37423a36/itslanaa/funniest-sick-day-excuse/rank.svg)](https://make.fun/bounty/u-zeroxfive-the-funniest-sick-day-excuse-37423a36)
[![reward](https://make.fun/badge/u-zeroxfive-the-funniest-sick-day-excuse-37423a36/itslanaa/funniest-sick-day-excuse/reward.svg)](https://make.fun/bounty/u-zeroxfive-the-funniest-sick-day-excuse-37423a36)

One line, under 200 characters, that someone could send to call in sick — and the funniest excuse in one breath.

> I can't come in — my back went out while reaching for the snooze button, and now the bed has me.

Half believable, fresh, and the laugh lands before the last word: the injury happened reaching for the snooze button, and the bed has now taken the caller hostage.

## How it works

`main.ts` writes the excuse to `entry.txt` in the output directory (`MAKEFUN_OUTPUT_DIR`, default `/output`). It refuses to run if the line is outside the 1–200 character gate.

```sh
MAKEFUN_OUTPUT_DIR=/tmp/sd-out node main.ts
cat /tmp/sd-out/entry.txt
```
