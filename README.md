# Content Craft Skills (for Claude Code and Codex)

Nine installable agent skills for content work, sales messaging, and learning design, in the Agent Skills format that both Claude Code and Codex load. Each skill is a folder with a `SKILL.md` (YAML frontmatter with `name` and `description`, then the instructions), plus optional `references/` files.

Proposed repo name: `content-craft-skills` (open to change).

## The skills

| Skill | What it does |
|---|---|
| `storytelling-hooks` | Hook and short-form story craft from named public frameworks (Stanton, Dicks, Vonnegut, Kenn Adams, Made to Stick), with testable opening patterns and a pre-publish checklist. |
| `captions-cta` | Caption anatomy (second hook, value block, one CTA), CTA selection by post goal, review checklist. |
| `creator-analysis` | A dated-evidence method for studying creators and extracting structure - observed facts kept separate from your inferences, all claims attributed. |
| `ai-tools-news-radar` | Verification-first coverage of AI tools and news: tiered sources, a five-axis "free" audit, scoring before publication. |
| `github-student-growth` | A five-axis-audited list of free GitHub repos for students (coding, AI, portfolio), with reuse-limit notes. |
| `agency-brand-content` | Content standard for a small studio's own social presence selling to brand buyers: proof, teaching, honesty rules, formats. |
| `sales-message-playbook` | Short sales messages (cold outreach, follow-ups, objections, negotiation, onboarding) gated by a buyer-perspective review (pass band 8.5/10). |
| `learning-design` | Evidence-tagged learning science for courses, study content and product loops - what works, what is mixed, what is myth, plus an ethics line on dark patterns. |
| `prashant-youtube-thumbnail` | Generates 16:9 YouTube thumbnails in Prashant's style from 8 named layout patterns with fill-in prompts. Personal to him: it needs a real photo of his face per job. Reference images are NOT included (third-party study material); supply your own or use the text recipes in `references/patterns.md`. |

## Install: Claude Code

Verified against the Claude Code skills docs (https://code.claude.com/docs/en/skills):

- Personal (all projects): copy a skill folder into `~/.claude/skills/`, e.g. `~/.claude/skills/storytelling-hooks/SKILL.md`
- Per project: copy it into `<project>/.claude/skills/`
- Invoke explicitly with `/storytelling-hooks` (the folder name becomes the command), or let Claude load it automatically when your request matches the skill's description.

## Install: Codex

Verified against the OpenAI skills docs (https://learn.chatgpt.com/docs/build-skills):

- User level: copy a skill folder into `$HOME/.agents/skills/`
- Repo level: copy it into `.agents/skills/` anywhere from your working directory up to the repository root
- Invoke explicitly with `$storytelling-hooks` (or select it via `/skills`), or let Codex pick it up from the description. Optional `agents/openai.yaml` configures UI metadata and invocation policy; these skills need no extra config.

Example, both hosts: after installing, ask `Use storytelling-hooks to write 5 hooks for a carousel about spaced repetition` - the skill loads and applies its frameworks and checklist.

## Licensing

MIT License applies to the original text authored for this repository (see LICENSE). It does NOT extend to third-party material referenced inside the skills: cited books, papers, talks, framework names and linked repositories remain the property of their respective authors. Short attributed quotations (a sentence from a talk, a paper's finding, a prompt template) may appear inside the skills; all rights in them stay with the original authors. Repo audits in `github-student-growth` were verified live against the GitHub API on 6 November 2026 and are point-in-time; re-verify licenses and activity before relying on them.

## Personal details present in this package

- `prashant-youtube-thumbnail` names Prashant and requires a real supplied photo of his face per job (composited as a cutout, never generated) - it is his personal thumbnail skill by design. Keep or omit that folder when forking for general use.
- All other skills are generic: no names, handles, contact details, client data, or account references.
- No secrets, credentials, or private client material anywhere in this package.
