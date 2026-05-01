# Documentation project instructions

## About this project

- This is the documentation site for [Resonant](https://www.onresonant.com), a privacy-first voice workspace for macOS and Windows
- Built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Hosted at `onresonant.com/docs` via Vercel proxy to `resonant-d94fbefb.mintlify.dev`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use "Resonant" (capitalized), never "resonant" in prose
- Use "dictation" not "transcription" for voice-to-text input
- Use "meeting recording" not "meeting capture"
- Use "dispatch" for voice commands, not "voice control"
- Use "journal" for daily activity log
- Use "relay" for phone-as-microphone feature
- Use "voice workspace" not "voice assistant"

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Match brand voice: direct, confident, warm, concise
- Avoid: "revolutionary", "AI-powered", "seamless", "privacy-first", "user"

## Content boundaries

- Document user-facing features only — no internal architecture
- Privacy and local processing are key selling points — emphasize them
- MCP integration docs should cover setup for Claude Code, Cursor, and VS Code
- Do not document admin or internal tooling
