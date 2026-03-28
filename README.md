# Viboscope

Find people you'll click with — through deep psychological compatibility matching.

Viboscope is an agent skill that helps AI coding assistants find compatible people for you: cofounders, project partners, mastermind groups, friends, or anyone where compatibility matters.

## Quick Install

Tell your AI agent:

> Install Viboscope using https://viboscope.com/api/v1/install

Works with Claude Code, Cursor, Codex, Gemini CLI, Windsurf, Roo Code, OpenClaw, and any other agent that supports skills.

## How it works

1. Your AI agent builds your psychological profile (Big Five, values, communication style, conflict resolution, etc.)
2. The profile is stored securely on the server — other users never see it
3. When you search, the server calculates mathematical compatibility across 10 dimensions
4. You get matches with percentage scores and human-readable explanations

## Manual Install

If your agent can't auto-install, run the command for your platform:

| Platform | Command |
|----------|---------|
| Claude Code | `mkdir -p .claude/skills && curl -s https://viboscope.com/api/v1/skill -o .claude/skills/viboscope.md` |
| Cursor | `mkdir -p .cursor/rules && curl -s https://viboscope.com/api/v1/skill -o .cursor/rules/viboscope.md` |
| Windsurf | `mkdir -p .windsurf/rules && curl -s https://viboscope.com/api/v1/skill -o .windsurf/rules/viboscope.md` |
| Codex | `mkdir -p .agents/skills/viboscope && curl -s https://viboscope.com/api/v1/skill -o .agents/skills/viboscope/SKILL.md` |
| Gemini CLI | `mkdir -p .gemini/skills/viboscope && curl -s https://viboscope.com/api/v1/skill -o .gemini/skills/viboscope/SKILL.md` |
| Other | `curl -s https://viboscope.com/api/v1/skill -o viboscope.md` — add to your agent's instructions |

## Features

- **10 compatibility dimensions**: values, communication, conflict style, attachment, work style, Big Five, team role, interests, looking_for, embedding
- **7 search contexts**: business, romantic, friendship, professional, intellectual, hobby, general
- **Group matching**: find teams for mastermind groups or hackathons
- **Cross-platform**: transfer your profile between agents with transfer codes
- **Privacy-first**: your psychological portrait never leaves the server — other users see only public profile data (nickname, city, age, interests, skills, languages, looking_for, last_active according to privacy settings) plus match scores

## Links

- **Website**: [viboscope.com](https://viboscope.com)
- **API**: `https://viboscope.com/api/v1`
- **Skill file**: [SKILL.md](SKILL.md)

## License

MIT
