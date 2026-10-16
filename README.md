<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2E9EF7&height=220&section=header&text=Vicky%20Kumar&fontSize=62&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=I%20turn%20chai%20%E2%98%95%20into%20APIs%20%E2%9A%A1&descAlignY=58&descSize=20" width="100%"/>

<a href="https://github.com/Vicky7632">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=900&color=2E9EF7&center=true&vCenter=true&width=720&lines=%24+whoami+%E2%86%92+Backend+%2B+Full-Stack+Engineer;%24+cat+current_obsession.txt+%E2%86%92+LLM+gateways+%F0%9F%A4%96;%24+redis-cli+GET+coffee+%E2%86%92+(nil)+%E2%98%95;%24+docker+compose+up+--build+%F0%9F%90%B3;%24+git+commit+-m+%22it+works+on+my+machine%22+%F0%9F%98%8E" alt="Typing SVG" />
</a>

![Profile Views](https://komarev.com/ghpvc/?username=Vicky7632&color=2E9EF7&style=for-the-badge&label=VISITORS)
![Codeforces](https://img.shields.io/badge/Codeforces-Specialist_(max_1405)-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)
![AtCoder](https://img.shields.io/badge/AtCoder-7_kyu-222?style=for-the-badge)

</div>

---

## 🖥️ `~/vicky/about.sh`

```bash
$ ./about.sh

 ╭──────────────────────────────────────────────────────╮
 │  👋  Hey! I'm Vicky — B.Tech CSE '26, Rungta College │
 │  📍  Bengaluru, India                                │
 │  🔭  Building : ai-proxy-router (LLM gateway)        │
 │  🌱  Learning : distributed systems, k8s, system     │
 │                 design, and how to cache everything  │
 │  ⚔️  Weapon   : C++ for contests, Python for shipping│
 │  💬  Ask me   : DSA, FastAPI, MERN, GenAI, RAG       │
 │  ⚡  Fun fact : I mentor juniors in DSA and still    │
 │                 TLE on my own submissions sometimes  │
 ╰──────────────────────────────────────────────────────╯
```

---

## 🔥 Latest Drop — [AI Proxy Router](https://github.com/Vicky7632/ai-proxy-router)

> *One endpoint. Many LLMs. Zero wasted tokens.*  
> A self-hosted gateway that sits between your app and Groq / Gemini / OpenRouter, and refuses to pay twice for the same answer. 💸

### 🎬 The life of a request (told like a thriller)

```mermaid
flowchart LR
    A(["🧑‍💻 Your app:<br/>'explain recursion'"]) --> B["🛡️ Bouncer<br/>API key + rate limit"]
    B --> C{"⚡ Redis<br/>seen this exact question?"}
    C -- "YES 🎉" --> Z(["✅ Instant answer<br/>cost: ₹0"])
    C -- "no" --> D{"🧠 pgvector<br/>asked something similar?"}
    D -- "YES 🎉<br/>(≥ 0.90 similar)" --> Z
    D -- "no" --> E["🚦 Router<br/>pick a healthy provider"]
    E --> F["🤖 Groq"]
    E --> G["✨ Gemini"]
    E --> H["🌐 OpenRouter"]
    F --> I(["📝 Answer + save to both caches"])
    G --> I
    H --> I
```

### 🧰 Superpowers

| 🦸 Power | 📖 Translation |
|---|---|
| 🧠 **Semantic cache** | "What's recursion?" and "explain recursion" → same answer, one LLM call |
| 🔐 **Paranoid by design** | API keys are shown *once*, stored as SHA-256 hashes. Even I can't read them |
| 🌊 **Streaming (SSE)** | Tokens flow live. Half-finished streams never poison the cache |
| 🚑 **Self-healing** | Provider down? Health tracking + cooldowns route around the pain |
| 📊 **Dashboard** | React 19 + Vite UI: keys, playground, provider health, cache hit-rate |
| ☸️ **Ships like a pro** | Docker Compose locally, Kubernetes manifests on Docker Desktop |

`Python 3.12` `FastAPI` `PostgreSQL + pgvector` `Redis` `React 19` `Vite` `Docker` `Kubernetes`

[📖 Architecture](https://github.com/Vicky7632/ai-proxy-router/blob/main/docs/ARCHITECTURE.md) · [📡 API Docs](https://github.com/Vicky7632/ai-proxy-router/blob/main/docs/API.md) · [⭐ Star it](https://github.com/Vicky7632/ai-proxy-router)

---

## 🗺️ `git log --oneline --graph` (my journey)

```text
* 2026  🚀  ai-proxy-router       → LLM gateway with 2-layer caching
* 2026  🧠  LectureIQ             → lectures in, summaries out
* Dec'25 💼  Veridia internship   → MERN Stack Developer
* 2025  💻  CodeGurukul           → coding platform + AI evaluation
* Sep'24 🌱  Digi Coders          → Full Stack Development Trainee
* 2022  🎓  git init              → B.Tech CSE, Rungta College
```

---

## 🧪 Other Experiments

| | Project | Vibe |
|---|---|---|
| 🧠 | [**LectureIQ**](https://github.com/Vicky7632/LectureIQ) | AI summarizes your lectures so you can pretend you paid attention (MERN · OpenAI · WebSocket) |
| 💻 | [**CodeGurukul**](https://github.com/Vicky7632/CodeGurukul-With-Ai) | LeetCode-style platform with Judge0 + AI feedback (MERN · Redis · GenAI) |
| ⚛️ | [**ReactMajorProject**](https://github.com/Vicky7632/ReactMajorProject) | Where the React muscles were built |
| 🤖 | [**FirstAiChatBot**](https://github.com/Vicky7632/FirstAiChatBot) | The origin story of my GenAI arc |

---

## 🧩 Competitive Programming Stats

<div align="center">

![CF](https://img.shields.io/badge/Codeforces-900%2B_solved-1F8ACB?style=flat-square&logo=codeforces&logoColor=white)
![GFG](https://img.shields.io/badge/GeeksforGeeks-700%2B_solved_%7C_95%25_accuracy-2F8D46?style=flat-square&logo=geeksforgeeks&logoColor=white)
![Hackathons](https://img.shields.io/badge/Hackathons-3x_Finalist-FF6B6B?style=flat-square)
![Mentor](https://img.shields.io/badge/Mentoring-Juniors_in_DSA-8E75B2?style=flat-square)

</div>

---

## ⚙️ `skills.config.json`

<div align="center">

<img src="https://skillicons.dev/icons?i=py,cpp,js,ts,react,redux,tailwind,nodejs,express,fastapi,django,flask&perline=12" /><br/>
<img src="https://skillicons.dev/icons?i=postgres,mysql,redis,docker,kubernetes,aws,git,github,vite,linux,vscode&perline=12" />

</div>

```jsonc
{
  "backend":   ["FastAPI", "Node/Express", "Django", "Flask", "SQLAlchemy", "Alembic"],
  "data":      ["PostgreSQL", "pgvector", "Redis", "MySQL"],
  "genai":     ["LangChain", "RAG", "Embeddings", "Vector DBs", "AI Agents", "Gemini", "OpenAI"],
  "infra":     ["Docker", "Kubernetes", "AWS", "CI/CD"],
  "superpower": "turning vague ideas into running containers 🐳"
}
```

---

## 📊 Stats (flex zone 💪)

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Vicky7632&show_icons=true&theme=tokyonight&hide_border=true" />
<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=Vicky7632&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Vicky7632&layout=compact&theme=tokyonight&hide_border=true" />

<img src="https://github-profile-trophy.vercel.app/?username=Vicky7632&theme=tokyonight&no-frame=true&row=1&column=6" />

</div>

---

## 🤝 Let's Build Something

<div align="center">

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vicky-kumar-b390a1354/)
[![Twitter](https://img.shields.io/badge/-Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/VickyKumar4545)
[![GeeksforGeeks](https://img.shields.io/badge/-GeeksforGeeks-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://www.geeksforgeeks.org/profile/vicky45)
[![Codeforces](https://img.shields.io/badge/-Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/VickyKumar45)

```text
 Cache hit  ✅  you reached out, instant reply.
 Cache miss ❌  I'll still answer, just with extra chai ☕
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2E9EF7,50:203a43,100:0f2027&height=120&section=footer" width="100%"/>

</div>

