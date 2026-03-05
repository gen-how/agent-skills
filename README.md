**English** | [繁體中文](README.zh-TW.md)

# Agent Skills

A collection of [Agent Skills](https://agentskills.io/home).

## Usage

Clone this repository and create a symlink to each agent's skill search path.

```shell
ln -s /path/to/agent-skills/skills <agent-search-dir>/skills
```

Common skill search paths for several agents:

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
> All of the paths above are user scope search paths.  
> For project scope paths, you can simply place them under the working directory in most cases.  
> For other special paths, please refer to each agent provider's official documentation.

## Skill List

### uv

Adapted from the official Claude Code plugin repository, [astral-sh/claude-code-plugins](https://github.com/astral-sh/claude-code-plugins), with small modifications.  
This enables agents to use [uv](https://github.com/astral-sh/uv) to manage Python projects.

## References

- [Agent Skills - Gemini CLI Docs](https://geminicli.com/docs/cli/skills/)
- [Agent Skills - Google Antigravity Documentation](https://antigravity.google/docs/skills)
- [Agent Skills - OpenAI Developers](https://developers.openai.com/codex/skills/)
- [Agent Skills - OpenCode Docs](https://opencode.ai/docs/skills/)
- [Extend Claude with Skills - Claude Code Docs](https://code.claude.com/docs/en/skills)
- [Use Agent Skills in VS Code - Visual Studio Code Documentation](https://code.visualstudio.com/docs/copilot/customization/agent-skills)
