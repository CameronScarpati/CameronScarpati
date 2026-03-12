# Hi there, I'm Cameron Scarpati! 👋

## About Me

I'm a Computer Science and Applied Mathematics double major at Vanderbilt University (4.0 GPA, Minor in Data Science) graduating May 2026. My focus is on **quantitative research and market microstructure** — I'm driven by the challenge of extracting signal from noisy financial data using rigorous mathematical modeling and high-performance computing. I have hands-on experience building ultra-low latency trading infrastructure at Morgan Stanley's Speedway Team and conducting original research at the intersection of statistical learning and financial markets.

📍 **Location:** Basking Ridge, NJ
🎓 **Education:** Vanderbilt University (B.A. in CS & Applied Mathematics, Minor in Data Science — May 2026)
📬 **Email:** [cameronscarp@gmail.com](mailto:cameronscarp@gmail.com)
🔗 **LinkedIn:** [linkedin.com/in/cameron-scarpati](https://linkedin.com/in/cameron-scarpati)

**Awards:** CRA Research Honorable Mention | Provost's Faculty Grant for Immersion Vanderbilt ($2000) | Calculus Top-Student Award | Dean's List (All Semesters)

## Skills

![C++](https://img.shields.io/badge/C++-Proficient-brightgreen?style=for-the-badge)
![Java](https://img.shields.io/badge/Java-Proficient-brightgreen?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-Intermediate-yellow?style=for-the-badge)
![LaTeX](https://img.shields.io/badge/LaTeX-Proficient-brightgreen?style=for-the-badge)
![Modern C++ (17/20)](https://img.shields.io/badge/Modern%20C++%2017%2F20-Proficient-brightgreen?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-Proficient-brightgreen?style=for-the-badge)
![JetBrains IDEs](https://img.shields.io/badge/JetBrains%20IDEs-Proficient-brightgreen?style=for-the-badge)
![Visual Studio Code](https://img.shields.io/badge/VS%20Code-Proficient-brightgreen?style=for-the-badge)
![Agile & Scrum](https://img.shields.io/badge/Agile%20%26%20Scrum-Experienced-blue?style=for-the-badge)
![SDLC](https://img.shields.io/badge/Software%20Development%20Life%20Cycle-Experienced-blue?style=for-the-badge)

**Relevant Coursework:** Data Structures | Algorithms | Machine Learning | Financial Mathematics | Linear Optimization | Probability & Statistics | Differential Equations | Linear Algebra | Operating Systems | Computer Architecture

## Featured Projects

### 📈 [LOB Regime Scanner](https://github.com/CameronScarpati/lob-regime-scanner)
A market microstructure analytics platform that detects hidden trading regimes from cryptocurrency order book data using **Gaussian Hidden Markov Models**. Processes Level 2 order book snapshots and extracts 30+ microstructure features (OFI, VPIN, Kyle's λ, book imbalance, realized volatility at multiple scales) to identify three distinct market states — Quiet, Trending, and Toxic. Key finding: VPIN spikes 30–120 seconds *before* toxic regime transitions, serving as a leading indicator of adverse selection. A regime-conditional strategy achieves a **1.8–2.5 annualized Sharpe ratio**. Built with Python 3.11+ and a **C++17/pybind11 LOB engine** processing 1M+ updates/sec, with an interactive Plotly Dash dashboard.

### 🎯 [Buckshot Roulette Bot](https://github.com/CameronScarpati/buckshot-roulette-bot)
A C++17 AI agent that plays the game Buckshot Roulette using **Expectiminimax search with alpha-beta pruning**. Evaluates thousands of game states per move within a 7-second budget via iterative deepening (depths 5–20). The game tree models max nodes (bot), min nodes (opponent), and chance nodes (shell uncertainty), with leaf scoring driven by weighted heuristics: health differential (600 pts), shell knowledge (300 pts), and item valuations (15–40 pts). Demonstrates adversarial search under uncertainty — a core algorithmic pattern in quantitative decision-making.

### 🌀 [Collatz Conjecture Visualized](https://github.com/CameronScarpati/collatz-conjecture-visualized)
An interactive C++/OpenGL visualization of the Collatz conjecture — one of mathematics' most famous unsolved problems. Supports bulk sequence generation and targeted number selection with animated gradient rendering, logarithmic/linear axis toggling, and real-time statistical overlays (step counts, peak values, averages). Performance-optimized through memoization for constant-time lookups on previously computed sequences.

## Experience

### Quantitative Developer — Speedway Team
**Morgan Stanley** · Equity Algorithms
*June 2025 – August 2025* · New York, NY
- Developed for the Speedway Team, an ultra-low latency solution connecting institutional clients to stock exchanges supporting up to 25,000 orders per second for high-frequency trading and market making
- Revamped stress-testing framework across Client Connectivity Services increasing throughput up to ~45%
- Researched C++ to push the limits of sending TCP messages at speeds of up to ~3–4 million per second

### Undergraduate Researcher
**Vanderbilt University** · NestJS | Angular | Kotlin & Gradle | AWS
*January 2024 – Present* · Nashville, TN
- Spearheaded the development of "DevStats," an application to promote academic integrity at Vanderbilt by monitoring student activities and identifying patterns indicative of academic dishonesty
- Architected a secure application capable of handling 1000+ logs per student weekly, serving 300+ users

### Software Engineering Intern
**LendOS** · NestJS | React | DAML | Agile & Scrum
*June 2024 – August 2024* · Remote
- Engineered components of a groundbreaking commercial lending platform optimizing its scalability and robustness
- Partnered closely with the product team to ensure the platform's user interface and functionality aligned seamlessly with strategic business goals

### Teacher's Assistant — Data Structures & Algorithms
**Vanderbilt University** · Java
*August 2024 – December 2024* · Nashville, TN
- Conducted office hours to mentor students, providing personalized guidance on course materials and assignments

### Early Insights Program Participant
**Morgan Stanley** · Technology
*February 2024* · New York, NY
- Engaged in workshops to explore operational strategies and technology-driven solutions to financial challenges

## Publications & Research

- **DevStats: A Novel Code Plagiarism Detector** — Primary Author | CRA Research Award Honorable Mention | *ITiCSE 2026* (Manuscript in Preparation)
- **Deep Learning Side-Channel Analysis** — Primary Author | *ITiCSE 2026* (Manuscript in Preparation)
- **Alternative Risk Measures and Stock Selection** — Editorial Contributor | Under Review (2025)
  - Delivered editorial guidance and LaTeX formatting for research on entropy and Hurst exponent as volatility measures

## Extracurriculars

Club Tennis Team | Conversational Italian | Rock Climbing | Chess | Sudoku | Table Tennis | Pool

![trophy](https://github-profile-trophy.vercel.app/?username=CameronScarpati&theme=onedark)
