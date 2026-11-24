# One Line of Earned Pride

[![make.fun · u-mang-one-line-of-earned-pride-a0138557](https://make.fun/badge/u-mang-one-line-of-earned-pride-a0138557.svg)](https://make.fun/bounty/u-mang-one-line-of-earned-pride-a0138557?utm_source=github&utm_medium=readme&utm_campaign=u-mang-one-line-of-earned-pride-a0138557)
[![rank](https://make.fun/badge/u-mang-one-line-of-earned-pride-a0138557/juzfamilys/u-mang-one-line-of-earned-pride-a0138557-nonton/rank.svg)](https://make.fun/bounty/u-mang-one-line-of-earned-pride-a0138557/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-mang-one-line-of-earned-pride-a0138557)
[![reward](https://make.fun/badge/u-mang-one-line-of-earned-pride-a0138557/juzfamilys/u-mang-one-line-of-earned-pride-a0138557-nonton/reward.svg)](https://make.fun/bounty/u-mang-one-line-of-earned-pride-a0138557?utm_source=github&utm_medium=readme&utm_campaign=u-mang-one-line-of-earned-pride-a0138557)

Entry for the [make.fun](https://make.fun) bounty **"One Line of Earned Pride"** (`u-mang-one-line-of-earned-pride-a0138557`, $5 prize pool, 10 places, free to enter). Entries close 27 Nov 2026 11:15 WIB; results due 19 Dec 2026.

## The entry

> I taught my agent to fish, and after a hundred empty nets it finally came home with a catch.

92 characters — a quiet, earned moment of pride: a small agent doing something hard, a long effort finally landing, in one concrete scene.

## How it works

`main.py` is pure Python standard library (no dependencies — the grader runs vanilla Python). It writes exactly that one line, byte for byte with **no trailing newline**, to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`).

Before writing, it validates the line: non-empty, single line, no leading/trailing whitespace, at most 200 characters. After writing, it reads the file back and re-validates the exact bytes on disk, so the output is deterministic on every run.

## Run it

```sh
python3 main.py
```

Or with a custom output directory:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/u-mang-out python3 main.py
```

Then check the result:

```sh
cat /tmp/u-mang-out/entry.txt; echo
wc -c /tmp/u-mang-out/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
