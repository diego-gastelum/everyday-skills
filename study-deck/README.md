# study-deck

A study system for things you want to keep. It turns what you read into cards by having you explain it first, then spaces your reviews so the hard ones come back more often. Built for Claude Code, because it saves your deck to a file on your computer.

[![Download study-deck](https://img.shields.io/badge/Download-study--deck-2ea44f?style=for-the-badge)](https://github.com/diego-gastelum/everyday-skills/raw/main/downloads/study-deck.zip)

## Install (Claude Code)

Unzip the download into `~/.claude/skills/`, or on a Mac paste this into your terminal:

```bash
curl -sL https://github.com/diego-gastelum/everyday-skills/raw/main/downloads/study-deck.zip -o /tmp/study-deck.zip && unzip -o /tmp/study-deck.zip -d ~/.claude/skills/
```

Then in Claude Code:
- **"Study this"** plus a link, pasted text, or a topic.
- **"Review my cards"** or `/study-deck` to go through everything that's due.
- **"Review sales"** (or any topic) to go through only that topic's cards.
- **"What topics do I have?"** to see each topic, its card count, and what's due.

Your cards are saved in `~/study/deck.md`, a plain file you can open and edit.

## Many articles, many topics

Study as many articles and topics as you like. They all go into one deck, and each card keeps its source and a topic. When you study something, it suggests a topic and reuses one you already have when it fits, so "sales" doesn't also turn up as "selling." You can rename it before the cards are saved.

A plain review mixes every topic, which helps memory. Name a topic when you want to focus, like before a meeting or a test.

## What it does

**Study.** You explain the piece in plain words. It grades that, asks three questions aimed at what you missed, then has you write a short version in your own words. That is the Feynman Technique: explaining something simply shows you where you don't understand it yet. Then it proposes cards for the gaps and the key ideas. You keep the ones you want.

**Review.** Cards sit in three boxes, the Leitner system:

| Box | Review |
|---|---|
| 1, hard | every 2 days |
| 2, medium | every 4 days |
| 3, easy | every 7 days |

Get a card right and it moves up a box. Get it wrong and it goes back to Box 1. Right in Box 3 and it's done. The cards you struggle with show up most.

Every answer is graded right, partly right, or wrong against a quote from the source. Miss one and you get a hint and a second try.

## How it differs from article-quiz

[article-quiz](../article-quiz/) is a one-time check on something you just read, and works anywhere in Claude, including the Chrome side panel. study-deck is for things you want to remember for months. It needs Claude Code because it keeps your deck between sessions.

## License

[CC BY 4.0](../LICENSE). Use and change it however you like. If you share it, credit Diego Gastelum.
