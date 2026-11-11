# Generate a Daily Lesson

Use this prompt with a coding assistant while its working directory is this repository.

## Prompt

Create one new daily English lesson in this repository.

Before writing:

1. Read and follow `AGENTS.md`, especially the public-repository safety rule.
2. Read `study-plan.md`, `progress.md`, the phrasebook, and the seven most recent lessons.
3. Use only a fictional, generic workplace meeting scenario invented from scratch.
4. Do not read, reference, summarize, transform, or infer content from any other repository, work note, ticket, meeting, message, log, or real event.
5. If any proposed detail might identify a real company or event, replace it with a neutral fictional detail or omit it.

Create the lesson at:

```text
lessons/YYYY-MM/YYYY-MM-DD-<generic-topic>.md
```

The lesson must contain:

1. A title and one meeting skill.
2. A 100–150 word passage at approximately A2–B1 level.
3. Three to five reusable meeting phrases with Chinese explanations.
4. Four substitution exercises using generic information.
5. Four comprehension questions.
6. A one-minute retelling challenge.
7. Day 1, Day 2, Day 4, and Day 7 review checkboxes.

Learning balance:

- Reuse approximately 70% familiar language from recent lessons.
- Introduce approximately 30% new language.
- Prefer clear, short, reusable sentences over complex grammar.
- Rotate among status updates, clarification, planning, testing, generic deployment, troubleshooting, risks, discussion, and action items.
- Do not repeat the same primary topic on consecutive days.

After writing:

1. Confirm the passage is between 100 and 150 English words.
2. Check every local Markdown link.
3. Review the complete diff for direct or indirect company information.
4. Update `progress.md` with one new lesson row, leaving completion unchecked.
5. Report the new lesson path and its review dates.
