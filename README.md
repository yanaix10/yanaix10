<div align="center">
  <h1 align="center" style="font-weight: 700; font-size: 2.25rem; letter-spacing: -0.02em;">
    Naitik Yadav
  </h1>

  <p align="center">
    <b>Backend & Systems Engineer &bull; Open-Source Contributor &bull; Full-Stack Developer</b><br>
    <i>3rd Year B.Tech Computer Science & Engineering &mdash; SRM University AP</i>
  </p>

  <p align="center">
    <a href="https://github.com/yanaix10"><img src="https://img.shields.io/badge/GitHub-0d1117?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
    <a href="https://linkedin.com/in/naitikyadav15"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="https://leetcode.com/u/naitik15/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
    <a href="https://x.com/naitik15dev"><img src="https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white" alt="X" /></a>
    <a href="mailto:naitik.yadav641@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  </p>

  <p align="center">
    <img src="https://komarev.com/ghpvc/?username=yanaix10&label=PROFILE+VIEWS&color=4f46e5&style=flat-square" alt="Profile Views" />
  </p>
</div>

---

### About

- **Undergraduate**: 3rd-year B.Tech in Computer Science & Engineering at **SRM University AP** *(CGPA: 8.40 / 10.0)*.
- **Engineering Focus**: Architecting scalable backend systems, high-concurrency multi-threaded runtimes, distributed caching, and low-latency network protocols.
- **Open Source**: Upstream contributor to **OpenSearch (Linux Foundation / AWS)**, **Quepid**, and **Chorus Search**.
- **Environment**: Arch Linux power user with daily focus on Linux internals, shell scripting, and systems tooling.
- **Competitions**: Winner at **VibeCraft Hackathon** (engineered decentralized solutions on the QUAI Network).

---

### Technical Skills

<div align="center">

#### Systems & Languages
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=c,cpp,go,py,ts,js,bash&theme=dark" alt="Languages & Systems" />
</a>

<br/>

#### Backend, Databases & Runtimes
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=fastapi,nodejs,express,mongodb,postgres,mysql,redis,firebase&theme=dark" alt="Backend & Databases" />
</a>

<br/>

#### DevOps & Infrastructure
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=arch,linux,docker,git,github,postman,cmake&theme=dark" alt="DevOps & Infrastructure" />
</a>

<br/>

#### Frontend & UI Architecture
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=react,tailwind,vite,html,css&theme=dark" alt="Frontend" />
</a>

</div>

---

### Open-Source Contributions

