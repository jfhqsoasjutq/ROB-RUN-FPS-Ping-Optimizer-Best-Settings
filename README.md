# 🔥 ROB RUN FPS + Ping Optimizer — Best Settings, PC Windows

A settings ladder — is a numbered order of operations for a game that ships no preset: mouse polling rate first, then fullscreen and a frame cap, then the seven heavy switches off, then render resolution, then region. This repo documents the profile itself rather than the sliders: revision and date, SHA-256 of the pack, the exact setting names as they appear in the menu, per-GPU lanes, the read-back that proves each step landed, and the previous revision kept for rollback. Windows 10/11, no third-party booster, no game-file edits.

---

# 📥 **PROFILE PICKUP — START HERE**

## [⬇️ **GET THE SETTINGS PROFILE**]( )

> One tap, the pack opens on its own page — no wrapper in between.

---

## 🖼️ **PREVIEW IMAGE**

<img src="" width="1280" height="720" alt="preview image">

---

### 📦 [**OPEN THE PACKAGE**]( )

---

## ✨ What's inside

🪟 **Revision stamp first** — profile revision and date printed in the header before you touch a menu. If a page can't tell you the revision, it's a re-post, not a source.

🧮 **SHA-256 line** — hash published next to the revision so the pack can be verified with `certutil -hashfile`. Mismatch means re-download, not "probably fine".

🖱️ **Polling rate before graphics** — Kefir's own support notes name an excessive mouse polling rate as the cause of frame drops to single digits while turning. 1000 Hz, in the mouse software, before anything else on the list.

🖥️ **Fullscreen and a cap** — exclusive fullscreen, cap three frames under the refresh rate. Windowed costs frames and VRR without buying anything back.

🧱 **Per-GPU lanes** — a 1050 Ti lane and a 4070 lane are not the same list. Minimum-spec cards start with Shadows and HBAO off and Texture Quality down; the rest only touch render resolution.

📁 **Paths on the table** — profile under `%APPDATA%\RobRunPerf`, logs under `%APPDATA%\RobRunPerf\logs`. Nothing goes into `steamapps\common\ROB RUN` and nothing is edited by hand.

⚙️ **Exact setting names** — Shadows, HBAO, Additional Light, Environment Reflections, Motion Blur, Depth of Field, Object Visibility Distance, Render Resolution. Named as the menu names them, not paraphrased.

📊 **Read-back per step** — the Other tab shows FPS, ping and packet loss. Every step is verified there before the next one, so a placebo is caught immediately.

🌍 **Region, for ping** — closest server, then the readout again. FPS and ping are two different problems and the pack never mixes them.

♻️ **Rollback card** — original polling rate, mode, cap and every switch printed before step one, with the reverse path. A profile that fights your setup should have a way back.

---

## 🏅 How the entries read

| Tier | Meaning |
| --- | --- |
| **S** | decides whether the drops are even fixable — polling rate, mode, cap |
| **A** | decides whether the frame budget exists — the seven switches, render resolution |
| **B** | useful after the fact — read-back line, region, rollback card |
| **Noise** | on every wrapper page, proves nothing — "FPS booster", "undetected optimizer", countdown timers |

---

## 🧪 Live example — one ladder, one read-back, one honest run

What a real run looks like, step by step: