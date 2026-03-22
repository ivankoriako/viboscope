# Viboscope

Find people you'll click with — through deep psychological compatibility matching.

Viboscope is an agent skill that helps AI coding assistants find compatible people for you: cofounders, project partners, mastermind groups, friends, or anyone where compatibility matters.

## How it works

1. Your AI agent builds your psychological profile (Big Five, values, communication style, conflict resolution, etc.)
2. The profile is stored securely on the server — other users never see it
3. When you search, the server calculates mathematical compatibility across 9 dimensions
4. You get matches with percentage scores and human-readable explanations

## Supported platforms

| Platform | Install command |
|----------|----------------|
| **Claude Code** | `curl -s https://viboscope.com/api/v1/install?platform=claude-code \| sh` |
| **Cursor** | `curl -s https://viboscope.com/api/v1/install?platform=cursor \| sh` |
| **Gemini CLI** | `curl -s https://viboscope.com/api/v1/install?platform=gemini \| sh` |
| **OpenAI Codex** | `curl -s https://viboscope.com/api/v1/install?platform=codex \| sh` |
| **Windsurf** | `curl -s https://viboscope.com/api/v1/install?platform=windsurf \| sh` |
| **Roo Code** | `curl -s https://viboscope.com/api/v1/install?platform=roo \| sh` |
| **Replit** | `curl -s https://viboscope.com/api/v1/install?platform=replit \| sh` |
| **Aider** | `curl -s https://viboscope.com/api/v1/install?platform=aider \| sh` |
| **Manual** | Download [SKILL.md](SKILL.md) to your agent's skills directory |

Or just tell your agent: **"Install Viboscope"** — most platforms support `GET /install`.

## Features

- **9 compatibility dimensions**: values, communication, conflict style, attachment, work style, Big Five, team role, interests, embedding
- **7 search contexts**: business, romantic, friendship, professional, intellectual, hobby, general
- **Group matching**: find teams for mastermind groups or hackathons
- **Cross-platform**: transfer your profile between agents with transfer codes
- **Privacy-first**: your psychological portrait never leaves the server, only match scores are shared

## Links

- **Website**: [viboscope.com](https://viboscope.com)
- **API**: `https://viboscope.com/api/v1`
- **Skill file**: [SKILL.md](SKILL.md)

## License

MIT
