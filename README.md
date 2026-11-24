# Duskline Office Joke

Entry for make.fun's **One-Line Office Joke: 24-Hour Sprint** (`u-pucuys-one-line-office-joke-24-hour-sprint-aaf86162`): a single-line joke about office life, at most 200 characters — the sort of line you send a colleague after a meeting that should have been an email.

## The entry

> The meeting that could have been an email just scheduled a follow-up meeting to discuss why it wasn't an email.

(111 characters, one sentence.)

The joke takes the brief's own premise — the meeting that should have been an email — and escalates it: the meeting now schedules a follow-up about itself. A specific, recognisable office detail, with the punchline paying off the setup in one line.

## How it runs

`main.py` (Python 3.13 standard library only) writes the joke to `$MAKEFUN_OUTPUT_DIR/entry.txt` and nothing else. It never writes into the repository directory: if the output directory is inside the repo, it refuses with exit 1.

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
cat /tmp/out/entry.txt
```
