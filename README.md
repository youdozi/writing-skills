# Writing Skills

**English** | [한국어](README.ko.md)

Eight AI agent skills for writing, editing, and translation. Korean is the default language; you can request another language, audience, or genre.

## Included skills

| Skill | Purpose |
| --- | --- |
| [writing](skills/writing/SKILL.md) | General-interest explanations, current affairs, community posts, everyday writing, fiction, and client communication |
| [tech-blog-writing](skills/tech-blog-writing/SKILL.md) | Technical explanations, tutorials, troubleshooting, comparisons, and retrospectives |
| [translate](skills/translate/SKILL.md) | Translation, localization, and translation review while preserving meaning |
| [website-copywriting](skills/website-copywriting/SKILL.md) | Websites, landing pages, service descriptions, and FAQs |
| [cms-ux-writing](skills/cms-ux-writing/SKILL.md) | Admin interface buttons, help text, errors, and workflow status messages |
| [marketing-pr-writing](skills/marketing-pr-writing/SKILL.md) | Campaigns, ads, social posts, press releases, and public statements |
| [ai-guide-writing](skills/ai-guide-writing/SKILL.md) | AI tool instructions, prompts, and workflow guides |
| [screenplay-writing](skills/screenplay-writing/SKILL.md) | Film, television, and short-form screenplays, scenes, and dialogue |

The skill instructions are currently written primarily in Korean. This English README explains how to use them; it is not a full English translation of the skill files.

Start with each folder's `SKILL.md`. Read the relevant material in `references/` when needed. You do not need to load every reference or use a long template for every task.

## Install and use

1. Download or clone this repository.
2. Copy the `skills/<name>` folders you need into your agent's skills directory. If a folder with the same name already exists, compare and back it up before replacing it.
3. Start a new session, check that the skills are available, and make your request.

For Codex, a user-level installation example is `~/.agents/skills/writing/SKILL.md`. Paths and invocation syntax vary by host, so check your environment's installation instructions. See the [official OpenAI documentation](https://learn.chatgpt.com/docs/build-skills) for Codex skill installation and invocation.

Example requests:

```text
$writing Write a fictional slice-of-life scene in Korean, around 200 characters, set in a convenience store on a rainy evening. Use a plain, understated tone.

$tech-blog-writing Turn this error reproduction record into a technical blog post. Distinguish confirmed causes from hypotheses, and briefly explain the fix and how it was verified.

$translate Translate this notice naturally into Japanese. Preserve the numbers, conditions, and {version}.

$website-copywriting Using only the supplied service facts, write a headline, description, and inquiry button label for the first screen.
```

## Writing principles

- Distinguish factual material from fiction. Do not invent experiences, figures, or sources.
- Preserve the reader's purpose and the writer's voice while reducing repetition and stock phrasing.
- Preserve meaning, conditions, and identifiers in translation while adapting expression to the reader's language and cultural context.
- Review what the task requires, and distinguish verified evidence from unresolved points.

These skills are instructions for an agent. They do not guarantee writing quality or factual accuracy for any model, language, audience, or subject. Review the output before publishing. Access to external sources depends on the tools and permissions available in your environment.

## Updates

The public files are maintained through a selective synchronization process. Changes to the skills and these instructions are published from their maintained source, so edits made directly in this repository may be overwritten by a later sync.

## License

[MIT License](LICENSE). External documents and articles linked from the skill files remain subject to their respective rights; this project's license does not relicense them.
