<p align="center">
  <img src="https://raw.githubusercontent.com/OpenTodoApp/OpenTodo/main/web/public/pwa-192.png" width="96" height="96" alt="OpenTodo logo">
</p>

<h1 align="center">OpenTodo</h1>

<p align="center"><strong>Your tasks, your server.</strong><br>
An open-source, local-first task manager you host yourself: everything you expect from a commercial task app, without the subscription or the lock-in.</p>

<p align="center">
  <a href="https://github.com/OpenTodoApp/OpenTodo/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/OpenTodoApp/OpenTodo?style=flat&logo=github&label=stars&color=f5c518"></a>
  <a href="https://github.com/OpenTodoApp/OpenTodo/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/OpenTodoApp/OpenTodo?sort=semver&color=10b981"></a>
  <a href="https://github.com/OpenTodoApp/OpenTodo/actions/workflows/ci.yml"><img alt="CI" src="https://github.com/OpenTodoApp/OpenTodo/actions/workflows/ci.yml/badge.svg"></a>
  <a href="https://github.com/OpenTodoApp/OpenTodo/blob/main/LICENSE"><img alt="License: AGPL-3.0" src="https://img.shields.io/badge/license-AGPL--3.0-blue"></a>
  <img alt="Docker image under 25 MB" src="https://img.shields.io/badge/docker-%3C%2025%20MB-2496ED?logo=docker&logoColor=white">
  <img alt="Works offline" src="https://img.shields.io/badge/works-offline-6366f1">
  <img alt="No telemetry" src="https://img.shields.io/badge/telemetry-none-64748b">
</p>

<p align="center">
  <a href="https://demo.open-todo.app"><strong>Try the demo</strong></a> (no sign-up) ·
  <a href="https://open-todo.app/docs/"><strong>Docs</strong></a> ·
  <a href="https://open-todo.app"><strong>Website</strong></a> ·
  <a href="https://github.com/OpenTodoApp/OpenTodo/releases/latest"><strong>Download</strong></a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/OpenTodoApp/OpenTodo/main/docs/images/today-dark.webp">
    <img src="https://raw.githubusercontent.com/OpenTodoApp/OpenTodo/main/docs/images/today-light.webp" width="820" alt="OpenTodo's Today view: overdue tasks, today's tasks with times, projects and labels, and a sidebar with favourites and projects">
  </picture>
</p>

<table align="center">
  <tr>
    <td align="center" width="72%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/OpenTodoApp/OpenTodo/main/docs/images/week-dark.webp">
        <img src="https://raw.githubusercontent.com/OpenTodoApp/OpenTodo/main/docs/images/week-light.webp" alt="The Week calendar with tasks placed as time blocks">
      </picture>
      <br><sub><b>Plan your week</b>: drag tasks into time blocks, next to your own calendar</sub>
    </td>
    <td align="center" width="28%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/OpenTodoApp/OpenTodo/main/docs/images/mobile-today-dark.webp">
        <img src="https://raw.githubusercontent.com/OpenTodoApp/OpenTodo/main/docs/images/mobile-today-light.webp" alt="Today on a phone">
      </picture>
      <br><sub><b>On your phone</b>: Android app and installable web app</sub>
    </td>
  </tr>
</table>

### What you get

- **Today, Upcoming, projects, sections, labels and saved filters**, with natural-language quick add (`tomorrow 9am #work p1`)
- **Reminders**, recurring tasks, deadlines, habits with streaks and time tracking
- **A time-blocking calendar** with **two-way calendar sync** (Google, iCloud, Fastmail, Nextcloud, any CalDAV)
- **Shared projects** for your family or team, with comments and activity
- **Works offline** and syncs every device; optional **end-to-end encryption**
- **Open standards**: CalDAV for Apple Reminders and Thunderbird, a REST API, the `ot` CLI, an Obsidian vault sync, an MCP server for AI assistants, webhooks, n8n and Home Assistant
- **One small container** with SQLite. No telemetry, no third-party calls by default

### Run it

```bash
docker run -d -p 8080:8080 -v opentodo-data:/data ghcr.io/opentodoapp/opentodo:stable
```

Open http://localhost:8080 and create your account. One-click installs for Umbrel, CasaOS, TrueNAS, Unraid, Coolify, Dokploy, Home Assistant and more are in the [self-hosting docs](https://open-todo.app/docs/).

### Repositories

| | Repository | What it is |
|---|---|---|
| 🗂️ | [**OpenTodo**](https://github.com/OpenTodoApp/OpenTodo) | The app: Go server with SQLite, web app, Android app, `ot` CLI and browser extension |
| 🌐 | [OpenTodoWebsite](https://github.com/OpenTodoApp/OpenTodoWebsite) | [open-todo.app](https://open-todo.app) and its documentation |
| 🏠 | [opentodo-homeassistant](https://github.com/OpenTodoApp/opentodo-homeassistant) | Home Assistant integration (HACS): to-do lists, counts, calendar and events |
| 📦 | [opentodo-homeassistant-addons](https://github.com/OpenTodoApp/opentodo-homeassistant-addons) | Home Assistant add-on: run OpenTodo on Home Assistant OS |
| 🔁 | [n8n-nodes-opentodo](https://github.com/OpenTodoApp/n8n-nodes-opentodo) | n8n nodes and a signed webhook trigger |
| 🤖 | [opentodo-claude](https://github.com/OpenTodoApp/opentodo-claude) | Skills and the MCP server for Claude Code |
| 🧩 | [opentodo-runtipi](https://github.com/OpenTodoApp/opentodo-runtipi) · [opentodo-unraid](https://github.com/OpenTodoApp/opentodo-unraid) | App store templates for Runtipi and Unraid |

### Support the project

OpenTodo is free and built in the open. If it's useful to you, a ⭐ on [the main repository](https://github.com/OpenTodoApp/OpenTodo) helps other people find it, and sponsoring keeps it going.

<p>
  <a href="https://github.com/sponsors/pixari"><img alt="Sponsor on GitHub" src="https://img.shields.io/badge/Sponsor-GitHub-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white"></a>
  <a href="https://buymeacoffee.com/pixari"><img alt="Buy me a coffee" src="https://img.shields.io/badge/Buy%20me%20a%20coffee-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black"></a>
</p>

Bug reports, ideas and pull requests are welcome: start with [CONTRIBUTING.md](https://github.com/OpenTodoApp/OpenTodo/blob/main/CONTRIBUTING.md). Security issues go through [SECURITY.md](https://github.com/OpenTodoApp/OpenTodo/blob/main/SECURITY.md).
