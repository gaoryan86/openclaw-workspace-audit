# openclaw-workspace-audit (OpenClaw skill)

Audits and optimizes an OpenClaw workspace (AGENTS.md / SOUL.md / USER.md / TOOLS.md / IDENTITY.md / HEARTBEAT.md / BOOT.md / MEMORY.md / memory/*) for:
- redundancy & dead content
- format compliance
- cross-file conflicts
- token efficiency

## Install

Clone (or copy) this folder into your OpenClaw skills directory:

```bash
mkdir -p ~/.openclaw/skills
cd ~/.openclaw/skills

git clone https://github.com/gaoryan86/openclaw-workspace-audit.git
```

Restart OpenClaw (or reload skills if your setup supports it), then invoke it by asking:
- “audit workspace”
- “clean up memory”
- “optimize tokens”
- “文档审计 / 精简文档”

## Files

- `SKILL.md` — the skill definition & workflow
