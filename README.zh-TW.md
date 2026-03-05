[English](README.md) | **繁體中文**

# Agent Skills

收集一些 [Agent Skills](https://agentskills.io/home)。

## 使用方法

複製此儲存庫並軟連結到各個 Agent 的搜尋路徑。

```shell
ln -s /path/to/agent-skills/skills <agent-search-dir>/skills
```

一些常見 Agent 的搜尋路徑：

<details><summary><b>Claude Code</b></summary>

- `$HOME/.claude/skills`

</details>

<details><summary><b>Codex</b></summary>

- `$HOME/.codex/skills`
- `$HOME/.agents/skills`

</details>

<details>
<summary><b>Gemini CLI</b></summary>


- `$HOME/.gemini/skills`
- `$HOME/.agents/skills`

</details>

<details><summary><b>GitHub Copilot</b></summary>

- `$HOME/.copilot/skills`
- `$HOME/.claude/skills`
- `$HOME/.agents/skills`

</details>

<details><summary><b>Google Antigravity</b></summary>

- `$HOME/.gemini/antigravity/skills`

</details>

<details><summary><b>OpenCode</b></summary>

- `$HOME/.config/opencode/skills`
- `$HOME/.claude/skills`
- `$HOME/.agents/skills`

</details>


> [!NOTE]
> 以上都是使用者範圍的搜尋路徑，專案範圍的路徑大部分都是直接放到工作目錄底下即可。  
> 其他特殊路徑請參考各個 Agent 提供者的官方文件。

## Skill 列表

### uv

取自官方 [astral-sh/claude-code-plugins](https://github.com/astral-sh/claude-code-plugins) Claude Code 插件儲存庫，有稍作修改。  
讓 Agent 能夠使用 [uv](https://github.com/astral-sh/uv) 管理 Python 專案。

## 參考資料

- [Agent Skills - Gemini CLI Docs](https://geminicli.com/docs/cli/skills/)
- [Agent Skills - Google Antigravity Documentation](https://antigravity.google/docs/skills)
- [Agent Skills - OpenAI Developers](https://developers.openai.com/codex/skills/)
- [Agent Skills - OpenCode Docs](https://opencode.ai/docs/skills/)
- [Extend Claude with Skills - Claude Code Docs](https://code.claude.com/docs/en/skills)
- [Use Agent Skills in VS Code - Visual Studio Code Documentation](https://code.visualstudio.com/docs/copilot/customization/agent-skills)
