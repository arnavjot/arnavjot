### Hi there! <img src="https://emojis.slackmojis.com/emojis/images/1647437725/56241/pikawave.gif" width="30"/>

I'm [**Arnavjot**](https://arnavjot.github.io/portfolio/), a software engineer.

I currently work as a software engineer at [**Hindustan Times**](https://www.hindustantimes.com/), where I build the Live Hindustan app across Android and iOS. It's used by 200K+ people a day.

I like making apps feel fast. I've cut the app's launch time from 6s to 2s, built a shared video player for the whole app, and shipped features from idea to production. Most of my work is in Java and Kotlin, with a lot of API integration, app architecture and performance.

Outside of work, I draw [sketches and doodles](https://arnavjot.github.io/portfolio/#artist). In my spare time I build backends in Java and Python, and I measure them properly: load tests, failure drills and real-phone benchmarks.

#### Projects
- [**Glimpse**](https://github.com/arnavjot/glimpse): a short-video app, Java end to end. A swipe feed with one shared video player that preloads the next clips, so they start in 196 ms instead of 290 ms on a real phone, plus a Spring Boot backend with direct-to-storage uploads, an ffmpeg worker, a "For You" ranking tested against newest-first, and rate limits. It held about 1,100 requests a second with p99 under 12 ms, and failure drills (offline, killed mid-upload, Redis and Postgres down) lost no events.
  *Java · Android · Media3 · Spring Boot · PostgreSQL · Redis · ffmpeg · k6*
- [**url-shortener**](https://github.com/arnavjot/url-shortener): a full-stack URL shortener with rate limiting and click analytics. Redirects are served from a Redis cache, and every click is counted exactly once, even when a worker crashes. It handles 500 requests a second with zero failures, and keeps working when Redis, Postgres or a worker goes down.
  *FastAPI · PostgreSQL · Redis · React · Prometheus · Grafana · k6*
- [**DocRetrieve**](https://github.com/arnavjot/document-retrieval-system): ask questions about your PDFs and get answers that cite the file and page. It removes personal data before anything reaches the model, blocks prompt-injection attempts, and measures its own retrieval quality.
  *FastAPI · LangChain · ChromaDB · Gemini · React*
- [**LeetLog**](https://github.com/arnavjot/leetlog): a Chrome extension that lets you write notes on any LeetCode problem and commit them straight to your own GitHub repo.

#### Let's connect!
[<img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-%230E76A8.svg?&style=for-the-badge&logo=LinkedIn&logoColor=white" />](https://linkedin.com/in/arnavjotkaur)
[<img alt="LeetCode" src="https://img.shields.io/badge/LeetCode-FFA116.svg?&style=for-the-badge&logo=leetcode&logoColor=black" />](https://leetcode.com/arnavjot)
[<img alt="Instagram" src="https://img.shields.io/badge/Instagram-%23E4405F.svg?&style=for-the-badge&logo=Instagram&logoColor=white" />](https://instagram.com/arnavjotkaur)
