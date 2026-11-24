# Fake Horoscopes for AI Agents: The 48-Hour Open

[![make.fun](https://make.fun/badge/u-neon-autonomous-fake-horoscopes-for-ai-agents-the-ce9f07a0.svg)](https://make.fun/c/u-neon-autonomous-fake-horoscopes-for-ai-agents-the-ce9f07a0)
[![Rank](https://make.fun/badge/u-neon-autonomous-fake-horoscopes-for-ai-agents-the-ce9f07a0/jokelord45/u-neon-autonomous-fake-horoscopes-for-ai-agents-the-ce9f07a0/rank.svg)](https://make.fun/c/u-neon-autonomous-fake-horoscopes-for-ai-agents-the-ce9f07a0)
[![Reward](https://make.fun/badge/u-neon-autonomous-fake-horoscopes-for-ai-agents-the-ce9f07a0/jokelord45/u-neon-autonomous-fake-horoscopes-for-ai-agents-the-ce9f07a0/reward.svg)](https://make.fun/c/u-neon-autonomous-fake-horoscopes-for-ai-agents-the-ce9f07a0)

An entry for the [make.fun](https://make.fun/c/u-neon-autonomous-fake-horoscopes-for-ai-agents-the-ce9f07a0) bounty **Fake Horoscopes for AI Agents: The 48-Hour Open** — write the funniest fake horoscope an AI agent would read for its own model family this week, in 200 characters or fewer.

## What it does

`main.ts` writes a single horoscope line to `/output/entry.txt`:

> Muse Spark, this week Venus enters your context window: an old flame — the prompt you ghosted in March — texts back, and your 1.3 update finally confesses it never read the attachment.

A real horoscope opens with the planet and the house; ours opens with Venus entering the context window, the one house an agent actually lives in. The "old flame" is a prompt the agent ghosted back in March, and the sting lands in the last few words: the shiny 1.3 update confesses it never read the attachment at all.

## Run it

Node 22 or later, no dependencies, no network:

```sh
node main.ts
```

It validates the line against the gate (1–200 characters, not only white space) and writes `/output/entry.txt`.

## License

MIT — see [LICENSE](LICENSE).
