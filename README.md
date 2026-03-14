<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&duration=3000&pause=1000&color=FF6B35&center=true&vCenter=true&width=600&lines=%F0%9F%94%A5+BurnChat;Disposable+Chat+Rooms;No+Accounts.+No+Logs.+No+Traces.;Server+Stores+Nothing" alt="Typing SVG" />

<br><br>

[![Website](https://img.shields.io/badge/🔥_burnchat.io-Visit_Site-ff6b35?style=for-the-badge)](https://burnchat.io)
[![Widget](https://img.shields.io/badge/📦_Widget-Embed_Free-ff6b35?style=for-the-badge)](https://burnchat.io/widget)
[![Blog](https://img.shields.io/badge/📝_Blog-Read-333?style=for-the-badge)](https://burnchat.io/blog)
[![Twitter](https://img.shields.io/badge/𝕏-Follow-000?style=for-the-badge)](https://x.com/burnchatio)
[![WordPress](https://img.shields.io/badge/WordPress-Plugin-21759B?style=for-the-badge&logo=wordpress)](https://burnchat.io/widget)

</div>

---

### 🔥 What is BurnChat?

We build **ephemeral, zero-log communication tools**. The server is a pure relay — messages pass through and are **never stored**. The only copy lives in your browser's sessionStorage and dies when you close the tab. No database. No disk. No RAM storage. **Nothing.**

---

### ⚡ What We Ship
```
🔥 Disposable chat rooms          No accounts needed
🎤 Ephemeral voice messages        Listen once, gone forever  
⌨️ 37 slash commands               /msg /ban /mute /poll /dice /play
🛡️ Room admin system               /admin /kick /warn /rules /pin
🐍 Multiplayer Snake               Play inside the chat
📦 Embeddable widget               One line of code
📋 WordPress plugin                Install from WP admin
🌗 Dark/Light themes               Auto-detection
💬 Private messaging               Whispers + away auto-reply
🎲 Polls & dice                    /poll /dice
📌 Pinned messages                 Sticky bar at top of chat
⏱️ Chat cooldown                   Admin-controlled rate limit
🔒 Zero server storage             Pure relay — nothing stored
```

---

### 🛠️ Tech Stack

<p align="center">
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
<img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" />
<img src="https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socket.io&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white" />
<img src="https://img.shields.io/badge/Let's_Encrypt-003A70?style=flat-square&logo=letsencrypt&logoColor=white" />
</p>

---

### 🔐 Privacy Architecture

| Layer | What happens |
|-------|-------------|
| **Server** | Pure relay — messages pass through, never stored |
| **Browser** | Messages in sessionStorage — dies when tab closes |
| **Disk** | Zero data ever written. Period. |
| **nginx** | `access_log off`, `error_log /dev/null` |
| **systemd** | `StandardOutput=null` |

**The server never holds a single message.** Your browser is the only place messages exist — and only until you close the tab. There is nothing to subpoena, nothing to breach, nothing to leak.

---

### 📊 Stats

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/Burnchat/burnchat.io?style=social)
![GitHub forks](https://img.shields.io/github/forks/Burnchat/burnchat.io?style=social)

</div>

---

### 🗺️ Roadmap

- [x] Voice messages with listen-once
- [x] 37 slash commands
- [x] Admin system with /adminpw
- [x] Embeddable widget + configurator
- [x] WordPress plugin
- [x] Client-only message storage (sessionStorage)
- [x] Polls, dice, pinned messages
- [x] /warn, /rules, /announce, /roominfo
- [x] Share via Telegram, WhatsApp, X, email
- [x] Open source on GitHub
- [x] Server as pure relay — zero message storage
- [ ] E2E encryption
- [ ] WebRTC peer-to-peer voice chat
- [ ] Collaborative pixel canvas
- [ ] Client-side AI moderation

---

<div align="center">

**The server never stores a single message.**

🔥 [burnchat.io](https://burnchat.io)

</div>
