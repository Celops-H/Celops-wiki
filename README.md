# agent-config

个人 agent 配置仓库。存放全局规则文件和自定义技能，同步到本机各 agent。

## 目录

- `agents/` — 全局规则文件，四份内容一致
  - `AGENTS.md` — pi、MiniCode、Qoder 读取
  - `CLAUDE.md` — Claude Code 读取
- `skills/` — 自定义技能，每个技能一个目录，内含 `SKILL.md`

## 同步到本机

```bash
cp agents/AGENTS.md ~/.pi/agent/AGENTS.md
cp agents/AGENTS.md ~/.minicode/AGENTS.md
cp agents/AGENTS.md ~/.qoder-cn/AGENTS.md
cp agents/CLAUDE.md ~/.claude/CLAUDE.md
```

## 修改流程

先改 `agents/AGENTS.md`，确认后再同步四份到本机。
