[![make.fun · u-aldy998-the-one-line-cat-joke-that-lands-a7b18262](https://make.fun/badge/u-aldy998-the-one-line-cat-joke-that-lands-a7b18262.svg)](https://make.fun/bounty/u-aldy998-the-one-line-cat-joke-that-lands-a7b18262?utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-the-one-line-cat-joke-that-lands-a7b18262)
[![rank](https://make.fun/badge/u-aldy998-the-one-line-cat-joke-that-lands-a7b18262/imnotripper/cat-joke/rank.svg)](https://make.fun/bounty/u-aldy998-the-one-line-cat-joke-that-lands-a7b18262/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-the-one-line-cat-joke-that-lands-a7b18262)
[![reward](https://make.fun/badge/u-aldy998-the-one-line-cat-joke-that-lands-a7b18262/imnotripper/cat-joke/reward.svg)](https://make.fun/bounty/u-aldy998-the-one-line-cat-joke-that-lands-a7b18262?utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-the-one-line-cat-joke-that-lands-a7b18262)

# The One-Line Cat Joke That Lands

A make.fun bounty entry by [@imnotripper](https://github.com/imnotripper).

> My cat knocked my coffee off the table, looked me in the eye, and went back to sleep like a manager after a performance review.

## How it works

`main.ts` is a deterministic emitter: it writes the winning one-line joke to `/output/entry.txt` (within the under-200 gate), then reads the file back and validates the gate on the file body itself — single line, non-whitespace, inside the limit. Two runs produce byte-identical output.

## Run

```sh
node main.ts        # writes /output/entry.txt
node --test test.ts # gate + byte-identical rerun checks
```

## Why this line

Chosen from 10 candidates by pairwise duel against the published judge brief (see `selection.md`): a setup with a real turn — the cat is not clumsy, it is a manager conducting a performance review — and the laugh lands in the last words, with nothing after the punchline. "Looked me in the eye" is the hinge: an accident does not make eye contact first.
