# AI Agent Rules for C Programming

## Impotant Update
This repo has been achrived because it is no longer needed because [the original auther](https://github.com/MaJerle/c-code-style) created a new agent skill which is much better and I personally use it more now.
Enjoy!

---

This repository packages a focused set of AI agent rules for recommended C code style and coding practices for standard C99 or later.

It is meant to keep assistants aligned with the surrounding codebase, reinforce consistent formatting and naming, and reduce style drift across C projects. The core guidance lives in [`rules/C-style-and-coding-rules.mdc`](./rules/C-style-and-coding-rules.mdc), which is loaded automatically for matching files.

Use this plugin when you want AI help that respects existing C conventions instead of rewriting code in a generic or inconsistent style. It is especially useful for projects that rely on `clang-format`, conventional header/source organization, and stable long-term maintainability.

> [!IMPORTANT]
> Credit: the original Recommended C style and coding rules were created by [MaJerle](https://github.com/MaJerle/c-code-style).

<img width="1419" height="608" alt="c-style-and-coding_banner" src="https://github.com/user-attachments/assets/9090e85d-5afc-4fe8-93a5-ec791227bfcc" />

## What it covers

- Core C style conventions for C99 and later
- Formatting rules that work with `clang-format`
- Indentation, spacing, braces, and control-flow layout
- Naming, scope, and variable usage patterns
- Functions, macros, structures, and typedef guidance
- Header/source organization and include handling
- Comments, documentation, and maintainable code structure
- Project-level consistency across existing codebases

## Installation

> [!NOTE]
> Claude Code installation guide is coming very soon.

<details>
<summary>Cursor</summary>

Copy the plugin into Cursor’s plugin directory:

```bash
git clone https://github.com/AhmedAbouelkher/ai_c_style_and_coding.git ~/.cursor/plugins/ai_c_style_and_coding
```

Cursor auto-discovers rules from `.agents/rules/` and `.cursor/rules/`.

</details>

<!-- <details>
<summary>Claude Code</summary>

Copy the plugin into Claude’s plugin directory:

```bash
cp -R .claude-plugin ~/.claude/plugins/ai_c_style_and_coding
```

</details> -->

<details>
<summary>Antigravity</summary>

Copy the plugin into Antigravity’s discovery directory:

```bash
git clone https://github.com/AhmedAbouelkher/ai_c_style_and_coding.git ~/.antigravity/skills/ai_c_style_and_coding
```

</details>

<details>
<summary>OpenCode</summary>

Copy the plugin into OpenCode’s discovery directory:

```bash
git clone https://github.com/AhmedAbouelkher/ai_c_style_and_coding.git ~/.agents/skills/ai_c_style_and_coding
```

OpenCode auto-discovers skills from `~/.agents/skills/`, `~/.opencode/skills/`, and `~/.claude/skills/`.

</details>

<details>
<summary>Codex (OpenAI)</summary>

Copy the plugin into Codex’s discovery directory:

```bash
git clone https://github.com/AhmedAbouelkher/ai_c_style_and_coding.git ~/.agents/skills/ai_c_style_and_coding
```

Codex auto-discovers skills from `~/.agents/skills/` and `.agents/skills/`.

</details>

<details>
<summary>Copilot</summary>

Copy the plugin into Copilot’s discovery directory:

```bash
git clone https://github.com/AhmedAbouelkher/ai_c_style_and_coding.git ~/.copilot/skills/ai_c_style_and_coding
```

Copilot auto-discovers rules from `.copilot/rules/`.

</details>

<details>
<summary>Gemini CLI</summary>

Install the extension from the repository URL:

```bash
gemini extensions install https://github.com/AhmedAbouelkher/ai_c_style_and_coding
```

Update with `gemini extensions update ai_c_style_and_coding`.

</details>

## License

MIT. See `LICENSE` for details.
