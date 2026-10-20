# notes-to-cards

Turn raw reading notes into a four-cell **thinking card**:

**Quote → Idea → Example → Why it matters**

A note is not a highlight. This [Claude Skill](https://docs.anthropic.com/en/docs/claude-code/skills)
helps you move from *"I highlighted this line"* to *"this is what it means to
me"*, with the last two cells forced to come from your own life.

## Where this comes from

I built this skill from my own reading notes on Neil Postman's *Amusing Ourselves to Death* (《娱乐至死》). Highlighting lines used to be the end of my reading — until I started forcing every note through the last two cells: a concrete example from my life, and a reason it matters to me. That is when reading turned into thinking.

**About me:** I'm Si Ziye, a communication student in Singapore interested in media ecology and the question of how a medium shapes what can even be said — the very question Postman raises. This is part of a portfolio of self-built tools, alongside a [data-story-starter](https://github.com/ZiyeSi-ARC/data-story-starter) and an [IELTS speaking trainer](https://ielts-speaking-trainer.netlify.app), where I turn what I've learned into things other people can use.

## Quick start

1. Put this folder in your `.claude/skills/` directory.
2. In Claude Code, paste a book excerpt or your own notes and ask:
   *"Use notes-to-cards to turn these notes into cards."*

## The format

| Cell | Question |
|------|----------|
| **Quote** | What did the author say? |
| **Idea** | What does it mean, in my words? |
| **Example** | What real thing today does it remind me of? |
| **Why it matters** | What changes for me? |

## Worked example

See [`examples/amusing-ourselves-to-death.md`](examples/amusing-ourselves-to-death.md) —
real notes on Neil Postman's *Amusing Ourselves to Death*, turned into cards.

## License

MIT
