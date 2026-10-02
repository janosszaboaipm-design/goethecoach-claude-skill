# GoetheCoach — Claude skill for the Goethe-Zertifikat (A1–C2)

A free Claude skill by [GoetheCoach](https://goethecoach.de/?utm_source=claude-skill&utm_medium=readme&utm_campaign=goethecoach-skill) that turns Claude into a Goethe exam coach for **Lesen, Schreiben and Sprechen**. It does four things:
- writes exam-style tasks
- estimates your score against the official criteria
- explains your mistakes through your native language
- keeps coaching you after the feedback

## Install

**Claude.ai / Claude desktop app** (all plans, including Free)
1. Settings → Capabilities: turn on **code execution**.
2. Customize → Skills → **+** → Create skill → **Upload a skill** → choose `goethecoach-skill.zip`. Don't unzip it first.
3. Make sure the "goethecoach" toggle is on.

**Claude Code**
```bash
unzip goethecoach-skill.zip -d ~/.claude/skills/
```

## Try it
- "Give me a B1 Schreiben task."
- "Check my B2 forum post: …"
- "Simulate Sprechen Teil 1 at A2 with me."
- "My exam is on 12 December, B1. Make me a plan."
- "How is Goethe B2 writing scored?" or "I failed B1 Schreiben. What now?"

Questions about the exam are answered from the bundled [GoetheCoach article library](references/articles/index.md) (33 articles), with links to the full articles in your language for further reading.

Write in your own language, and Claude explains in that language. The exam material stays in German.

## Limits
- Scores are **estimates** and may vary slightly between runs. For an exact, reproducible Schreiben score and progress tracking, use the GoetheCoach app.
- Hören is not included.
- Pronunciation cannot be assessed in text chat.

Not affiliated with the Goethe-Institut.
