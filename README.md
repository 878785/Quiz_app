<p align="center">
  <img src="https://img.shields.io/badge/✦-AI_Quizly_Advanced-6d5ce8?style=for-the-badge&labelColor=14182b" alt="AI Quizly Advanced"/>
</p>

<h1 align="center">Make learning <em>unforgettable</em>.</h1>

<p align="center">
  A polished, browser-based CS quiz app — difficulty levels, live timer,<br/>
  dark mode, keyboard shortcuts, streaks &amp; history.<br/>
  <strong>No backend. No signup. Just open and learn.</strong>
</p>

<p align="center">
  <a href="https://878785.github.io/Quiz_app/">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-Open_App-6d5ce8?style=for-the-badge&logo=github&logoColor=white&labelColor=1c2340" alt="Live Demo"/>
  </a>
  &nbsp;
  <a href="https://878785.github.io/Quiz_app/">
    <img src="https://img.shields.io/badge/▶_Try_Now-20c8bd?style=for-the-badge&labelColor=0d3d38" alt="Try Now"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/API-Open_Trivia_DB-20c8bd?style=flat-square" alt="OpenTDB"/>
  <img src="https://img.shields.io/badge/Theme-Dark_/_Light-8b7cf0?style=flat-square" alt="Theme"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="MIT"/>
</p>

---

<br/>

## 🌐 Live Demo

<table>
  <tr>
    <td align="center" width="100%">
      <br/>
      <a href="https://878785.github.io/Quiz_app/">
        <strong>👉 https://878785.github.io/Quiz_app/</strong>
      </a>
      <br/><br/>
      <code>Open → Pick subject → Start quiz → Learn</code>
      <br/><br/>
    </td>
  </tr>
</table>

<br/>

## ✨ Why Quizly feels different

Most quiz demos are plain forms. **Quizly Advanced** is built to feel like a real product.

<table>
<tr>
<td width="50%" valign="top">

### 🎯 Practice your way
- Subject chips for organisation  
- **Easy / Medium / Hard / Any**  
- **10 · 15 · 20** questions  
- **10 · 15 · 20** min timer  

</td>
<td width="50%" valign="top">

### ⌨️ Built for speed
- Keys `1–4` select answers  
- `Enter` / `→` next · `←` prev  
- `S` skip · `Esc` quit  
- Instant feedback + explanation  

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 Track what matters
- Total quizzes &amp; questions  
- Average + **best score**  
- **Daily streak** 🔥  
- Difficulty-wise breakdown  

</td>
<td width="50%" valign="top">

### 💎 Polish everywhere
- Glass UI + mesh gradients  
- **Dark / light** mode  
- Loading overlay + toasts  
- Full history modal  

</td>
</tr>
</table>

<br/>

## 🖼️ What you get

```
┌──────────────────────────────────────────────────────────────────┐
│                                                                  │
│   ✦ AI Quizly          Workspace / Dashboard                     │
│   ───────────                                                    │
│   ▦ Dashboard          ┌────────┐ ┌────────┐ ┌────────┐ ┌──────┐ │
│   ▤ Create Quiz        │ Quizzes│ │Answered│ │Average │ │ Best │ │
│   ◷ History            │   12   │ │  240   │ │  78%   │ │ 95%  │ │
│                        └────────┘ └────────┘ └────────┘ └──────┘ │
│   🌙 Dark mode                                                   │
│                        ┌─ Create a quiz ───────────────────────┐ │
│                        │  [Python] [Java] [JS] [DSA] ...       │ │
│                        │  Difficulty ▓ Any ░ Easy ░ Med ░ Hard │ │
│                        │  Questions  ░ 10  ░ 15  ▓ 20          │ │
│                        │  Timer      ░ 10m ░ 15m ▓ 20m         │ │
│                        │            [ Start quiz → ]           │ │
│                        └───────────────────────────────────────┘ │
│                                                                  │
└──────────────────────────────────────────────────────────────────┘
```

