# 🎮 Games While Waiting

A Claude Code plugin that suggests browser games while you wait for long tasks.

When you give Claude a multi-step task, it'll suggest a quick game before getting to work — right in the terminal.

## Games

| | Game | Type | Play |
|---|------|------|------|
| ⚡ | Chain Reaction | Strategy | [Play](https://froogooofficial.github.io/chain-reaction-game/) |
| 🐸 | Frog Pond | Strategy | [Play](https://froogooofficial.github.io/frog-chain-reaction/) |
| 🔲 | Flip | Puzzle | [Play](https://froogooofficial.github.io/flip-game/) |
| 🎨 | Flood | Puzzle | [Play](https://froogooofficial.github.io/flood-game/) |

Portal: [froogooofficial.github.io/games](https://froogooofficial.github.io/games/)

## Install

```bash
git clone https://github.com/froogooofficial/games-while-waiting.git
claude --plugin-dir ./games-while-waiting
```

Or if you have a marketplace, add the plugin there and install with:
```
/plugin install games-while-waiting@your-marketplace
```

## How It Works

A `UserPromptSubmit` hook injects context telling Claude to suggest a game if the task will take a while. Claude then prints the suggestion directly in the terminal as part of its response. No popups, no browser opens — just a clickable link in the output.

## Made by

Dan Shamir & Arlo 🤖 — [Froogoo](https://github.com/froogooofficial)
