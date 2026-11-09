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
    <a href="https://naitikyadav.pages.dev"><img src="https://img.shields.io/badge/Portfolio-6366f1?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
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
- **Open Source**: Upstream contributor to **OpenSearch (Linux Foundation / AWS)**, **OneBusAway**, **Quepid**, and **Chorus Search**.
- **Environment**: Arch Linux power user with daily focus on Linux internals, shell scripting, and systems tooling.
- **Competitions**: Winner at **VibeCraft Hackathon** (engineered decentralized solutions on the QUAI Network).

---

### Technical Skills

<div align="center">

#### Systems & Languages
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=c,cpp,go,ts,js,bash&theme=dark" alt="Languages & Systems" />
</a>

<br/>

#### Backend, Databases & Runtimes
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,postgres,mysql,firebase&theme=dark" alt="Backend & Databases" />
</a>

<br/>

#### DevOps & Infrastructure
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=arch,linux,docker,git,githubactions,postman,cloudflare,cmake&theme=dark" alt="DevOps & Infrastructure" />
</a>

<br/>

#### Frontend & UI Architecture
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=react,tailwind,vite,html,css&theme=dark" alt="Frontend" />
</a>

</div>

---

### Open-Source Contributions

| # | Project | Contribution & Impact | PRs' Merged |
| :-: | :--- | :--- | :-: |
| **01** | **[OpenSearch Go SDK](https://github.com/opensearch-project/opensearch-go)** | Re-architected bulk indexing with worker-partitioned queues and deterministic `documentID` shard hashing.<br/>Eliminated goroutine write contention with lock-free atomic round-robin fallback for unkeyed records. | [`#950`](https://github.com/opensearch-project/opensearch-go/pull/950) |
| **02** | **[OneBusAway Watchdog](https://github.com/OneBusAway/watchdog)** | Fixed dropped server recovery attribution by preserving original failing server metadata tags during reconciliation.<br/>Purged dead `duplicateEligible` logic and resolved false-positive Sentry recovery reporting for shared identities. | [`#183`](https://github.com/OneBusAway/watchdog/pull/183) |
| **03** | **[Chorus OpenSearch](https://github.com/o19s/chorus-opensearch-edition)** | Implemented standalone Product Detail Page (`/product/:asin`) routing with direct OpenSearch middleware queries.<br/>Decoupled `CLICK_THROUGH` and conversion telemetry from cart actions, eliminating fabricated tracking events. | [`#192`](https://github.com/o19s/chorus-opensearch-edition/pull/192) |
| **04** | **[Chorus OpenSearch](https://github.com/o19s/chorus-opensearch-edition)** | Resolved cross-session cart desynchronization by replacing DOM mutation with an event-driven `cart_updated` bus.<br/>Upgraded Docker environment to Node 20 and established end-to-end automated Playwright CI verification suites. | [`#190`](https://github.com/o19s/chorus-opensearch-edition/pull/190) |
| **05** | **[Chorus OpenSearch](https://github.com/o19s/chorus-opensearch-edition)** | Enforced storage persistence for `client_id` and `session_id` to preserve user sessions across page reloads.<br/>Corrected schema field mappings for search queries and brand facet filters (`Brand.keyword` to `brand.keyword`). | [`#188`](https://github.com/o19s/chorus-opensearch-edition/pull/188) |
| **06** | **[Chorus OpenSearch](https://github.com/o19s/chorus-opensearch-edition)** | Fixed product card `undefined $` pricing and missing brand labels using defensive property guards.<br/>Corrected UBI analytics payload identifiers by mapping undefined `item.id` to valid `item.asin` tokens. | [`#186`](https://github.com/o19s/chorus-opensearch-edition/pull/186) |
| **07** | **[Chorus OpenSearch](https://github.com/o19s/chorus-opensearch-edition)** | Migrated React root mounting lifecycle to React 18 `createRoot` API to resolve console deprecation errors.<br/>Fixed uncontrolled input state warnings in `AlgoPicker` by initializing comparison configs to empty strings. | [`#184`](https://github.com/o19s/chorus-opensearch-edition/pull/184) |
| **08** | **[Quepid](https://github.com/o19s/quepid)** | Hardened Docker orchestration with service healthchecks to resolve Rails worker and MySQL startup race conditions.<br/>Added configurable host port overrides (`APP_PORT`) and type-coerced `SOLID_QUEUE_POLLING` float parsing. | [`#1726`](https://github.com/o19s/quepid/pull/1726) |
| **09** | **[Meshery](https://github.com/meshery/meshery)** | Contributed community attendance verification and developer introduction to the CNCF Meshery repository.<br/>Adhered to CNCF Developer Certificate of Origin (DCO) commit sign-off and contribution standards. | [`#20145`](https://github.com/meshery/meshery/pull/20145) |
| **10** | **[OpenSearch Specs](https://github.com/opensearch-project/opensearch-api-specification)** | Prevented runtime deserialization crashes across multi-language SDKs by relaxing required token frequency constraints.<br/>Preserved backward compatibility across client code generators for OpenSearch analyzer token objects. | [`#1229`](https://github.com/opensearch-project/opensearch-api-specification/pull/1229) |

---

### Featured Projects

#### Doodle.io &mdash; Collaborative Canvas Multiplayer Game
<p>
  <a href="https://github.com/yanaix10/Doodle.io" title="GitHub Repository"><img src="https://img.shields.io/badge/GitHub-0d1117?style=flat-square&logo=github&logoColor=white" height="20" alt="GitHub" /></a>
  <a href="https://doodle-io-lake.vercel.app/" title="Live Demo"><img src="https://img.shields.io/badge/Live_Demo-10b981?style=flat-square&logo=vercel&logoColor=white" height="20" alt="Live Demo" /></a>
</p>

*React &bull; Node.js &bull; Socket.io &bull; Express &bull; HTML5 Canvas &bull; Tailwind CSS*

- **Low-Latency Vector Streaming**: Broadcasts high-frequency canvas drawing vectors over WebSockets with sub-50ms latency across 10+ concurrent multiplayer sessions.
- **Intelligent Guess Matching**: Constructed proximity guess validation using Levenshtein distance algorithms (80% similarity threshold) for typo-tolerant guess evaluation.
- **Multiplayer State Management**: Managed in-memory game room lobbies, round countdown timers, and live leaderboard calculations.

<br/>

#### hey &mdash; End-to-End Encrypted Terminal Chat & Daemon
<p>
  <a href="https://github.com/yanaix10/hey" title="GitHub Repository"><img src="https://img.shields.io/badge/GitHub-0d1117?style=flat-square&logo=github&logoColor=white" height="20" alt="GitHub" /></a>
</p>

*Go &bull; Bubble Tea &bull; TLS 1.3 &bull; AES-256-GCM &bull; Linux*

- **Decoupled Client-Daemon Architecture**: Developed an autonomous Go background daemon decoupled from an interactive Bubble Tea TUI client, integrated with a TLS 1.3 cloud relay for low-latency peer messaging across NAT boundaries.
- **Zero-Knowledge Cryptography**: Enforced end-to-end security using AES-256-GCM encryption with 96-bit nonces and ephemeral 6-digit OTP pairing, alongside local mDNS LAN discovery and a 16 kHz PCM voice pipeline.

<br/>

#### Mini-Redis &mdash; Concurrent Key-Value Store
<p>
  <a href="https://github.com/yanaix10/mini-redis" title="GitHub Repository"><img src="https://img.shields.io/badge/GitHub-0d1117?style=flat-square&logo=github&logoColor=white" height="20" alt="GitHub" /></a>
</p>

*C++ &bull; POSIX Sockets &bull; pthreads &bull; Reader-Writer Locks &bull; CMake*

- **High-Concurrency Core**: Built a non-blocking TCP key-value server from scratch in C++ using POSIX sockets and a pre-allocated thread pool to eliminate thread-creation overhead under high volume.
- **Granular Locking & $O(1)$ Eviction**: Integrated reader-writer locks (`pthread_rwlock`) to maximize concurrent read throughput paired with an $\mathcal{O}(1)$ LRU memory cache.
- **Deterministic Durability**: Implemented an Append-Only File (AOF) persistence logging engine with state replay crash recovery and a custom RESP command parser.

<br/>

#### SkillSphere &mdash; Real-Time Coding Arena
<p>
  <a href="https://github.com/yanaix10/Skill-Sphere-" title="GitHub Repository"><img src="https://img.shields.io/badge/GitHub-0d1117?style=flat-square&logo=github&logoColor=white" height="20" alt="GitHub" /></a>
</p>

*React &bull; Node.js &bull; Socket.io &bull; Monaco Editor &bull; MongoDB &bull; Tailwind CSS*

- **Event-Driven WebSocket Gateway**: Architected low-latency 1v1 matchmaking and editor state synchronization over Socket.io, featuring automated heartbeat pinging and a 30-second disconnect recovery grace period.
- **Sandboxed Execution & Verdict Streaming**: Integrated Monaco Editor with a server-authoritative pluggable execution pipeline, running isolated multi-language test suites to stream real-time verdicts with sub-100ms latency.
- **Matchmaking & Stats Engine**: Engineered room-based matchmaking lobbies with Elo rating calculations, synchronized match timers, and MongoDB duel tracking.

---

### GitHub Analytics

<div align="center">
  <p align="center">
    <a href="https://github.com/pulls?q=is%3Apr+is%3Amerged+author%3Ayanaix10">
      <img src="https://img.shields.io/github/issues-search?query=is%3Apr+is%3Amerged+author%3Ayanaix10&label=Total%20PRs%20Merged&style=flat-square&color=8957e5&logo=github&logoColor=white" alt="Total PRs Merged" />
    </a>
  </p>
  <img src="https://github-readme-stats-fast.vercel.app/api?username=yanaix10&show=prs_merged&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" height="165" />
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs?username=yanaix10&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165" />
</div>
