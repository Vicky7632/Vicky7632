<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0f2027,50:203a43,100:2E9EF7&height=240&section=header&text=VICKY.EXE&fontSize=80&fontColor=ffffff&animation=twinkling&fontAlignY=40&desc=%E2%9A%94%EF%B8%8F%20Backend%20Artificer%20%7C%20Level%2022%20%7C%20Currently%20on%20the%20LLM%20Quest&descAlignY=65&descSize=18" width="100%"/>

<a href="https://github.com/Vicky7632">
  <img src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=14&pause=1000&color=2E9EF7&center=true&vCenter=true&width=760&height=40&lines=%3E+PLAYER+1+HAS+ENTERED+THE+REPO;%3E+LOADING+SKILLS...+FastAPI+%E2%9C%94+Redis+%E2%9C%94+K8s+%E2%9C%94;%3E+BOSS+DETECTED%3A+THE+LLM+BILL+%F0%9F%92%B8;%3E+PRESS+START+TO+SCROLL" alt="Typing SVG" />
</a>

![Visitors](https://komarev.com/ghpvc/?username=Vicky7632&color=2E9EF7&style=for-the-badge&label=PLAYERS+ONLINE)

</div>

---

## ðŸŽ® CHARACTER SELECT

```text
 â•”â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•—
 â•‘  ðŸ§™  PLAYER   : Vicky Kumar                               â•‘
 â•‘  ðŸ›¡ï¸  CLASS    : Backend Artificer  (sub-class: Full-Stack) â•‘
 â•‘  ðŸ°  GUILD    : Rungta College of Engg & Tech, Bhilai     â•‘
 â•‘  ðŸ—ºï¸  REGION   : Bengaluru, India                           â•‘
 â•‘  âš”ï¸  WEAPONS  : C++ (contests)  Â·  Python (shipping)       â•‘
 â•‘  ðŸ§ª  MAGIC    : Redis âš¡  PostgreSQL ðŸ˜  pgvector ðŸ§          â•‘
 â•‘  ðŸ³  MOUNT    : Docker  â†’  upgrading to Kubernetes â˜¸ï¸      â•‘
 â•‘  ðŸŽ¯  QUEST    : Make LLM APIs fast, cheap & reliable      â•‘
 â•‘  â˜•  FUEL     : Chai (potion of +10 focus)                 â•‘
 â•šâ•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•
```

### ðŸ… Achievements Unlocked

| Badge | Title | How |
|:-:|---|---|
| ðŸ¦ˆ | **Pull Shark** | Earned on GitHub by getting pull requests merged |
| ðŸŽ² | **YOLO** | Earned on GitHub by merging a PR without a review (very brave, very legal) |
| ðŸ¥‡ | **Hackathon Finalist Ã—3** | Three college competitions, three finals |
| ðŸ¥ˆ | **Codeforces Specialist** | Max rating **1405**, 900+ problems slain |
| ðŸ§™ | **Mentor** | Trains junior adventurers in DSA |

---

## âš”ï¸ MAIN QUEST: [AI Proxy Router](https://github.com/Vicky7632/ai-proxy-router)

> **Quest objective:** Build one gateway to rule all LLM providers, and stop paying twice for the same answer.  
> **Boss:** ðŸ‘¹ *The Token Bill*  
> **Reward:** âš¡ faster responses, ðŸ’¸ lower cost, ðŸ˜Œ peaceful sleep

### ðŸ—ºï¸ The Dungeon Map (every request must survive it)

```mermaid
flowchart TD
    S(["ðŸ§‘â€ðŸ’» Request enters the dungeon"]) --> G["ðŸ›¡ï¸ LEVEL 1: The Gatekeeper<br/>API key + rate limit + budget"]
    G --> R{"âš¡ LEVEL 2: Redis Vault<br/>exact answer already stored?"}
    R -- "ðŸ’Ž TREASURE FOUND" --> W(["ðŸ† Victory! Instant reply"])
    R -- "empty" --> P{"ðŸ§  LEVEL 3: pgvector Library<br/>similar question answered before?"}
    P -- "ðŸ’Ž TREASURE FOUND<br/>(similarity â‰¥ 0.90)" --> W
    P -- "empty" --> B["ðŸš¦ LEVEL 4: The Router<br/>picks a healthy provider"]
    B --> A1["ðŸ¤– Groq"]
    B --> A2["âœ¨ Gemini"]
    B --> A3["ðŸŒ OpenRouter"]
    A1 --> L(["ðŸ“ Loot saved to both caches<br/>for the next adventurer"])
    A2 --> L
    A3 --> L
```

### ðŸŽ’ Inventory (what this repo carries)

| Item | Effect |
|---|---|
| ðŸ§  **Semantic Cache Amulet** | "What is recursion?" â‰ˆ "explain recursion" â†’ one LLM call, not two |
| ðŸ” **Cloak of SHA-256** | API keys are shown once, stored only as hashes. Not even the dev can read them |
| ðŸŒŠ **Streaming Boots** | Live SSE tokens. Broken streams are never cached |
| ðŸš‘ **Healing Potion** | Provider health tracking + cooldown when a provider goes down |
| ðŸ“Š **Scrying Mirror** | React dashboard: keys, playground, provider health, cache hit-rate |
| â˜¸ï¸ **Dragon Mount** | Runs on Docker Compose and local Kubernetes |

`Python 3.12` `FastAPI` `PostgreSQL + pgvector` `Redis` `React 19` `Vite` `Docker` `Kubernetes`

[ðŸ“œ Architecture Scroll](https://github.com/Vicky7632/ai-proxy-router/blob/main/docs/ARCHITECTURE.md) Â· [ðŸ“¡ API Spellbook](https://github.com/Vicky7632/ai-proxy-router/blob/main/docs/API.md) Â· [â­ Give it a star](https://github.com/Vicky7632/ai-proxy-router)

---

## ðŸ§­ SIDE QUESTS

| ðŸ·ï¸ | Quest | Loot |
|:-:|---|---|
| ðŸ§  | [**LectureIQ**](https://github.com/Vicky7632/LectureIQ) | Turns long lectures into summaries *(MERN Â· OpenAI Â· WebSocket)* |
| ðŸ’» | [**CodeGurukul**](https://github.com/Vicky7632/CodeGurukul-With-Ai) | Coding arena with Judge0 + AI feedback *(MERN Â· Redis Â· GenAI)* |
| âš›ï¸ | [**ReactMajorProject**](https://github.com/Vicky7632/ReactMajorProject) | The training grounds for React skills |
| ðŸ¤– | [**FirstAiChatBot**](https://github.com/Vicky7632/FirstAiChatBot) | The tutorial level of my GenAI arc |

---

## ðŸ“œ QUEST LOG (the story so far)

```mermaid
timeline
    title Vicky's Adventure
    2022 : ðŸŽ“ Joined the guild : B.Tech CSE at Rungta College
    2024 : ðŸŒ± Digi Coders (Aug-Sep) : Full Stack Development Trainee
    2025 : ðŸ’» Built CodeGurukul : ðŸ’¼ Veridia internship (Nov-Dec) : MERN Stack Developer
    2026 : ðŸ§  Built LectureIQ : ðŸš€ Built ai-proxy-router : ðŸŽ¯ Graduating from the guild
```

---

## ðŸ‘¹ BOSS FIGHTS (Competitive Programming)

<div align="center">

![CF](https://img.shields.io/badge/âš”ï¸_Codeforces-Specialist_|_max_1405_|_900%2B_solved-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)
![AtCoder](https://img.shields.io/badge/ðŸ—¡ï¸_AtCoder-7_kyu-333?style=for-the-badge)
![GFG](https://img.shields.io/badge/ðŸ›¡ï¸_GeeksforGeeks-700%2B_solved_|_95%25_accuracy-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white)

</div>

---

## ðŸ§° SKILL TREE

<div align="center">

<img src="https://skillicons.dev/icons?i=py,cpp,js,ts,react,redux,tailwind,nodejs,express,fastapi,django,flask&perline=12" /><br/>
<img src="https://skillicons.dev/icons?i=postgres,mysql,redis,docker,kubernetes,aws,git,github,vite,linux,vscode&perline=12" />

</div>

```text
ðŸŒ³ SKILL TREE
 â”œâ”€â”€ âš”ï¸  Combat        â†’ C++, DSA, problem solving
 â”œâ”€â”€ ðŸ§™ Backend Magic  â†’ FastAPI Â· Node/Express Â· Django Â· Flask Â· SQLAlchemy
 â”œâ”€â”€ ðŸ§  Dark Arts (AI) â†’ LangChain Â· RAG Â· Embeddings Â· Vector DBs Â· AI Agents
 â”œâ”€â”€ ðŸ° Fortress       â†’ PostgreSQL Â· pgvector Â· Redis Â· MySQL
 â”œâ”€â”€ ðŸ³ Logistics      â†’ Docker Â· Kubernetes Â· AWS Â· CI/CD
 â””â”€â”€ ðŸŽ¨ Illusion       â†’ React Â· Redux Â· Tailwind Â· Vite Â· TypeScript
```

---

## ðŸ“ˆ PLAYER STATS

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Vicky7632&show_icons=true&theme=tokyonight&hide_border=true" />
<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=Vicky7632&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Vicky7632&layout=compact&theme=tokyonight&hide_border=true" />

<img src="https://github-profile-trophy.vercel.app/?username=Vicky7632&theme=tokyonight&no-frame=true&row=1&column=6" />

</div>

<!--
ðŸ OPTIONAL: Contribution Snake
Step 1: add .github/workflows/snake.yml to this repo (file given separately)
Step 2: Actions tab â†’ "Generate Snake" â†’ Run workflow (wait ~1 min)
Step 3: delete these comment markers (the opening and closing arrows) so the snake shows up

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Vicky7632/Vicky7632/output/github-snake-dark.svg" />
    <img alt="snake" src="https://raw.githubusercontent.com/Vicky7632/Vicky7632/output/github-snake.svg" />
  </picture>
</div>
-->

---

## ðŸ’¾ SAVE POINT & CONTACT

<div align="center">

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vicky-kumar-b390a1354/)
[![Twitter](https://img.shields.io/badge/-Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/VickyKumar4545)
[![GeeksforGeeks](https://img.shields.io/badge/-GeeksforGeeks-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://www.geeksforgeeks.org/profile/vicky45)
[![Codeforces](https://img.shields.io/badge/-Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/VickyKumar45)

```text
 â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
 â”‚   ðŸŽ®  GAME PAUSED                         â”‚
 â”‚                                          â”‚
 â”‚   [A] Hire me        [B] Collab on code  â”‚
 â”‚   [X] Talk DSA       [Y] Share chai â˜•    â”‚
 â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
```

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:2E9EF7,50:203a43,100:0f2027&height=120&section=footer" width="100%"/>

</div>