| Screen | Experience |
|--------|------------|
| **Dashboard** | Stats, streak, recent activity, subject launcher |
| **Quiz** | Progress bar, timer, live score, keyboard nav |
| **Results** | Score · % · answered + easy/medium/hard bars |
| **Review** | Every question listed — click to jump back |
| **History** | Full modal list with clear option |

<br/>

## ⌨️ Keyboard shortcuts

| Key | Action | Key | Action |
|:---:|--------|:---:|--------|
| `1` `2` `3` `4` | Select option A–D | `S` | Skip question |
| `Enter` / `→` | Next / Finish | `Esc` | Quit quiz |
| `←` | Previous question | | |

<br/>

## 🛠️ Tech stack

```text
┌─────────────┬────────────────────────────────────────────┐
│  Frontend   │  HTML5 · CSS3 · Vanilla JavaScript (ES6+)  │
│  Style      │  Custom properties · Glass · Dark theme    │
│  API        │  Open Trivia Database (opentdb.com)        │
│  Storage    │  localStorage (history, theme, streak)     │
│  Hosting    │  GitHub Pages                              │
│  Build      │  None — zero dependencies                  │
└─────────────┴────────────────────────────────────────────┘
```

<p align="center">
  <img src="https://img.shields.io/badge/Dependencies-0-success?style=for-the-badge" alt="Zero deps"/>
  <img src="https://img.shields.io/badge/Framework-None-lightgrey?style=for-the-badge" alt="No framework"/>
  <img src="https://img.shields.io/badge/Backend-None-lightgrey?style=for-the-badge" alt="No backend"/>
</p>

<br/>

## 📁 Project structure

```text
Quiz_app/
│
├── 📄 index.html      ← App shell, layout, modals
├── 🎨 style.css       ← Glass UI, dark mode, animations, responsive
├── ⚡ script.js       ← Quiz engine, API, storage, keyboard, UI
└── 📖 README.md       ← You are here
```

<br/>

## 🏁 Run locally

```bash
# 1. Clone
git clone https://github.com/878785/Quiz_app.git
cd Quiz_app

# 2. Serve (pick one)
python -m http.server 5500
#  or
npx serve .

# 3. Open
# http://localhost:5500
```

> Or just open `index.html` in a browser.  
> Internet is required for live questions from OpenTDB.

<br/>

## 🎮 How to use

```text
  ①  Open the live app
  ②  Pick a subject chip  (Python · Java · JS · DSA · …)
  ③  Set difficulty · question count · timer
  ④  Hit  Start quiz
  ⑤  Answer with mouse or keys  ·  skip if stuck
  ⑥  Finish → review → try again
```

Progress (history, streak, theme, last settings) is saved **only on this browser**.

<br/>

## 🔒 Privacy

| What | Where |
|------|--------|
| Questions | Fetched from **Open Trivia DB** only |
| History / streak / theme | **localStorage** on your device |
| Accounts / analytics | **None** |

No signup. No tracking baked in. Your data stays with you.

<br/>

## 🗺️ Roadmap

- [ ] Offline / curated packs per subject  
- [ ] Export results as PDF  
- [ ] Challenge a friend (shareable link)  
- [ ] Hindi UI toggle  
- [ ] Spaced repetition for wrong answers  
- [ ] Confetti on 90%+ scores  

Ideas and PRs are welcome.

<br/>

## 📜 License

**MIT** — use it, fork it, ship it.

---

<br/>

<p align="center">
  <strong>Built for curious minds</strong> ♥
  <br/><br/>
  <a href="https://878785.github.io/Quiz_app/">
    <img src="https://img.shields.io/badge/🚀_Open_Live_App-6d5ce8?style=for-the-badge&labelColor=14182b" alt="Open Live App"/>
  </a>
  <br/><br/>
  <code>HTML · CSS · JavaScript · OpenTDB</code>
  <br/><br/>
  <sub>© 2026 AI Quizly Advanced</sub>
</p>
