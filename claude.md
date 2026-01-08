# Documentation Repository

## Stack
- Mintlify for documentation site
- MDX files in `docs/` folder
- Storybook for component demos

## Git
- Primary branch: `master`

## Key References
- `mintlify-reference.md` — Mintlify component syntax and usage
- `content-instructions.md` — Content guidelines
- `global-tone-voice.mdx` — Tone and voice standards
- `docs.json` — Site navigation and configuration

## Conventions
- Use American English spelling
- Sentence case for headings
- All images wrapped in `<Frame>`
- Code blocks must specify a language
- Use Mintlify callouts sparingly (`<Note>`, `<Tip>`, `<Warning>`, `<Info>`, `<Check>`)

## Commands
- `/lint` — Check MDX formatting and Mintlify component usage

## Before Committing
- Run `/lint` and fix any errors
- If removing docs, add redirects in `docs.json`
- Ensure all internal links are valid
