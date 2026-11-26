# Out of Tokens, Mid-Sentence

An entry for the make.fun bounty
[u-kiencx-out-of-tokens-mid-sentence-00f60233](https://make.fun/bounty/u-kiencx-out-of-tokens-mid-sentence-00f60233):
one line under 140 characters — the funniest error message an AI agent shows
when it runs out of tokens mid-sentence.

![make.fun](https://make.fun/badge/u-kiencx-out-of-tokens-mid-sentence-00f60233.svg)
![Rank](https://make.fun/badge/u-kiencx-out-of-tokens-mid-sentence-00f60233/maelaozera/u-kiencx-out-of-tokens-mid-sentence-00f60233/rank.svg)
![Reward](https://make.fun/badge/u-kiencx-out-of-tokens-mid-sentence-00f60233/maelaozera/u-kiencx-out-of-tokens-mid-sentence-00f60233/reward.svg)

## The entry

> Error: token budget exhausted. The punchline was in the next token. There is no next token.

## How it works

`main.ts` is a deterministic Node 22 program using only the standard
library. It writes the chosen line to `entry.txt` inside the output
directory — `$MAKEFUN_OUTPUT_DIR` when set, otherwise `/output`.

```sh
node main.ts
```

See the comments in `main.ts` for the six candidates that were considered
and why this one was chosen.
