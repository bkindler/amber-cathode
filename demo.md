# Amber Cathode — Theme Demo

Welcome to the terminal. This file showcases every visual element of the theme. Open it in **Obsidian** with Amber Cathode enabled.

---

## System Status

### Connection Established
#### Modem Speed: 2400 Baud
##### Signal Quality: Excellent
###### Last Login: 1987-03-15 23:42

---

## Body Text & Inline Formatting

All text renders in **monospace** — just like a real terminal. The amber phosphor glows softly against the near-black CRT screen. You can write **bold text** for emphasis, use *italic text* for annotations, or combine ***both*** when it matters. ~~Strikethrough~~ marks deprecated entries. Inline `code snippets` have a subtle border like input fields.

Here is a [link to the BBS](https://obsidian.md) with the characteristic amber glow, and here is an [[Internal Link]] as you'd use it in your vault.

---

## Blockquotes

> "The future is already here — it's just not evenly distributed."
> — William Gibson, 1993

> [!tip] SYSOP Message
> Welcome to the board! Please read the rules before posting. New file areas have been added to Door #3.

> [!warning] System Warning
> Disk space critical: 847 KB remaining on Drive C:

> [!info] Bulletin
> FidoNet mail will be processed at 02:00 AM. Please keep messages under 64 KB.

---

## Lists

### Unordered

- CRT phosphor glow via text-shadow
- Scanline overlay via repeating-linear-gradient
- Heavy edge vignette simulating barrel distortion
- Monospace font throughout — full terminal aesthetic
  - IBM Plex Mono as primary face
  - JetBrains Mono as fallback

### Ordered

1. Dial the BBS number
2. Wait for carrier tone
3. Press ENTER for terminal mode
4. Login with your handle

### Checklists

- [x] Amber phosphor colours
- [x] CRT scanlines
- [x] Phosphor glow text-shadow
- [x] Screen vignette
- [ ] Submit to Community Themes
- [ ] Add screenshots

---

## Tags

#retro #crt #amber #terminal #bbs #80s #nostalgia #modem

---

## Code

Inline: The colour `#ffb000` is classic amber phosphor.

```basic
10 PRINT "================================"
20 PRINT "  WELCOME TO AMBER CATHODE BBS"
30 PRINT "  SysOp: Björn Kindler"
40 PRINT "  Nodes: 2 | Speed: 2400 Baud"
50 PRINT "================================"
60 PRINT
70 INPUT "Enter your handle: "; H$
80 PRINT "Welcome, "; H$; "!"
90 GOTO 100
```

```
╔══════════════════════════════════╗
║     AMBER CATHODE BBS v1.0      ║
║  ────────────────────────────    ║
║  [1] Message Boards              ║
║  [2] File Library                ║
║  [3] Door Games                  ║
║  [4] User List                   ║
║  [5] SysOp Chat                  ║
║  [Q] Logoff                      ║
║                                  ║
║  Select: _                       ║
╚══════════════════════════════════╝
```

---

## Tables

| Area | Files | Description |
|---|---|---|
| GAMES | 142 | DOS games & shareware |
| UTILS | 87 | System utilities |
| COMMS | 34 | Modem & terminal software |
| MUSIC | 23 | MOD tracker files |
| ASCII | 56 | ANSI/ASCII artwork |

---

## ASCII Art Sample

```
    ___          __              ______      __  __             __
   /   |  ____ _/ /_  ___  ____/ ____/___ _/ /_/ /_  ____  ___/ /___
  / /| | / __ `__ \/ __ \/ _ \/ /   / __ `/ __/ __ \/ __ \/ __  / _ \
 / ___ |/ / / / / / /_/ /  __/ /___/ /_/ / /_/ / / / /_/ / /_/ /  __/
/_/  |_/_/ /_/ /_/_.___/\___/\____/\__,_/\__/_/ /_/\____/\__,_/\___/
```

---

## Horizontal Rules

The lines above and below are `<hr>` elements — rendered as glowing amber bars.

---

## Math (if KaTeX enabled)

Baud rate calculation: $B = \frac{1}{T}$ where $T$ is the symbol duration.

$$
\text{Transfer time} = \frac{\text{File size (bits)}}{\text{Baud rate}} = \frac{8 \times 1024 \times 50}{2400} \approx 170.7 \text{ seconds}
$$

---

## Footnotes

Amber Cathode recreates the look of 80s monochrome CRT terminals[^1] and BBS systems[^2].

[^1]: Amber phosphor monitors (e.g., Hercules-compatible) were popular in Europe, while green phosphor dominated in the US.
[^2]: Bulletin Board Systems — dial-up servers accessed via modem, predecessor to the modern internet.

---

## Embedded Content

> [!example] Terminal Session
> A typical BBS login sequence:
> ```
> ATDT 555-0142
> CONNECT 2400
>
> ══════════════════════════════
>   Welcome to Night Owl BBS
>   SysOp: The Wizard
>   Running: RemoteAccess 2.50
> ══════════════════════════════
>
> Login: _
> ```
> The carrier signal was music to our ears.

---

## Colour Palette Reference

| Role | Swatch | Hex |
|---|---|---|
| **Phosphor Bright** | ████ | `#ffb000` |
| **Phosphor Normal** | ████ | `#cc8800` |
| **Phosphor Muted** | ████ | `#8a5e10` |
| **Phosphor Dim** | ████ | `#5a3e0a` |
| **Screen Black** | ████ | `#0c0a04` |
| **Sidebar** | ████ | `#060400` |
| **Border** | ████ | `#2a2208` |

---

*Amber Cathode v1.0.0 — MIT License — Björn Kindler*
*NO CARRIER*
