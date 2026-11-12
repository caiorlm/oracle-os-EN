```
   ██████╗ ██████╗  █████╗  ██████╗██╗     ███████╗     ██████╗ ███████╗
  ██╔═══██╗██╔══██╗██╔══██╗██╔════╝██║     ██╔════╝    ██╔═══██╗██╔════╝
  ██║   ██║██████╔╝███████║██║     ██║     █████╗      ██║   ██║███████╗
  ██║   ██║██╔══██╗██╔══██║██║     ██║     ██╔══╝      ██║   ██║╚════██║
  ╚██████╔╝██║  ██║██║  ██║╚██████╗███████╗███████╗    ╚██████╔╝███████║
   ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝╚══════╝╚══════╝     ╚═════╝ ╚══════╝
            O F F L I N E   S U R V I V A L   S Y S T E M
```

<p align="center">
<b>Survive and rebuild — no internet, no network, just an Android phone.</b><br>
On-device AI · survival guides · offline maps and routes · compass · plant ID by camera<br>
extreme power saving · printable guides · and a game: <b>GENESIS</b>
</p>

<p align="center">
<a href="https://github.com/caiorlm/oracle-os/releases/latest/download/OracleOS.apk"><b>⬇️ DOWNLOAD ORACLE (APK)</b></a>
&nbsp;·&nbsp;
<a href="https://github.com/caiorlm/oracle-os/releases/latest/download/GENESIS.apk"><b>🎮 DOWNLOAD THE GENESIS GAME (APK)</b></a>
&nbsp;·&nbsp;
<a href="https://github.com/caiorlm/oracle-os-EN/releases/latest"><b>📦 ALL FILES</b></a>
</p>

