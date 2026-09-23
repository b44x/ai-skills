# CLAUDE.md

Repository of AI skills. Full rules: `CONTRIBUTING.md`.

- Each skill: `skills/<name>/SKILL.md` with `name` + `description` frontmatter; `name` == directory name (kebab-case).
- Start new skills from a copy of `skills/_template/`.
- After changes run `python3 scripts/validate_skills.py`.
- Branches: work on `skill/<name>`, `update/<name>`, `fix/…`, `docs/…`, `chore/…` from `dev` → PR to `dev`; `dev` → `main` only for releases. No `claude/…` or personal prefixes.
- Commits: Conventional Commits, scope = skill name.
- Repo docs in English; never commit secrets or tokens.
