# Hi, I'm Dallin

I'm a computer science student at BYU (machine learning emphasis, graduating May 2027). I like building things people actually use, and most of the projects below started as something I wanted for myself.

Right now I'm building **Argus**, a stove-safety startup, and doing ML research at BYU on computer vision and LLM evaluation.

---

## Projects

Most of these are in private repos. I'm happy to walk through any of the code.

### Argus

Stove safety for older adults, and a startup I'm building with friends. Argus is a smart plug for the stove that turns it off automatically after a set time and alerts you when it's been left on. It also tracks usage, so families can worry less about a parent who lives alone. The app pairs with the plug over Bluetooth and controls it on the local network or through the cloud.

`Flutter` `Bluetooth LE` `Shelly local + cloud APIs` `ESP32` `Raspberry Pi`

### Spruce

**1st place, BYU Homecoming Hackathon**

Spruce helps you keep track of the people you meet. After a conversation, you record a quick voice recap. Spruce transcribes it, drafts a contact with notes, and adds that person to your network, where you can search it later ("who do I know in biotech?") and see how people connect. It was a team project, and I built most of it: the Flutter app, the API, and the transcription and search pipeline.

`Flutter` `FastAPI` `PostgreSQL + pgvector` `Gemini` `Render`

[Live app](http://spruce.my) · [Code](https://github.com/wwwillott/cs-homecoming-hackathon)

<p align="center"><img src="assets/spruce.png" width="210" alt="Spruce sign-in screen"></p>

### Gospel Library 2.0

A scripture reader for web, iOS, and Android. It covers the basics of the Gospel Library app and adds what I kept wishing it had: side-by-side compare across books and Bible translations, search by meaning instead of exact wording, and highlights and notes that sync across devices.

`Flutter` `Firebase` `OpenAI embeddings`

[Live app](https://gosepl-library.web.app)

<p align="center"><img src="assets/gospel-library.png" width="420" alt="Gospel Library 2.0 library and reader screens"></p>

### Budget

A personal finance dashboard that runs on your own computer. It pulls transactions from your banks through Plaid or imports bank export files. It categorizes everything and shows spending pace, budgets, savings goals, and net worth. Your data lives in a local database, not someone else's server.

`Python` `FastAPI` `SQLite` `Plaid`

<p align="center"><img src="assets/budget.png" width="800" alt="Budget dashboard with demo data"></p>

### Sib-journal

A voice-first journal. You talk for a minute, and it transcribes the recording, cleans it up into a readable entry with a title and mood, and makes your entries searchable by meaning ("times I felt overwhelmed"). Entries are stored on your device.

`Flutter` `Riverpod` `Whisper` `OpenAI embeddings`

[Live app](https://dallinmj.github.io/Sib-journal/)

<p align="center"><img src="assets/sib-journal.png" width="420" alt="Sib-journal feed and collage views"></p>

### Focus Blocker

An Android app that keeps me off YouTube. It runs a local DNS-only VPN that answers lookups for blocked sites with NXDOMAIN and leaves all other traffic alone. A friend holds a rotating authenticator code, and I need that code to take a break or unblock a site. Breaks end on their own after 15 minutes.

`Kotlin` `Jetpack Compose` `Android VpnService` `TOTP`

### ML Research Trends

How fast are different areas of ML research growing? We pulled papers from Semantic Scholar on transformers, RAG, chain-of-thought reasoning, and vision-language models. We embedded the abstracts with Qwen3-Embedding-4B and built a Python package and Streamlit app to explore the results.

`Python` `Semantic Scholar API` `Qwen3 embeddings` `UMAP` `Streamlit`

[Project site](https://dallinmj.github.io/ml_research_trends/) · [Code](https://github.com/dallinmj/ml_research_trends)

<p align="center"><img src="assets/ml-research-trends.png" width="800" alt="UMAP of transformer paper abstracts colored by year"></p>

### Smaller projects

- **[Scripture Memorizer](https://github.com/dallinmj/scripture_memorizer):** hides more and more of a verse until you can say it from memory. Plain HTML, CSS, and JavaScript.
- **[Chess](https://github.com/dallinmj/chess):** a multiplayer chess server and terminal client in Java with HTTP, WebSockets, and MySQL, built for BYU CS 240.
- **[NFL Play Predictor](https://github.com/rkgreathouse/NFL_Play_Predictor):** a group project predicting run vs. pass from game situation, using ten seasons of play-by-play data.
- **[Multi-modal Education AI](https://github.com/BYU-PCCL/multi-modal-education-ai):** research code from BYU's PCCL lab that turns a lesson prompt into a Manim math animation.

---

## Experience

- **Research Assistant**, BYU Computer Vision & Record Linking Lab: computer vision pipelines that read handwritten historical census records for FamilySearch
- **Research Assistant**, BYU Faith Benchmark: benchmarks for how AI models discuss and represent different religions
- **AI & Software Engineer**, Red Compass Health: an AI charting pipeline that drafts SOAP notes and treatment plans, with HIPAA-compliant storage and RAG over medical documentation
- **Software Engineer**, White Pine Financial: Python automation for investment management workflows

**Tools I use most:** Python, PyTorch, Dart/Flutter, Kotlin, Java, JavaScript, SQL, FastAPI, Firebase