> 🇵🇹🇧🇷 *Versão em português: [caiorlm/oracle-os](https://github.com/caiorlm/oracle-os).*

---

## 📲 Install in 3 steps (for people who have never used GitHub)

No coding needed. **Do this on your Android phone, while you still have internet.**

```
 ┌──────────────────────────┐   ┌──────────────────────────┐   ┌──────────────────────────┐
 │  STEP 1                  │   │  STEP 2                  │   │  STEP 3                  │
 │                          │   │                          │   │                          │
 │  Tap the blue link:      │   │  Open the file           │   │  Open ORACLE.            │
 │                          │   │  OracleOS.apk            │   │                          │
 │  ⬇️ DOWNLOAD ORACLE      │ → │  (it is in               │ → │  It already works        │
 │                          │   │   "Downloads")           │   │  WITHOUT internet. ✔     │
 │  (top of this page)      │   │  and tap INSTALL.        │   │                          │
 └──────────────────────────┘   └──────────────────────────┘   └──────────────────────────┘
```

1. **Tap [⬇️ DOWNLOAD ORACLE](https://github.com/caiorlm/oracle-os/releases/latest/download/OracleOS.apk)**. Your phone downloads `OracleOS.apk` (about 120 MB).
2. **Open the file** (from the notification or *Files → Downloads*) and tap **Install**.
   - If Android says *"For your security, your phone is not allowed to install unknown apps from this source"*: tap **Settings → Allow from this source**, go back and tap **Install** again.
   - If *Play Protect* warns about an unknown app: tap **More details → Install anyway**. (The app is open source: all the code is in this repository.)
3. **Open Oracle.** The **71 guides** (English and Portuguese) are already inside. Compass, plants, emergency and power saving work straight away, with no internet.
   - 🌐 **Language:** tap **EN** at the top right of the Home screen to switch the whole app to English.

### Extras (optional, recommended)

| What | What for | How |
|---|---|---|
| 🎮 [`GENESIS.apk`](https://github.com/caiorlm/oracle-os/releases/latest/download/GENESIS.apk) | The game (farm + companion + lineage) | Install it like Oracle. Open it from Oracle's **GAME** tab ▶. On the first screen tap **English** |
| 🧠 [`Qwen3.5-0.8B-Q4_K_M.gguf`](https://huggingface.co/unsloth/Qwen3.5-0.8B-GGUF/resolve/main/Qwen3.5-0.8B-Q4_K_M.gguf) | The **AI** that answers on your phone, no internet (508 MB) | Download → in Oracle: **System → Import GGUF** → pick the file → **AI** tab → Activate |
| 🖨️ [`Oracle-Print-EN.pdf`](https://github.com/caiorlm/oracle-os/releases/latest/download/Oracle-Print-EN.pdf) | All the guides on paper (A4), in priority order | Print it **now**, keep it in a plastic bag, in 2 places |

> 🧠 The model downloads from **Hugging Face** (the same official file, SHA-256 `bd258782e35f7f45…`, checked against our `SHA256SUMS.txt`).

> 💡 **Paper needs no battery.** Print at least guides 1–3: first aid, water and the 50-year plan.

---

## 🧭 What's inside — and what each part does

```
                         ┌───────────────────────────────┐
                         │          ORACLE OS            │
                         │  (everything inside the phone)│
                         └───────────────┬───────────────┘
     ┌──────────────┬──────────────┬─────┴────────┬──────────────┬──────────────┐
     ▼              ▼              ▼              ▼              ▼              ▼
 ┌────────┐   ┌──────────┐   ┌──────────┐   ┌──────────┐   ┌──────────┐   ┌──────────┐
 │ ⌂ HOME │   │ ◇  AI    │   │ ⌖  MAP   │   │ ▤LIBRARY │   │ ▶  GAME  │   │ ⚙ SYSTEM │
 └────┬───┘   └────┬─────┘   └────┬─────┘   └────┬─────┘   └────┬─────┘   └────┬─────┘
  status panel,  answers        offline map    guides and     GENESIS       power,
  EMERGENCY,     questions      + GPS +        manuals in a   (farm,        printing,
  plants,        citing the     compass +      tree: health,  companion,    AI models,
  compass,       library        useful places  water, crafts… lineage)      language
  radio
```

| Icon | Part | What it does | Needs internet? |
|:-:|---|---|:-:|
| ⚠ | **Emergency** | Big button on Home: dialer (112/999/911), SMS with your coordinates, FM radio | ❌ |
| ◇ | **Local AI** | Ask questions ("how do I purify water?") — the AI answers on the phone and shows **which guide** the answer came from | ❌ |
| ▤ | **Library** | A tree: *Health · Survival · Water · Crafts · Navigation · Spirit · Society · Rebuilding*. Opens PDFs and guides even without AI | ❌ |
| ⌖ | **Map** | Offline map, your GPS position, useful places (hospitals, shelters, water) and routes | ❌ * |
| ⊕ | **Compass** | True north, follow a bearing, calibration warning | ❌ |
| ✿ | **Plants** | Photograph a plant → likely name + an article to confirm (never eat anything based on the app alone) | ❌ |
| ⚡ | **Power** | Extreme saving: black screen, minimum brightness, AI and GPS off, tips to last for weeks | ❌ |
| ⎙ | **Print** | The vital guides and manuals as A4 PDFs, ready to print | ❌ |
| ▶ | **Game** | GENESIS — to pass the time, ages 5 and up | ❌ |
| 🎬 | **Intro** | A PS1-style 3D animation on launch (with signal it always plays; without signal only once) | ❌ |

\* *The detailed map and the big encyclopedias (Wikipedia, medicine, iFixit…) are packs of several GB: see "Large content" below.*

### 📚 The 71 built-in guides (EN + PT)

```
 🩹 First aid               💧 Drinking water          📋 The 50-year plan
 🔥 Fire                    🏠 Blackout, cold, shelter 🍲 Cooking without power
 🥫 Food preservation       🧼 Hygiene with little water ☢️ War and attacks
 🚑 Search and rescue       🤱 Childbirth & med. plants 🌿 Wild plants
 🎣 Fishing                 🪤 Hunting and trapping    🌾 Seeds and grains
 🐐 Animals and vet care    🧱 Natural building        ☀️ Off-grid energy
 ⚗️ Basic chemistry         🔨 Smithing/pottery/carpentry 🧵 Textiles and leather
 🪢 Ropes and knots         🧭 Navigation              🌊 Rivers, lakes and sea
 📻 Comms without power     📡 Radio                   🌦️ Weather and calendar
 🤝 Community & education   🛡️ Protecting your family  🧠 Mental health
 🤸 Stretching and pain     🥋 Self-defence            🧘 Yoga · Meditation · Chakras
```

---

## 🎮 GENESIS — Legacy of Life

```
   ┌─────────────────────────────────────────┐
   │ Day 3 · 14:30 · Spring · clear          │
   │ LIFE ████████  FOOD █████  WATER ██████ │
   │                                         │
   │   🏠        ┌┬┬┬┬┬┬┬┬┬┐       ≈≈≈≈       │
   │   🪣  🧍 🐾  │🌱🌱🥕🥕🥬│       ≈≈🌉≈ 🌲🌲   │
   │            └┴┴┴┴┴┴┴┴┴┘       ≈≈≈≈ 🌲🌲🌲  │
   │                       👵 Grandma Rosa    │
   │   [◀][▲][▼][▶]                  (B) (A)  │
   └─────────────────────────────────────────┘
```

An **original**, 100% offline game inspired by classic farming and virtual-pet games:

- 🧍 **Create your character** — the look is generated from a **unique ID (SHA-256 + 256 random bits)**: nobody has the same one.
- 🐾 **Look after your companion** — food, water, happiness, energy, hygiene and health.
- 🌱 **Farm** — 8 crops (lettuce, carrot, potato, corn, bean, tomato, pumpkin, strawberry): dig, plant, water, harvest.
- ⏰ **Time always runs** — 1 game hour = 6 real minutes; 1 real day = 10 game days. With the phone closed, crops keep growing and your character eats and drinks from the bag.
- 🥚 **Lineage** — on day 100 the family egg appears; 10% of everything you collect goes to it; descendants carry the story on.
- 👶 **Ages 5–10 mode** — big buttons, little text, simple alerts ("Your companion is thirsty! GIVE WATER").

**Controls:** arrows = walk · **A** = act (dig, plant, water, harvest, talk) · **B** = menu.

---

## 🗂️ How the project is organised (for developers)

```
oracle-os/
├── app/                    ← Android app (Kotlin + Jetpack Compose)
│   └── src/main/
│       ├── java/…/feature/ ← one folder per screen: chat, maps, knowledge, plants, intro, game, print…
│       └── assets/guias/   ← the 71 guides shipped inside the APK
├── core/                   ← rules, contracts, power and AI policies
├── knowledge/              ← document database + search (SQLite FTS5)
├── inference/              ← local AI (llama.cpp, GGUF models)
├── genesis/                ← 🎮 the game (Godot 4.7, GDScript)
│   ├── autoload/Game.gd    ←   state, clock, simulation, saving
│   ├── core/               ←   maths, identity/genome, sprites and tiles generated in code
│   ├── ui/ world/          ←   screens, touch controls, the 64×64 valley
│   └── tests/              ←   559 automated tests + an automated playthrough
├── companion/
│   ├── library-builder/    ← source catalogues, downloader, signed packs, guides (.md)
│   └── i18n/               ← PT/EN interface translations
├── scripts/                ← automation: build, download, install over USB
└── docs/                   ← architecture, permissions, tests, pack format
```

| I want to… | Where |
|---|---|
| Build Oracle | [docs/DESENVOLVIMENTO.md](docs/DESENVOLVIMENTO.md) — `./gradlew :app:assembleDebug` (JDK 17, Android SDK 35, NDK 27) |
| Open the game in Godot | Godot **4.7.2** → *Import* → `genesis/project.godot` |
| Run the game tests | `godot --headless --path genesis --script res://tests/run_tests.gd` |
| Swap the AI model | Any llama.cpp-compatible GGUF → **System → Models / Import GGUF** |
| Write or edit a guide | `companion/library-builder/guias/*.md` (plain Markdown; `*-en.md` are the English ones) |
| Build the print PDFs | `python3 companion/library-builder/build_print_pack.py` |

### 📦 Large content (not on GitHub)

The offline encyclopedias (Wikipedia, medicine, iFixit, Wikibooks…), the detailed map and third-party manuals add up to **more than 70 GB**, and some may not be redistributed. So they are **not** here: the scripts in `companion/library-builder/` (`fetch.py` + the `survival-catalog*.json` catalogues) download them **from the original sources**, check SHA-256 and build signed packs (Ed25519) that the app verifies before use.

```
 original sources ──fetch.py──▶ downloads/ ──build_knowledge_pack.py──▶ signed pack ──USB──▶ 📱
 (Kiwix, Gutenberg,            (SHA-256)                               (Ed25519)
  WHO, MSF, FAO…)
```

---

## ⚖️ Licences and warnings

- **Code** of Oracle OS and GENESIS: **[GPL-3.0](LICENSE)** — use, study, change and share it; modified versions you distribute must stay open.
- **Oracle guides** (`guias/*.md`): GPL-3.0, like the rest of the project.
- **Qwen 3.5 model**: Apache-2.0 (Qwen team / Alibaba Cloud).
- **Third-party content** keeps its original licence (recorded in each catalogue).
- ⚠️ **The guides do not replace training or professionals.** In an emergency, call local services (112 / 999 / 911) if they exist. Never eat a plant just because the app identified it.
