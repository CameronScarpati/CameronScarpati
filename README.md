<h1 align="center">Hi, I am Cameron Scarpati 👋</h1>

<p align="center">
  <b>MSCF @ Carnegie Mellon · Ex-Morgan Stanley Equity Algorithms · Seeking Summer 2027 Quant Internships</b>
</p>

## About Me

I am a computer scientist and mathematician who comes at quantitative finance from the engineering side. In the summer of 2025 I worked on the Morgan Stanley team that owns an ultra-low-latency execution system, and that work is a large part of why I am moving toward research and why I came to Carnegie Mellon. My strength is fast, well-tested C++ and performance optimization, and I learn the finance by building. I am now a Master of Science in Computational Finance (MSCF) student at Carnegie Mellon, where the program is filling in the finance for me, from stochastic calculus to fixed income.

I graduated from Vanderbilt University summa cum laude with a 4.0, majoring in Computer Science and Mathematics, and my undergraduate research earned a national Honorable Mention for the Computing Research Association Outstanding Undergraduate Researcher Award. I am looking for a Summer 2027 internship in quant research, systematic trading, or quant development.

### 🎯 Quick Facts

- 🎓 **MSCF** at **Carnegie Mellon University**, Tepper School of Business (Pittsburgh, PA); expected Dec 2027
- 🎓 **Vanderbilt University**, B.A. in Computer Science and Mathematics, minor in Data Science, summa cum laude, 4.0 GPA, class rank 1 of 951 in the College of Arts and Science (May 2026)
- 💼 Ex-**Morgan Stanley** Equity Algorithms intern (Speedway Team)
- 🔬 Undergraduate researcher in computing-education analytics
- 📍 Pittsburgh, PA
- 📬 [cameronscarp@gmail.com](mailto:cameronscarp@gmail.com)
- 🔗 [linkedin.com/in/cameron-scarpati](https://linkedin.com/in/cameron-scarpati)

### 🏆 Awards

Computing Research Association Outstanding Undergraduate Researcher Award, Honorable Mention (national) · CS Immersion Showcase (FortyAU-sponsored), 1st Place ($3,500) · MSCF Distinguished Merit Scholarship ($15,000) · Provost's Faculty Grant for Immersion Vanderbilt ($2,000) · Calculus Top-Student Award (College of William &amp; Mary) · Dean's List (all semesters)

## 🛠️ Skills

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

**Focus areas:** Low-Latency Systems · Multithreading · Performance Optimization · TCP/IP · Machine Learning · Probability &amp; Statistics · Linear Algebra · Optimization · Data Structures &amp; Algorithms

**Vanderbilt coursework:** Data Structures · Algorithms · Machine Learning · Financial Mathematics · Linear Optimization · Probability &amp; Statistics · Differential Equations · Linear Algebra · Operating Systems · Computer Architecture · Database Systems

## 🚀 Featured Projects

### 📊 [Volatility Surface Engine](https://github.com/CameronScarpati/vol-surface-engine)
A personal learning project that builds an implied-volatility surface for equity options, SPY by default. It pulls option chains through yfinance or generates a synthetic chain offline, backs out implied volatility with Newton-Raphson root-finding (Brent's method as a fallback), and fits the SVI parameterization per expiry slice with multi-start L-BFGS-B optimization. It checks the butterfly and calendar no-arbitrage conditions and reports violations rather than enforcing them, then computes Dupire local volatility and the Black-Scholes delta, gamma, vega, and theta. Written in Python with NumPy and SciPy, with a Streamlit dashboard and a pytest suite that includes golden-value tests. I built it as a hands-on way to learn options and surface construction ahead of MSCF.

### 📈 [LOB Regime Scanner](https://github.com/CameronScarpati/lob-regime-scanner)
A personal learning project that explores whether hidden market regimes can be detected in cryptocurrency order-book data with a Gaussian Hidden Markov Model. It ingests Level 2 order-book snapshots, engineers 36 candidate features (order-flow imbalance, book imbalance, realized volatility at multiple scales, and more), and fits the model on a curated subset of eight to separate three states, which I rank by variance and label quiet, trending, and toxic. Regimes are decoded causally with the forward algorithm. The pipeline is written in Python, and the repo also includes a C++17 order-book engine with pybind11 bindings that rebuilds a book from level updates. I built it to learn quant research methods end to end before starting MSCF.

### 🎯 [Buckshot Roulette Solver](https://github.com/CameronScarpati/buckshot-roulette-bot)
A C++17 move advisor and playable opponent for Buckshot Roulette, built on an expectiminimax search. It tracks which seat has seen which shell and answers only from what the advised seat has seen. It ranks the available moves by the chance, under a stated opponent model, of being the last player standing in the round, looking a set number of reloads ahead and scoring positions beyond that point by the charges each player has left. A rules document separates what is verified about the game from what is reported or assumed. I built it as a hands-on study of adversarial search under uncertainty.

### 🌀 [Collatz Conjecture Visualized](https://github.com/CameronScarpati/collatz-conjecture-visualized) · [Live demo](https://collatz-conjecture-visualized.netlify.app/)
An interactive mathematics demo built with React, TypeScript, and HTML5 canvas. It animates the hailstone trajectories of the 3n + 1 problem, grows the reverse Collatz tree into an organic coral rendering after an idea by Edmund Harriss, and charts total stopping times with the record setters highlighted, with the mathematics typeset beside each chart. I built it to explore mathematical visualization.

### 📉 [Cauchy Convergence](https://github.com/CameronScarpati/cauchy-convergence) · [Live demo](https://cauchy-convergence.netlify.app/)
An interactive statistics demo built with React, TypeScript, and HTML5 canvas. It runs seeded simulations to show why the running mean of Cauchy samples never converges while the running median converges to the location parameter, with the mathematics typeset beside a live chart. I built it to explore statistical visualization.

## 💼 Experience

### Morgan Stanley · Equity Algorithms Intern (Speedway Team)
*New York, NY · Jun 2025 to Aug 2025*
- Worked on the team that owns Speedway, an ultra-low-latency execution system that connects institutional clients to exchanges and sustains 25,000 client orders per second for high-frequency trading and market making.
- Rebuilt the stress-test framework across Client Connectivity Services and raised the framework's own throughput by roughly 45 percent after tracing a thread-contention bottleneck, delivering in two weeks what was scoped at ten.
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

I also contributed to a Multi-Chip Ensemble side-channel analysis project that combines readings across devices to reduce noise. The project won first place at Vanderbilt's CS Immersion Showcase, sponsored by FortyAU.

## 🎾 Interests

Tennis (playing since age four, high school varsity and senior captain) · Skiing · Rock Climbing · Chess · Sudoku · Table Tennis (2nd place, MSCF tournament) · Pool · Conversational Italian
