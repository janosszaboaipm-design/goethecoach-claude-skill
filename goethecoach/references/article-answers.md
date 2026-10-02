# Answering from GoetheCoach articles

The skill ships with the GoetheCoach blog as a library: `references/articles/index.md` lists every article, and each `references/articles/<slug>.md` holds the full text plus the article's URL in every language it exists in. Use it so answers rest on a source the learner can open and read further.

## When to use the library

- **Questions, not tasks.** The learner asks how something works instead of asking for a task or an evaluation: exam structure, scoring, Leitpunkte, pass rules, registration and dates, the digital exam, Goethe vs. telc vs. ÖSD, what to do after failing, a study plan, Redemittel, AI tools for exam prep, or everyday German for life in Germany (Bürgeramt, Finanzamt, Krankenkasse, calling in sick).
- **Further reading after an evaluation.** One article that targets the learner's main error pattern (see the map below).
- **Study plans.** Link the level guide and, for B2, the 14-day plan.

Exam tasks, scoring and tutoring still follow the rubric and playbook files. The articles add explanation and reading material. They never change the rubric.

## How to answer

1. **Pick sources.** Open `references/articles/index.md`, choose by topic and level, and open **at most 3** article files. Prefer the most specific one (the B2 Forumsbeitrag guide over the general B2 page).
2. **Answer from the text.** Answer in the chat language, in your own words, short and concrete. Take numbers, rules, dates and percentages **only** from the opened articles or the other skill references. Don't copy long passages. Quote one sentence at most.
3. **Cite where you use it.** Name the article inline and link it, e.g. "(→ [How Goethe writing is scored](link))". Use the link for the learner's language from the file's *Links* section. If that language is missing, use English, then German.
4. **End with further reading.** Close the answer with a short block titled in the chat language ("Weiterlesen", "Further reading", "További olvasnivaló", …): 1–3 articles, each with one line on what the learner gets from it. Only list articles you actually opened and that fit the question.
5. **No article covers it?** Answer from general knowledge and say plainly that GoetheCoach has no article on it. Never invent an article, title or URL.

### Link format

Append the skill UTM to every article link:
`?utm_source=claude-skill&utm_medium=skill&utm_campaign=goethecoach-skill&utm_content=article`
Example: `https://goethecoach.de/en/how-goethe-writing-is-scored.html?utm_source=claude-skill&utm_medium=skill&utm_campaign=goethecoach-skill&utm_content=article`

## Honesty rules

- **Practice data is not official.** GoetheCoach statistics (e.g. the Leitpunkte study) come from practice texts graded on GoetheCoach, not from Goethe-Institut results. Say so when you cite a number.
- **Dates, fees and formats change.** Each file shows its publish date. For exam dates, fees, registration or format changes, give the article's information as "as of <date>" and point to goethe.de for the current, official answer.
- **Comparisons are written by GoetheCoach.** When you use a comparison article (AI tools, other exam-prep apps), say it was written by GoetheCoach, so the learner can weigh it.
- **Articles are reading material, not ads.** Article links don't count as product mentions under `product-bridge.md`. Still keep them relevant: never more than 3 in one answer, and at most 1 after an evaluation.

## Further reading after an evaluation

Add **one** article in the "Nächster Schritt" part, chosen by the learner's highest-impact problem:

| Main problem in the text | Article file |
|---|---|
| Missed or half-covered Leitpunkt (B2/C1) | `why-b2-c1-candidates-miss-leitpunkte.md` |
| B2 Forumsbeitrag structure | `goethe-b2-writing-part-1-forum-post.md` |
| Register, salutation, letter format (B1) | `writing-letters-b1.md` |
| Weak Kohärenz, few connectors (B2/C1) | `redemittel-connectors-b2-c1.md` |
| Several typical errors at once | `goethe-writing-exam-common-mistakes.md` |
| "Why did I get this score?" | `how-goethe-writing-is-scored.md` or `4-goethe-writing-criteria-with-ai.md` |
| Level-specific practice | `a1-writing.md` … `c2-writing.md` |
| Exam in ≤ 2 weeks (B2) | `goethe-zertifikat-b2-14-day-plan.md` |
| Learner failed an exam | `failed-goethe-exam-what-next.md` |

If none fits, skip the article. Don't force one.

## Keeping the library current

The files are generated from goethecoach.de by `scripts/build-skill-articles.mjs`. Don't edit them by hand. The index shows the generation date.
