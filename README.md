## 💬 Support

Found a bug or need help? [Join the Discord](https://discord.gg/ZYPbDzf7Sc) to report it.

[![Discord](https://img.shields.io/badge/Discord-Join-5865F2?logo=discord&logoColor=white)](https://discord.gg/ZYPbDzf7Sc)
# Tpa 🌀🖥️

A teleport-request plugin with full GUI confirmation menus — no more guessing who accepted what. Send, accept,
decline, and cancel requests through clean point-and-click menus, or fall back to plain commands. ✨
<img width="746" height="409" alt="image" src="https://github.com/user-attachments/assets/0ff55d5f-6b2a-41e7-b566-c7b09de74172" />

---

## 🚀 Features 🌟

- 📨 **`/tpa <player>`** → opens a confirm-before-send GUI (red = cancel, green = confirm)
- 💬 Target gets a **clickable chat message** — click it to respond, or type `/tpaccept`
- 🖥️ Accept/Decline GUI: red glass panels on the left, green on the right, requester's **player head + username** front and center
- ⏳ **3-second countdown** before teleporting (configurable), cancels instantly if you move
- 🤖 **`/tpauto`** — toggle auto-accepting every incoming request, confirms ON/OFF in chat
- ❌ **`/tpacancel`** — cancel your own outgoing request
- 🚫 **`/tpadecline`** — reject an incoming request directly
- ⏱️ Requests auto-expire after 60s if ignored (configurable)
- 🔁 20-second resend cooldown per target, so you can't spam the same person (configurable)
- ⚙️ All timings and every message fully customizable via `config.yml`

---

## 📜 Commands

| Command             | Description                                       |
| -------------------- | --------------------------------------------------- |
| `/tpa <player>`      | 🌀 Request to teleport to a player (opens GUI)      |
| `/tpaccept`          | ✅ Open the accept/decline menu for your pending request |
| `/tpadecline`        | 🚫 Decline your pending incoming request             |
| `/tpacancel`         | ❌ Cancel your outgoing request                       |
| `/tpauto`            | 🤖 Toggle auto-accepting all incoming requests        |

## ⚙️ Configuration

```yaml
teleport-countdown-seconds: 3
request-expiry-seconds: 60
resend-cooldown-seconds: 20
```

Every chat message (request sent, expired, declined, cancelled, countdown, etc.) is also editable under `messages:` in `config.yml`.

Found at `plugins/Tpa/config.yml` after first run — edit and restart to apply.

---

## ⚡ Installation

1. Download the latest JAR and place it in your server's `plugins` folder 📥
2. Start or restart your Paper server 🔄

**Requires:** Paper 1.21.11+ • Java 21+

---

## 📄 Author & Use

Plugin by **Metro** 💥
Free to use on your servers. Re-uploading or claiming as your own is **not allowed**.

---

Teleporting, made painless. 🎉🌀
