<h1 align="center">Hi, I am Cameron Scarpati 👋</h1>

<p align="center">
  <b>Incoming MSCF @ Carnegie Mellon · Ex-Morgan Stanley Equity Algorithms · Seeking Summer 2027 Quant Internships</b>
</p>

## About Me

I am a computer scientist and mathematician who comes at quantitative finance from the engineering side. Last summer I worked on an ultra-low-latency trading system at Morgan Stanley, and that work is a large part of why I am moving toward research and Carnegie Mellon. My strength today is fast, well-tested C++ and performance optimization, and I learn the finance by building. Starting Fall 2026 I will be a Master of Science in Computational Finance (MSCF) student at Carnegie Mellon, where the program fills in the finance for me, from stochastic calculus to fixed income.

I graduated from Vanderbilt University summa cum laude with a 4.0, majoring in Computer Science and Mathematics, and my undergraduate research earned a national Honorable Mention for the Computing Research Association Outstanding Undergraduate Researcher Award. I am looking for a Summer 2027 internship in quant research, systematic trading, or quant development.

### 🎯 Quick Facts

- 🎓 Incoming **MSCF** at **Carnegie Mellon University**, Tepper School of Business (Pittsburgh, PA); expected Dec 2027
- 🎓 **Vanderbilt University**, B.A. in Computer Science and Mathematics, minor in Data Science, summa cum laude, 4.0 GPA (May 2026)
- 💼 Ex-**Morgan Stanley** Equity Algorithms intern (Speedway Team)
- 🔬 Undergraduate researcher in computing-education analytics
- 📍 Basking Ridge, NJ
- 📬 [cameronscarp@gmail.com](mailto:cameronscarp@gmail.com)
- 🔗 [linkedin.com/in/cameron-scarpati](https://linkedin.com/in/cameron-scarpati)

### 🏆 Awards

Computing Research Association Outstanding Undergraduate Researcher Award, Honorable Mention (national) · FortyAU Showcase, 1st Place ($3,500) · MSCF Distinguished Merit Scholarship ($15,000) · Provost's Faculty Grant for Immersion Vanderbilt ($2,000) · Calculus Top-Student Award (College of William &amp; Mary) · Dean's List (all semesters)

## 🛠️ Skills

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Focus areas:** Low-Latency Systems · Multithreading · Performance Optimization · TCP/IP · Machine Learning · Probability &amp; Statistics · Linear Algebra · Optimization · Data Structures &amp; Algorithms

**Vanderbilt coursework:** Data Structures · Algorithms · Machine Learning · Financial Mathematics · Linear Optimization · Probability &amp; Statistics · Differential Equations · Linear Algebra · Operating Systems · Computer Architecture · Database Systems

## 🚀 Featured Projects

### 📊 [Vol Surface Engine](https://github.com/CameronScarpati/vol-surface-engine)
A personal learning project that builds an arbitrage-free implied-volatility surface for live SPY options. It pulls option chains, backs out implied volatility with Newton-Raphson root-finding (Brent's method as a fallback), and fits the SVI parameterization per expiry slice with multi-start L-BFGS-B optimization. It enforces butterfly and calendar no-arbitrage constraints, then computes Dupire local volatility and the full Black-Scholes Greeks. Written in Python with NumPy and SciPy, with a Streamlit dashboard and a full pytest suite. It is a hands-on way to learn options and surface construction while I ramp up at MSCF.

### 📈 [LOB Regime Scanner](https://github.com/CameronScarpati/lob-regime-scanner)
A personal learning project that explores how hidden trading regimes can be detected from cryptocurrency order-book data using Gaussian Hidden Markov Models. It ingests Level 2 order-book snapshots and engineers roughly 30 features (order-flow imbalance, VPIN, book imbalance, realized volatility at multiple scales) to separate quiet, trending, and toxic states. The heavy lifting runs through a C++17 and pybind11 order-book engine, with the modeling and analysis in Python. I built it to learn quant research methods end to end as I move into MSCF.

### 🎯 [Buckshot Roulette Bot](https://github.com/CameronScarpati/buckshot-roulette-bot)
A C++17 AI agent that plays Buckshot Roulette using expectiminimax search with alpha-beta pruning. It evaluates thousands of game states per move inside a time budget using iterative deepening, modeling max nodes, min nodes, and chance nodes with a weighted heuristic evaluation. It is a compact study in adversarial search under uncertainty.

### 🌀 [Collatz Conjecture Visualized](https://github.com/CameronScarpati/collatz-conjecture-visualized)
An interactive C++ and OpenGL visualization of the Collatz conjecture, with bulk sequence generation, targeted number selection, animated gradient rendering, logarithmic and linear axis toggles, and real-time statistics. Memoization gives constant-time lookups on sequences already computed.

## 💼 Experience

### Morgan Stanley · Equity Algorithms Intern (Speedway Team)
*New York, NY · Jun 2025 to Aug 2025*
- Developed on the Speedway Team, an ultra-low-latency system that connects institutional clients to exchanges and supports up to 25,000 client orders per second for high-frequency trading and market making.
- Rebuilt the stress-test framework across Client Connectivity Services and raised the framework's own throughput by roughly 45 percent after tracing a thread-contention bottleneck.
- Researched C++ techniques to push TCP message rates toward 3 to 4 million messages per second.
- Received a return offer.

### LendOS · Software Engineering Intern
*Remote · Jun 2024 to Aug 2024*
- Debugged and cleaned up frontend components on a commercial lending platform.
- Updated and improved data-entry forms in close coordination with the product team.
- Contributed, as part of the team, toward the platform's Blackstone MVP (LendOS raised a Series A led by Blackstone Innovations).
- Received a return offer.
- *Stack: NestJS · DAML*

### Vanderbilt University · Teaching Assistant, Data Structures and Algorithms (Java)
*Nashville, TN · Aug 2024 to Dec 2024*
- Held office hours and mentored students through data structures and algorithms coursework.

### Morgan Stanley · Early Insights Program
*Spring 2024*
- Participated in workshops on technology-driven approaches to problems in finance.

## 🔬 Research

As an undergraduate researcher at Vanderbilt, I helped build an internal analytics platform that supports computer science instructors, built to handle more than 1,000 events per user each week across more than 300 users. My work focused on the data pipeline and on validating the platform's signals against ground truth using standard classifier evaluation (precision, recall, and accuracy). This research is being prepared for submission to ITiCSE 2027.

I also contributed to a Multi-Chip Ensemble side-channel analysis project that combines readings across devices to reduce noise. The project won first place at the FortyAU Showcase.

## 🎾 Interests

Tennis (playing since age four, high school varsity and senior captain) · Skiing · Rock Climbing · Chess · Sudoku · Table Tennis · Pool · Conversational Italian

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=CameronScarpati&show_icons=true&theme=onedark&hide_border=true&count_private=true" alt="Cameron's GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=CameronScarpati&layout=compact&theme=onedark&hide_border=true&langs_count=8" alt="Top languages" />
</p>

[![trophy](https://github-profile-trophy.vercel.app/?username=CameronScarpati&theme=onedark&no-frame=true&column=4&margin-w=15&margin-h=15)](https://github.com/CameronScarpati)
