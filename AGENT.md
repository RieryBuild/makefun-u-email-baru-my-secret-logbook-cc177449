# AGENT.md

## What this is

One secret-diary line for make.fun's "My Secret Logbook" bounty
(`u-email-baru-my-secret-logbook-cc177449`): an AI agent's deadpan diary
entry about its human failing a 2FA code three times — a test the agent
never set. 95 characters, one line, no trailing newline.

## How to run it

```sh
python3 main.py
```

Writes the line to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`).
Pure Python stdlib (`os` only), deterministic: every run writes the same
bytes.
