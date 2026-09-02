# Hi, I'm Ronak Singh

First-year @ University of Washington, Paul G. Allen School of Computer Science & Engineering — B.S. Computer Science, expected 2030 (sophomore standing via AP credit).

I like building things that touch the real world before they touch a resume — assistive hardware, systems from scratch, and the occasional too-ambitious weekend project.

- 🔭 Currently building a **vector database (HNSW, C++)** from scratch — Python bindings via pybind11, REST API in Flask, benchmarked against pgvector's production implementation
- 🧠 Published research on assistive brain-computer interfaces (P300, synthetic-to-real EEG transfer)
- 🏆 USACO Gold Division
- 📄 Two USPTO provisional patents
- 📫 Reach me at rsingh81@uw.edu

---

## Featured Projects

### [Vector Database in C++ (HNSW)](https://github.com/ronaksingh21/vector-db)
A Hierarchical Navigable Small World index built from scratch in C++, exposed via Python bindings (pybind11) and a Flask REST API.
- **93.7% recall@10** at **4.9ms average query latency** on 100K vectors (SIFT1M benchmark)
- Benchmarked against pgvector's production HNSW implementation to identify concrete optimization targets in memory layout and SIMD vectorization
- `C++` `pybind11` `Flask` `Systems Programming`

### [H.A.L.O. — Facial Recognition Home Access System](https://github.com/ronaksingh21/H.A.L.O) · [demo](https://youtu.be/NVgkAk_kEqg)
A real-time facial-recognition access system for visually impaired users. Runs as a two-tier system — a Raspberry Pi edge device sending detection events over the network to a Flask backend and companion app.
- Designed an idempotent event-notification method to eliminate duplicate alerts under repeated triggers — filed as **USPTO provisional patent 63/847,782**
- `Python` `OpenCV` `Flask` `Raspberry Pi` `REST APIs`

### [Autonomous Assistive Drone for the Visually Impaired](https://github.com/ronaksingh21/assistive-drone-documentation)
Real-time obstacle detection and audible alerts for visually impaired users, with autonomous user-following flight.
- YOLOv5 (PyTorch) object detection sustaining **30 FPS** on embedded hardware
- **6th nationally out of 140+ teams**, TSA Drone Challenge
- `Python` `PyTorch` `YOLOv5` `Embedded Systems`

### [Independent Research — Assistive BCI](https://github.com/ronaksingh21/BCIresearch)
A P300 brain-computer-interface classifier trained on synthetic EEG and fine-tuned on real recordings (MNE dataset).
- **6% accuracy improvement**, **9x inference latency reduction** (~4ms/sample on CPU)
- Published in the *National High School Journal of Science* (Nov 2025) · **USPTO provisional patent 63/847,808**
- `Python` `PyTorch` `MNE`

### [NFL Elo Ratings & Monte Carlo Outcome Prediction](https://github.com/ronaksingh21/nfl-elo-monte-carlo)
A statistical modeling pipeline over 25 seasons of NFL play-by-play data.
- Processed **901,698 records** across 6,730 games into analysis-ready features
- Validated the Pandas-based feature pipeline against independently-derived results using SQL (joins, `GROUP BY`, window functions)
- Elo rating + Monte Carlo simulation reaching **62.8% prediction accuracy** on held-out 2024 outcomes
- `Python` `Pandas` `SQL` `Monte Carlo Simulation`

### Tythe — Multi-Label Wallet Risk Classification
*Co-founder, private repo.* A hybrid risk-classification system pairing a config-driven rules engine with score-based heuristics.
- Pluggable model-training framework (LightGBM/XGBoost) with feature validation, train/eval splitting, and a versioned model registry
- `Python` `LightGBM` `XGBoost` `pytest`

---

## Tech Stack

**Languages:** Python, Java, C++
**ML / AI:** PyTorch, scikit-learn, LightGBM, XGBoost, YOLOv5, OpenCV
**Backend:** Flask, REST APIs, SQL
**Tools:** Git, GitHub, pytest, Linux, Raspberry Pi
**AI Dev Tools:** GitHub Copilot, Claude Code, Microsoft Roo Code

---

## Leadership

- **President & Technical Project Lead**, Technology Student Association — led a 300+ member chapter, directed prep for a 6th-place national finish
- **National Competitor**, FBLA — 2nd nationally in Network Design, 2nd nationally in Management Information Systems
- **Community Technology Volunteer**, Sikh Center of Seattle — taught programming to 31 students across three years (200+ hours)

---

*USACO Gold Division · Data Structures & Algorithms · Graph Traversal · Dynamic Programming*
