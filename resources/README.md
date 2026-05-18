# Resources

This directory contains a curated list of AI tools for educators, along with the prompts used to generate it.

## Files

### `resource_list.md`
A categorized markdown reference of AI teaching tools, each with a direct URL and a one-sentence description. Tools are grouped into five categories:

- **AI Slide & Presentation Generation** — Gamma, SlidesAI, Slidesgo AI, Plus AI
- **AI Lesson Plan Tools** — LessonPlans.ai, Canva, Kuraplan, Flint K12, Eduaide, Diffit, Khanmigo
- **AI Grading & Assessment** — Gradescope, Turnitin, Formative
- **AI Quiz & Worksheet Generators** — ClassPoint AI, Twee, Flint K12, Diffit
- **AI Bots & All-in-One Platforms** — MagicSchool AI, Brisk Teaching, Khanmigo, Juji, LiveChat AI

### `instructions.txt`
The prompt(s) fed to the Claude Code CLI to research and produce `resource_list.md`. Run via:

```sh
claude instructions.txt
```

The file also documents how the initial prompt was refined — the first pass returned blog posts and review sites rather than actual product pages, so a follow-up instruction was added to filter those out and surface only real tools.

