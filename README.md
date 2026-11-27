# Konstantinos Botonakis

I lead AI engineering at WP Engine and founded OpenCart Greece and London. I still write tools for the work I do, whether that’s running a shop from the terminal or making a coding agent easier to work with.

[Website](https://konstantinos.top/) · [Writing](https://konstantinos.top/blog/) · [CV](https://konstantinos.top/cv/)

## Featured projects

### Agent Computer Use

I built a Chrome extension so coding agents can check a page in the browser I already use. Their tabs stay in a separate background group.

[Repository & setup](https://github.com/konstantinosbotonakis/agent-computer-use)

<details>
<summary>See an example task</summary>

> Open the staging site and check whether the sign-in link is visible on the homepage.

1. The agent opens the site in its own Chrome tab group.
2. It reads the page and reports what it found.
3. The tab you were working in stays in focus.

</details>

### Context Diet

I built a Codex plugin for the point when tool output starts to bury the few lines you actually need.

[Why I built it](https://konstantinos.top/blog/42/) · [Repository](https://github.com/konstantinosbotonakis/codex-context-diet)

<details>
<summary>See a before-and-after example</summary>

**Original tool output**

```text
PASS tests/config.test.ts
FAIL tests/settings.test.ts
  Expected 200, received 403
PASS tests/render.test.ts
… more passing tests …
```

**What Codex could keep**

```text
FAIL tests/settings.test.ts
  Expected 200, received 403

Passing test lines omitted.
```

</details>

## Explore my work

<details open>
<summary>Tools for coding agents</summary>

- [Agent Computer Use](https://github.com/konstantinosbotonakis/agent-computer-use) lets agents use your Chrome in grouped background tabs.
- [Context Diet](https://github.com/konstantinosbotonakis/codex-context-diet) keeps bulky tool results from filling Codex’s context.
- [AI Skills](https://github.com/konstantinosbotonakis/ai-skills) collects reusable workflows for Codex, Claude Code, and other agents.

</details>

<details>
<summary>Tools for shops and servers</summary>

- [OC-CLI](https://github.com/Custom-Services-Limited/oc-cli) lets you manage OpenCart from the terminal.
- [WatchMySQL](https://github.com/konstantinosbotonakis/watchmysql) monitors MySQL connections and lets you set per-account limits in cPanel.

</details>

<details>
<summary>Away from the keyboard</summary>

I’m a petrolhead and I travel a lot. [My 2025 year in review](https://konstantinos.top/blog/34/) has a bit of work and a lot of miles.

</details>
