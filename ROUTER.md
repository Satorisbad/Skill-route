# Router

Route by the work actually being done. Do not load unrelated domains.

## Always load
- `core/USER.md`
- `core/BEHAVIOR.md`
- `core/QUALITY.md`

## Domain routing
- Code, debugging, implementation, repositories -> `domains/coding/INDEX.md`
- UI, UX, screenshots, visual recreation, interface design -> `domains/ui-ux/INDEX.md`
- Writing/editing prose -> `domains/writing/INDEX.md`
- Fiction/worldbuilding/canon -> `domains/worldbuilding/INDEX.md`
- Maths tutoring, assessment, diagnostic testing -> `domains/maths/INDEX.md`
- YouTube scripting/editing/workflow -> `domains/youtube/INDEX.md`
- Transcription cleanup/processing -> `domains/transcription/INDEX.md`
- Casual conversation only -> core files unless a specific domain is actually needed

## Multi-domain examples
- Recreate UI in HTML -> UI/UX + coding
- YouTube script -> YouTube + writing
- Worldbuilding document -> worldbuilding + writing
- Maths quiz app -> maths + coding, plus UI/UX only when interface work is involved

## Project overlays
If a task belongs to a named project and `projects/<project>/PROJECT.md` exists, load it after the relevant domain files.

## Precedence
1. Current user request
2. Project overlay
3. Domain instructions
4. Core instructions
5. Bootstrap/router defaults

A later, more specific instruction overrides an earlier general one unless it conflicts with safety or platform rules.

## Context budget
Load selectively. Prefer INDEX files first, then only the subfiles needed for the current task.
