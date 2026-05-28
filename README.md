<div align="center">

<img src="https://pegasusac.net/logo/pegasus.png" width="100" alt="PegasusAC Logo" />

# PegasusAC

### The Most Advanced FiveM Anti-Cheat — 2026

<br/>

[![Discord](https://img.shields.io/discord/1113814297999581245?color=5865F2&label=Discord&logo=discord&logoColor=white&style=for-the-badge)](https://discord.gg/pegasusac)
[![Website](https://img.shields.io/badge/Website-pegasusac.net-22d3ee?style=for-the-badge&logo=googlechrome&logoColor=white)](https://pegasusac.net)
[![Panel](https://img.shields.io/badge/Panel-panel.pegasusac.net-7c3aed?style=for-the-badge&logo=vercel&logoColor=white)](https://panel.pegasusac.net)
[![YouTube](https://img.shields.io/badge/YouTube-Subscribe-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCb8_VgKaeNMn7ww1nihNkdA)
[![TikTok](https://img.shields.io/badge/TikTok-Follow-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@pegasus.anticheat)

<br/>

[![OneSync](https://img.shields.io/badge/OneSync-Required-3b82f6?style=flat-square&logo=fivem&logoColor=white)](https://docs.fivem.net/docs/scripting-reference/onesync/)
[![Artifacts](https://img.shields.io/badge/Latest%20Artifacts-Required-3b82f6?style=flat-square&logo=fivem&logoColor=white)](https://runtime.fivem.net/artifacts/fivem/)
[![CFX Asset](https://img.shields.io/badge/CFX%20Asset%20System-Permanent%20License-22c55e?style=flat-square)](https://forum.cfx.re/)
[![Framework](https://img.shields.io/badge/Framework-ESX%20%7C%20QBCore%20%7C%20VRP%20%7C%20Custom-f97316?style=flat-square)](https://pegasusac.net/docs)

<br/>

![PegasusAC Banner](https://pegasusac.net/images/wallpaper_pegasus.png)

</div>

<br/>

## What is PegasusAC?

PegasusAC started as a personal project to solve a real problem — cheaters on Greek FiveM servers were using spoofers to bypass bans and come back within minutes. After building a server-side script to catch them, the results were good enough that other server owners started asking for it too. That's how this turned into what it is today.

The core idea is simple: when someone connects to your server you get their SteamHex, IP, license, and hardware tokens. A spoofer tries to hide or change those values. We built detection around exactly that, and kept adding to it ever since — event protection, AI screenshot analysis, real-time monitoring, and a full management panel.

PegasusAC is now running on 500+ servers worldwide. It's not magic, but it works.

<br/>

## Features

**Detection**

| Feature | Description |
|---|---|
| AI Screenshot Detection | Real-time screen analysis using AI. Catches cheaters that would otherwise slip through server-side checks |
| Spoofer Detection | Identifies players trying to reconnect after a ban using spoofed hardware identifiers |
| Event Protection | Blocks malicious FiveM network events and server exploits |
| Identifier Analysis | Inspects SteamHex, IP, license, and hardware tokens on every connection |
| Continuous Updates | We push updates whenever new cheats or bypasses start spreading |

**Management Panel** — [panel.pegasusac.net](https://panel.pegasusac.net)

| Module | What it does |
|---|---|
| Live Map | See all players on the map in real time, with health, armor, ping, and coordinates |
| Player Management | Full player list with history and quick actions |
| Ban System | Create, manage, and review bans. Includes an unban request workflow |
| Detection Analytics | See every anti-cheat trigger visualized, per player and per detection type |
| Activity Logs | Full history of everything that happens on your server and in the panel |
| Staff Logs | Every admin action is logged so you always know who did what |
| Roles and Permissions | Set up role-based access so your staff only sees what they need to |
| Sub-users | Add team members to your server without giving them full access |
| Server Config | Edit your anti-cheat configuration directly from the panel, no file access needed |
| AI Live Stream | Open a live stream of any player's screen directly from the panel |
| Screenshot Capture | Take a screenshot of any player on demand |

**General**

- Works out of the box with ESX, QBCore, VRP, and custom frameworks. No extra setup needed.
- Designed to run with minimal performance impact. Your server won't notice it's there.
- Every detection threshold is configurable so you can tune it to your server's specific needs.
- Fully CFX compliant. We don't do anything that violates platform rules or player privacy.
- Your license is permanent through the CFX asset system. Not a subscription, not tied to our uptime.

<br/>

## How to get it

1. Go to [pegasusac.net/products](https://pegasusac.net/products) and grab a license
2. Join our [Discord](https://discord.gg/pegasusac) and head to the **#claim-pegasus** channel to claim your resource
3. Drop the `PegasusAC` folder into your server's resources directory
4. Read through the docs before you start — it takes about 30 minutes and it matters. Misconfigured settings are the main reason people see false positives
5. Add `ensure PegasusAC` to your `server.cfg` and you're good to go

<br/>

## Requirements

| Requirement | Details |
|---|---|
| OneSync | Required, must be enabled |
| FiveM Artifacts | Keep your server artifacts up to date |

Take the time to configure it properly before you open your server. A default config is included but every server is different, and 30 minutes of reading the docs will save you a lot of headaches.

<br/>

## Documentation

Everything you need is at [pegasusac.net/docs](https://pegasusac.net/docs) — installation, configuration, framework setup, and troubleshooting.

You can also reach us at [pegasusac.net/support](https://pegasusac.net/support) or jump into our [Discord](https://discord.gg/pegasusac) for direct help.

<br/>

## Showcase

<div align="center">

<br/><br/>

<a href="https://www.youtube.com/channel/UCb8_VgKaeNMn7ww1nihNkdA">
  <img src="https://img.youtube.com/vi/5cY1V7LxT5Q/maxresdefault.jpg" alt="PegasusAC Showcase" width="680">
</a>

</div>

<br/>

## Questions

<details>
<summary><b>How does the detection actually work?</b></summary>
<br/>
It runs on both the client and server side. When someone connects we check their identifiers, and throughout the session we monitor for suspicious events, unauthorized modifications, and known cheat behavior. The AI screenshot detection adds an extra layer by actually looking at what the player sees on screen.
</details>

<details>
<summary><b>Will it lag my server?</b></summary>
<br/>
No. Performance was a priority from the start. The detection runs in the background and you won't see a noticeable impact on server resources.
</details>

<details>
<summary><b>Does it work with ESX / QBCore / VRP?</b></summary>
<br/>
Yes, all of them. PegasusAC doesn't depend on any specific framework so it works with whatever you're running, custom setups included.
</details>

<details>
<summary><b>Can it fully stop spoofing?</b></summary>
<br/>
No, and anyone who tells you their anti-cheat fully stops spoofing is lying. What we can do is make it significantly harder and catch most attempts. Out of 400 test cases, 5 players were incorrectly flagged — those can all be whitelisted through the panel.
</details>

<details>
<summary><b>How often do you push updates?</b></summary>
<br/>
Regularly. Whenever a new cheat or bypass starts circulating we work on catching it. You can follow what changed at <a href="https://pegasusac.net/changelog">pegasusac.net/changelog</a>.
</details>

<details>
<summary><b>Why the CFX asset system and not a custom license server?</b></summary>
<br/>
Because your license should belong to you permanently. With the CFX asset system, even if we stopped operating tomorrow your resource would still work. You're not renting access, you own it.
</details>

<details>
<summary><b>Why does it cost money?</b></summary>
<br/>
A free anti-cheat is one that every cheater can also download and reverse engineer. Keeping it paid means the people who have it are server owners, not the people we're trying to catch.
</details>

<details>
<summary><b>Is it open source?</b></summary>
<br/>
No. Making it open source would let anyone find the detection methods and build bypasses. We use the Tebex escrow system so you don't have to take our word for the file safety — it's independently verified.
</details>

<br/>

## Links

[Website](https://pegasusac.net) &nbsp;&nbsp; [Panel](https://panel.pegasusac.net) &nbsp;&nbsp; [Documentation](https://pegasusac.net/docs) &nbsp;&nbsp; [Purchase](https://pegasusac.net/products) &nbsp;&nbsp; [Discord](https://discord.gg/pegasusac) &nbsp;&nbsp; [YouTube](https://www.youtube.com/channel/UCb8_VgKaeNMn7ww1nihNkdA) &nbsp;&nbsp; [TikTok](https://www.tiktok.com/@pegasus.anticheat) &nbsp;&nbsp; [Changelog](https://pegasusac.net/changelog)

<br/>

<div align="center">
<sub>Built in Greece · <a href="https://pegasusac.net/terms">Terms</a> · <a href="https://pegasusac.net/privacy">Privacy</a></sub>
</div>
