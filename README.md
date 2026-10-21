# Maple EXP Overlay

> **Beta.** This is an early test version shared with a small group of players. Expect rough
> edges, and please tell us what breaks: right-click the panel > **Send feedback…**.

A small panel for **MapleStory Classic World** that shows your EXP/hr, time to the next level,
kills per minute, mesos and loot, your best EXP/hr per map with a shared leaderboard, and
celebrates rare drops with your friends.

## Before you install

- **Screen reading only.** The overlay looks at the game's picture, the same way you do. It never
  reads or changes the game's memory or files, never injects anything into the game, and never
  presses keys or clicks for you.
- **Use at your own risk.** Nexon's terms of service restrict third-party software. This tool is
  not made, endorsed or approved by Nexon. We believe a screen-only reader is low risk, but we
  can't promise how Nexon sees it.
- **What goes online.** Update checks; your character name and item, but only if you agree to
  share rare drops; your name, level and best EXP/hr per map, but only if you agree to share zone
  records. There are also anonymous usage logs: errors, plus a short summary every 5 minutes
  (EXP/hr, level, how well it reads the screen). They hold no names, map names, emails or
  screenshots. Each of these can be switched off in the right-click menu. Feedback you send
  includes only what you type, plus diagnostics if you leave that box ticked (screen size, UI
  scale, what it could read; no screenshots).
- Tested so far at 2560×1440. Other resolutions and UI sizes should work but are less tested;
  tell us if numbers look wrong.

## Download (Windows)

**[Download MapleExpOverlay.zip (latest)](https://github.com/idoglaive/maple-exp-overlay-releases/releases/latest/download/MapleExpOverlay.zip)**

1. Unzip it anywhere (e.g. your Documents folder).
2. Open the `MapleExpOverlay` folder, then the `runtime` folder, and double-click
   **`pythonw.exe`**. That's Python itself, signed by the Python Software Foundation, so Windows
   Smart App Control lets it run. (Smart App Control blocks shortcuts and .cmd launchers to it,
   so start it this way.)

## The one setup step: Ctrl+Alt+S

**Press Ctrl+Alt+S** (or click **Select EXP area** in the panel) and drag a box around the
`HP[…] MP[…] EXP …[…%]` numbers at the bottom of the game. A loose box is fine.

Until you do this, the panel can't measure anything. You only do it once; redo it if you change
the game's resolution or UI size. Your level, character name, map, loot and potions are then
found automatically.

"How to use.txt" in the zip explains every number.

It updates itself: when a new version is out, a green **UPDATE** badge appears in the panel's
title bar. Click it to restart into the new version.

## Mac

**[Download MapleExpOverlay-mac.zip (latest)](https://github.com/idoglaive/maple-exp-overlay-releases/releases/latest/download/MapleExpOverlay-mac.zip)**
(Apple Silicon Macs, M1 or newer, macOS 11+. The Mac version is the least tested.)

1. Unzip it and drag **MapleExpOverlay.app** into **Applications**.
2. The first time, right-click the app and choose **Open**, then **Open** again (it isn't
   notarized). On macOS 15 or newer, if it is blocked: **System Settings > Privacy & Security**,
   scroll down and click **Open Anyway**.
3. Allow **Screen Recording** when asked (and **Accessibility**, for the hotkeys), then quit and
   reopen the app: macOS applies these permissions only after a restart.
4. **Press Ctrl+Option+S** (or click **Select EXP area** in the panel) and drag a box around the
   `HP[…] MP[…] EXP …[…%]` row. This is the one required setup step.