- **[OpenSearch Go SDK](https://github.com/opensearch-project/opensearch-go/pull/950)** &bull; *Merged into Upstream*
  - Re-architected the `opensearchutil` bulk indexing pipeline by replacing a single channel with worker-partitioned queues.
  - Implemented deterministic `documentID` shard hashing (`hashValue % NumWorkers`) to eliminate write contention and race conditions during high-throughput ingestion.
  - Engineered a lock-free round-robin fallback distribution for unkeyed records to maximize multi-core CPU utilization.

- **[Chorus OpenSearch & Elasticsearch Edition](https://github.com/o19s/chorus-opensearch-edition)**
  - Resolved telemetry drops in User Behavior Insights (UBI) tracking through persistent client-side session synchronization.
  - Modernized search diagnostic interfaces to React 18 and refactored deprecated protocol routing logic.

- **[Quepid](https://github.com/o19s/quepid)**
  - Contributed to container orchestration and isolated Docker networking for the test-driven search relevance evaluation suite.

---

### Featured Projects

#### VulnPulse &mdash; Distributed DAST Engine
<p>
  <a href="https://github.com/yanaix10/vulnscan" title="GitHub Repository"><img src="https://img.shields.io/badge/-%20-0d1117?style=flat-square&logo=github&logoColor=white" height="20" alt="GitHub" /></a>
  <a href="https://vulnpulse.vercel.app/" title="Live Demo"><img src="https://img.shields.io/badge/-%20-10b981?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHdpZHRoPScyNCcgaGVpZ2h0PScyNCcgdmlld0JveD0nMCAwIDI0IDI0JyBmaWxsPSdub25lJyBzdHJva2U9J3doaXRlJyBzdHJva2Utd2lkdGg9JzInIHN0cm9rZS1saW5lY2FwPSdyb3VuZCcgc3Ryb2tlLWxpbmVqb2luPSdyb3VuZCc+PGNpcmNsZSBjeD0nMTInIGN5PScxMicgcj0nMTAnLz48bGluZSB4MT0nMicgeTE9JzEyJyB4Mj0nMjInIHkyPScxMicvPjxwYXRoIGQ9J00xMiAyYTE1LjMgMTUuMyAwIDAgMSA0IDEwIDE1LjMgMTUuMyAwIDAgMS00IDEwIDE1LjMgMTUuMyAwIDAgMS00LTEwIDE1LjMgMTUuMyAwIDAgMSA0LTEweicvPjwvc3ZnPg==" height="20" alt="Live Demo" /></a>
</p>

*FastAPI &bull; Python &bull; Playwright &bull; React 19 &bull; SQLAlchemy*

- **Autonomous Crawler & Fuzzer**: Dynamic Application Security Testing (DAST) engine pairing a headless browser crawler with concurrent heuristic fuzzers for multi-target security auditing.
- **Vulnerability Detection**: Features 10+ modular OWASP checks with automated Proof-of-Concept (PoC) generation and CVSS v3.1 risk scoring.
- **Operations Dashboard**: Real-time SOC command dashboard streaming live scan telemetry, vulnerability classifications, and severity breakdowns.

<br/>

#### Mini-Redis &mdash; Concurrent Key-Value Store
<p>
  <a href="https://github.com/yanaix10/mini-redis" title="GitHub Repository"><img src="https://img.shields.io/badge/-%20-0d1117?style=flat-square&logo=github&logoColor=white" height="20" alt="GitHub" /></a>
</p>

*C++ &bull; POSIX Threads &bull; Reader-Writer Locks &bull; Sockets &bull; CMake*

- **Multi-Threaded Architecture**: Thread-safe in-memory database built from scratch using low-level POSIX sockets and a custom thread pool to handle concurrent TCP client connections.
- **Concurrency & Locking**: Integrated granular reader-writer locks (`pthread_rwlock`) to maximize concurrent read throughput while ensuring mutually exclusive writes.
- **Persistence & Eviction**: Implemented an Append-Only File (AOF) logging engine with replay crash recovery, custom RESP-like command parsing, and LRU cache eviction.

<br/>

#### SkillSphere &mdash; Real-Time Coding Arena
<p>
  <a href="https://github.com/yanaix10/Skill-Sphere-" title="GitHub Repository"><img src="https://img.shields.io/badge/-%20-0d1117?style=flat-square&logo=github&logoColor=white" height="20" alt="GitHub" /></a>
  <a href="https://xskillsphere.vercel.app/" title="Live Demo (In Progress)"><img src="https://img.shields.io/badge/-%20-dc2626?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHdpZHRoPScyNCcgaGVpZ2h0PScyNCcgdmlld0JveD0nMCAwIDI0IDI0JyBmaWxsPSdub25lJyBzdHJva2U9J3doaXRlJyBzdHJva2Utd2lkdGg9JzInIHN0cm9rZS1saW5lY2FwPSdyb3VuZCcgc3Ryb2tlLWxpbmVqb2luPSdyb3VuZCc+PGNpcmNsZSBjeD0nMTInIGN5PScxMicgcj0nMTAnLz48bGluZSB4MT0nMicgeTE9JzEyJyB4Mj0nMjInIHkyPScxMicvPjxwYXRoIGQ9J00xMiAyYTE1LjMgMTUuMyAwIDAgMSA0IDEwIDE1LjMgMTUuMyAwIDAgMS00IDEwIDE1LjMgMTUuMyAwIDAgMS00LTEwIDE1LjMgMTUuMyAwIDAgMSA0LTEweicvPjwvc3ZnPg==" height="20" alt="Live Demo" /></a>
  <a href="https://xskillsphere.vercel.app/"><img src="https://img.shields.io/badge/In_Progress-dc2626?style=flat-square" height="20" alt="In Progress" /></a>
</p>

*React &bull; Node.js &bull; Socket.io &bull; Express &bull; MongoDB &bull; Tailwind CSS*

- **Real-Time Synchronization**: 1v1 competitive arena with sub-100ms bidirectional event synchronization over WebSockets for code edits and matchmaking state.
- **Sandboxed Execution**: Integrated Monaco Editor with Piston sandboxed execution API for live multi-language compilation against custom test suites.
- **Matchmaking Engine**: Engineered room-based matchmaking lobbies, live match timers, and persistent rating profiles in MongoDB.

<br/>

#### Doodle.io &mdash; Collaborative Canvas Multiplayer Game
<p>
  <a href="https://github.com/yanaix10/Doodle.io" title="GitHub Repository"><img src="https://img.shields.io/badge/-%20-0d1117?style=flat-square&logo=github&logoColor=white" height="20" alt="GitHub" /></a>
  <a href="https://doodle-io-lake.vercel.app/" title="Live Demo"><img src="https://img.shields.io/badge/-%20-10b981?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHdpZHRoPScyNCcgaGVpZ2h0PScyNCcgdmlld0JveD0nMCAwIDI0IDI0JyBmaWxsPSdub25lJyBzdHJva2U9J3doaXRlJyBzdHJva2Utd2lkdGg9JzInIHN0cm9rZS1saW5lY2FwPSdyb3VuZCcgc3Ryb2tlLWxpbmVqb2luPSdyb3VuZCc+PGNpcmNsZSBjeD0nMTInIGN5PScxMicgcj0nMTAnLz48bGluZSB4MT0nMicgeTE9JzEyJyB4Mj0nMjInIHkyPScxMicvPjxwYXRoIGQ9J00xMiAyYTE1LjMgMTUuMyAwIDAgMSA0IDEwIDE1LjMgMTUuMyAwIDAgMS00IDEwIDE1LjMgMTUuMyAwIDAgMS00LTEwIDE1LjMgMTUuMyAwIDAgMSA0LTEweicvPjwvc3ZnPg==" height="20" alt="Live Demo" /></a>
</p>

*React &bull; Node.js &bull; Socket.io &bull; Express &bull; HTML5 Canvas &bull; Tailwind CSS*

- **Low-Latency Streaming**: Broadcasts high-frequency canvas drawing vectors with sub-50ms latency across multi-user game rooms.
- **Intelligent Guess Matching**: Implemented proximity guess validation using Levenshtein distance algorithms to award partial and exact match points.
- **Room Orchestration**: Automated DoodleBot practice lobbies with turn timers, word generation queues, and dynamic leaderboard calculation.

---

### GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api?username=yanaix10&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" height="165" />
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=yanaix10&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165" />
</div>
