# Project Context: The Anubis Protocol (Quartz 4 + Obsidian)

## Core Tech Stack
- **Framework:** Quartz 4 (built on Hugo/Go/TypeScript).
- **Content Source:** Obsidian Vault (Markdown files in the `/content` folder).
- **Deployment:** GitHub Pages.

## Coding & Content Rules
- **Obsidian Compatibility:** Never change the internal wikilink style `[[link]]`. 
- **Frontmatter:** Every new post must have a YAML frontmatter with `title`, `description`, and `date`.
- **Quartz Config:** Any changes to the site's "vibe" (colors, fonts) must be done in `quartz.config.ts`.
- **Refactoring:** If I ask to move files, ensure the `index.md` files remain in their respective folders to prevent 404 errors in Quartz.

## Personal Preferences
- **Alias:** Use **JackalNull** in file headers or code comments.
- **Tone:** Keep the blog technical but accessible (Sufism and Cybersecurity focus).
- **Language:** Stick to clean TypeScript for any Quartz component modifications.

## Terminal Commands
- Use `npx quartz build` to preview changes.
- Use `npx quartz sync` to push to GitHub.