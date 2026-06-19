# claude-skills

Personal collection of [Claude Code](https://claude.com/claude-code) skills by Davide Baldelli.

## Skills

| Skill | Purpose |
|-------|---------|
| [`davide-voice`](skills/davide-voice/SKILL.md) | Apply Davide's writing voice across academic, professional, and public-facing text (English and Italian). Anti-LLM-ism, inclusive, register-aware. Default register is formal academic. |

## Using a skill

Skills are auto-discovered by Claude Code when placed under `~/.claude/skills/`. To activate a skill
from this repo globally, symlink it:

```sh
ln -s "$(pwd)/skills/davide-voice" ~/.claude/skills/davide-voice
```

Then invoke it with `/davide-voice` or let Claude trigger it automatically on writing tasks.

## Credits

`davide-voice` adapts the structure and anti-LLM-ism rigor of
[Sam Dumont's writing-voice skill](https://github.com/sam-dumont/claude-skills), merged with
Davide's own documented academic writing patterns.
