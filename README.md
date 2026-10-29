# Three Pac-Men (and Eight More) — Same Brief, Eleven Builds

**Read it live: https://marlandoj.github.io/three-pac-men/**

One Pac-Man brief, given word for word to three builders on 2026-10-22:

- **Muse-PacMan** — Muse Spark, writing directly in chat
- **grok-PacMan** — Grok, in a single generation
- **workshop-PacMan** — Claude Opus 5.5 through the Hermes harness, built as a Zouroboros Workshop factory task

The article embeds all three published games in a live, playable split screen and compares what the builders actually shipped — measured from the files: maze contents counted tile by tile, timing models and ghost AI read from the source, verification evidence weighed. Its conclusion: the models wrote the code, but the processes decided how much of it you should believe.

**Added 2026-10-29 — Exhibit B:** eight more builds of the same brief, all playable on the page and stored in this repo under `games/`, each byte-identical to what its builder delivered:

| Folder | Builder | Model |
| --- | --- | --- |
| [`games/pi-opus/`](games/pi-opus/) | Demo Workshop · Pi | anthropic/claude-opus-5.5 |
| [`games/hermes-muse-wonder/`](games/hermes-muse-wonder/) | Demo Workshop · Hermes | meta/muse-wonder |
| [`games/claude-code-opus/`](games/claude-code-opus/) | Zouroboros Workshop · Claude Code | claude-opus-5-5 |
| [`games/claude-code-fable/`](games/claude-code-fable/) | Zouroboros Workshop · Claude Code | claude-fable-5-1 |
| [`games/hermes-grok/`](games/hermes-grok/) | Zouroboros Workshop · Hermes | x-ai/grok-4.7 |
| [`games/hermes-kimi/`](games/hermes-kimi/) | Zouroboros Workshop · Hermes | moonshotai/kimi-k3.1-pro |
| [`games/codex-astra/`](games/codex-astra/) | Demo Workshop · Codex | gpt-6-astra |
| [`games/claude-direct/`](games/claude-direct/) | Claude, directly in chat | claude-opus-5-5 |

The essay's analysis still covers the original three; Exhibit B adds build time, cost, size and a short note for each of the eight.

The games:

- Play: [Muse-PacMan](https://marlandoj.github.io/Muse-PacMan/) · [grok-PacMan](https://marlandoj.github.io/grok-PacMan/) · [workshop-PacMan](https://marlandoj.github.io/workshop-PacMan/) · the eight above at `https://marlandoj.github.io/three-pac-men/games/<folder>/`
- Code: [Muse-PacMan](https://github.com/marlandoj/Muse-PacMan) · [grok-PacMan](https://github.com/marlandoj/grok-PacMan) · [workshop-PacMan](https://github.com/marlandoj/workshop-PacMan) · [`games/`](games/)
- The brief itself: [PROMPT.md](https://github.com/marlandoj/workshop-PacMan/blob/main/PROMPT.md) (identical in all three repos)

## License

MIT — see [LICENSE](LICENSE).
