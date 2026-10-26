<p align="center">
  <img src="https://raw.githubusercontent.com/OpenTodoApp/OpenTodo/main/web/public/pwa-192.png" width="88" height="88" alt="OpenTodo logo">
</p>

<h3 align="center">OpenTodo: your tasks, your server</h3>

<p align="center">
An open-source, local-first task manager you host yourself. Today, Upcoming, projects, reminders, a time-blocking calendar, shared lists and two-way sync with your calendar, on your phone and your computer, even offline. No subscription, no tracking, AGPL-3.0.
</p>

<p align="center">
  <a href="https://demo.open-todo.app"><strong>Try the demo</strong></a> ·
  <a href="https://open-todo.app/docs/"><strong>Docs</strong></a> ·
  <a href="https://open-todo.app"><strong>Website</strong></a> ·
  <a href="https://github.com/OpenTodoApp/OpenTodo/releases/latest"><strong>Latest release</strong></a>
</p>

### Repositories

| Repository | What it is |
|---|---|
| [**OpenTodo**](https://github.com/OpenTodoApp/OpenTodo) | The app: Go server with SQLite, the web app, the Android app, the `ot` CLI and the browser extension |
| [OpenTodoWebsite](https://github.com/OpenTodoApp/OpenTodoWebsite) | [open-todo.app](https://open-todo.app) and its docs |
| [opentodo-homeassistant](https://github.com/OpenTodoApp/opentodo-homeassistant) | Home Assistant integration (HACS): your lists, counts, a calendar and events |
| [opentodo-homeassistant-addons](https://github.com/OpenTodoApp/opentodo-homeassistant-addons) | Home Assistant add-on: run OpenTodo on Home Assistant OS |
| [n8n-nodes-opentodo](https://github.com/OpenTodoApp/n8n-nodes-opentodo) | n8n community nodes and a signed webhook trigger |
| [opentodo-claude](https://github.com/OpenTodoApp/opentodo-claude) | Skills and the MCP server for Claude Code |
| [opentodo-runtipi](https://github.com/OpenTodoApp/opentodo-runtipi) · [opentodo-unraid](https://github.com/OpenTodoApp/opentodo-unraid) | App store templates for Runtipi and Unraid |

### Run it

```bash
docker run -d -p 8080:8080 -v opentodo-data:/data ghcr.io/pixari/opentodo:stable
```

Then open http://localhost:8080. Guides for Docker Compose, Umbrel, CasaOS, TrueNAS, Unraid, Coolify, Home Assistant and more are in the [self-hosting docs](https://open-todo.app/docs/).

### Get involved

Bug reports, ideas and pull requests are welcome: start with [CONTRIBUTING.md](https://github.com/OpenTodoApp/OpenTodo/blob/main/CONTRIBUTING.md). Security issues: see [SECURITY.md](https://github.com/OpenTodoApp/OpenTodo/blob/main/SECURITY.md). If OpenTodo is useful to you, a ⭐ helps others find it.
