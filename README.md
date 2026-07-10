# ACC RT Target Delineation Skill — 部署包

## 文件说明

| 文件 | 用途 |
|------|------|
| `SKILL.md` | 主 Skill 文件（Hermes Agent / Claude Code 通用格式） |
| `README.md` | 本说明文件 |

## 一、在 Hermes Agent 上部署

```bash
# 复制到 Hermes skills 目录
mkdir -p ~/AppData/Local/hermes/skills/research/adenoid-cystic-carcinoma-rt-targets
cp SKILL.md ~/AppData/Local/hermes/skills/research/adenoid-cystic-carcinoma-rt-targets/

# 验证
hermes skills list | grep adenoid
```

## 二、在 Claude Code (Claude Desktop) 上部署

Claude Code 使用 skills-plugin 目录：

```bash
# 复制到 Claude skills 目录
mkdir -p ~/AppData/Local/Claude-3p/local-agent-mode-sessions/skills-plugin/00000000-0000-4000-8000-000000000001/<your-user-id>/skills/adenoid-cystic-carcinoma-rt-targets
cp SKILL.md ~/AppData/Local/Claude-3p/local-agent-mode-sessions/skills-plugin/00000000-0000-4000-8000-000000000001/<your-user-id>/skills/adenoid-cystic-carcinoma-rt-targets/
```

或者通过 Claude Code 的内置 skill 安装命令（如果支持）。

## 三、加载后使用

在 Hermes Agent 或 Claude Code 中，使用以下方式触发此 Skill：

**自动触发关键词**：
- "腺样囊性癌"
- "ACC 靶区"
- "adenoid cystic carcinoma radiotherapy"
- "三叉神经通路"
- "神经侵犯 放疗"

**手动加载**：
- Hermes Agent: `/skill adenoid-cystic-carcinoma-rt-targets`
- Claude Code: 提及上述关键词自动加载

## 依赖

此 Skill 是自包含的，不依赖其他 Skill。但如需完整的头颈靶区勾画体系，可同时加载 `head-neck-target-delineation` Skill。
