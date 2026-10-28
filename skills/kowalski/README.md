# Kowalski

A quality check that reviews a target, applies fixes within scope, and reports suggestions and remaining issues. Named after the penguin Kowalski.

## Install

In Codex, ask:

```text
Use $skill-installer to install https://github.com/mszlapa/agentic/tree/main/skills/kowalski
```

Or copy this folder into your agent’s skills directory. For Codex, use `~/.agents/skills/kowalski/` for personal use or `.agents/skills/kowalski/` in a repository.

## Use

```text
$kowalski review the changes from this session
```

Run it in the session that produced the work. It checks necessity, practicality, safety, completeness, effort, simplicity, discoverability, reuse, and preservation. It runs up to three fix rounds and does not commit.

The canonical skill name is `kowalski`. The description also mentions the former spelling `kowalsky` for recognition. This does not register a second command.

See [SKILL.md](SKILL.md) for the complete workflow.
