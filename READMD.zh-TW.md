[English](README.md) | **繁體中文**

# Agent Skills

收集一些 [Agent Skills](https://agentskills.io/home)。

## 使用方法

複製此儲存庫並軟連結到各個 Agent 的搜尋路徑。

```shell
ln -s /path/to/agent-skills/skills <agent-search-dir>/skills
```

一些常見 Agent 的搜尋路徑：

<details>
<summary>

#### Claude Code

</summary>

- `$HOME/.claude/skills`

</details>

<details>
<summary>

#### Codex

</summary>

- `$HOME/.codex/skills`
- `$HOME/.agents/skills`

</details>

<details>
<summary>

#### Gemini CLI

</summary>

- `$HOME/.gemini/skills`
- `$HOME/.agents/skills`

</details>

<details>
<summary>

#### GitHub Copilot

</summary>

- `$HOME/.copilot/skills`
- `$HOME/.claude/skills`
- `$HOME/.agents/skills`

</details>

<details>
<summary>

#### Google Antigravity

</summary>

- `$HOME/.gemini/antigravity/skills`

</details>

<details>
<summary>

#### OpenCode

</summary>

- `$HOME/.config/opencode/skills`
- `$HOME/.claude/skills`
- `$HOME/.agents/skills`

</details>

## 參考資料

- [Agent Skills - Gemini CLI Docs](https://geminicli.com/docs/cli/skills/)
- [Agent Skills - Google Antigravity Documentation](https://antigravity.google/docs/skills)
- [Agent Skills - OpenAI Developers](https://developers.openai.com/codex/skills/)
- [Agent Skills - OpenCode Docs](https://opencode.ai/docs/skills/)
- [Extend Claude with Skills - Claude Code Docs](https://code.claude.com/docs/en/skills)
- [Use Agent Skills in VS Code - Visual Studio Code Documentation](https://code.visualstudio.com/docs/copilot/customization/agent-skills)