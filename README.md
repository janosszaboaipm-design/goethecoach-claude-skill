# GoetheCoach — free Claude skill for the Goethe-Zertifikat (A1–C2)

Turns [Claude](https://claude.ai) into a Goethe exam coach for **Lesen, Schreiben and Sprechen**:

- **Tasks:** exam-style tasks for every level and Teil
- **Evaluation:** scored against the four official criteria (Aufgabenerfüllung, Kohärenz, Wortschatz, Strukturen), shown as an honest estimate range
- **Tutoring:** self-correction, micro-drills, rewrite and re-score, with mistakes explained through your native language (Hungarian, Turkish, Ukrainian, Vietnamese, Arabic, Hindi, English, plus a general guide for others)
- **Study plan:** a week-by-week plan up to your exam date
- **Questions:** answers about the exam (format, scoring, Leitpunkte, dates, digital exam, Goethe vs. telc, failing) from the bundled GoetheCoach article library, with links to the full articles in your language for further reading

Full guide: [DE](https://goethecoach.de/goethe-pruefung-claude-skill.html?utm_source=github&utm_medium=readme&utm_campaign=goethecoach-skill) · [EN](https://goethecoach.de/en/goethe-exam-claude-skill.html?utm_source=github&utm_medium=readme&utm_campaign=goethecoach-skill)

## Install

1. Download `goethecoach-skill.zip` from the [latest release](../../releases/latest). Don't unzip it.
2. **Claude.ai / desktop app** (all plans, incl. Free):
   - Settings → Capabilities: turn on **code execution**.
   - Customize → Skills → **+** → Create skill → **Upload a skill**.
3. **Claude Code:** `unzip goethecoach-skill.zip -d ~/.claude/skills/`

Then ask, in your own language: *"Give me a B1 Schreiben task"*, *"Grade my B2 forum post: …"* or *"Simulate Sprechen Teil 1 at A2 with me."* You can also just ask: *"How is Goethe B2 writing scored?"*

## What's inside

```
goethecoach/
├── SKILL.md                   # entry point: modes, language + honesty rules
├── references/
│   ├── exam-formats.md        # A1–C2 Lesen / Schreiben / Sprechen
│   ├── rubric-schreiben.md    # 4 criteria, band scale, error-density cap
│   ├── rubric-sprechen.md     # speaking simulation + criteria
│   ├── lesen.md               # reading tasks + scoring
│   ├── tutoring-playbook.md   # feedback delivery + follow-up coaching
│   ├── study-plan.md
│   ├── product-bridge.md      # when the skill points to the GoetheCoach app
│   ├── article-answers.md     # answering from the article library, citing sources
│   ├── articles/              # 33 GoetheCoach articles (full text + URL per language)
│   └── l1/                    # native-language interference patterns
└── assets/calibration-examples.md
```

## Limits

- Scores are **estimates** and can vary slightly between runs. For an exact, reproducible writing score and progress tracking, use the [GoetheCoach app](https://goethecoach.de/?utm_source=github&utm_medium=readme&utm_campaign=goethecoach-skill).
- Hören is not included, because the chat has no audio.
- Pronunciation cannot be assessed in text chat.

Feedback and corrections, especially to the native-language pattern files, are welcome via issues or pull requests.

Not affiliated with the Goethe-Institut. MIT License.
