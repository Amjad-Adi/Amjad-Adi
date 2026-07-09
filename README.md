# Amjad Adi

**Computer Engineering Student** | Birzeit University, Ramallah, Palestine
[LinkedIn](https://www.linkedin.com/in/amjad-adi-308b06338) | [GitHub](https://github.com/Amjad-Adi) | [Email](mailto:amjadqaher@gmail.com)

---

## 🛠️ Technical Expertise

**Languages:** Java, Python, C, SQL, Verilog HDL, Bash

**Frameworks & Libraries:** JavaFX, Android SDK, PyTorch, Pandas, NLTK, Scikit-learn, Hugging Face Transformers (BERT, MARBERT)

**Core Competencies:** RTL Design & Digital Verification, VLSI/Analog Circuit Design, Machine Learning/NLP, Full-Stack Development, Database Design, Systems Programming, Mobile Development, Networking, Shell Scripting

**Tools & Platforms:** MySQL, SQLite, Maven, Git, Linux, ModelSim/Icarus Verilog, SPICE (ngspice/LTspice), Electric VLSI, Cloudinary, Android Studio

---

## 🏆 Key Achievements

- Solved 450+ competitive programming problems on Codeforces and LeetCode
- Ranked 4th and 3rd in two consecutive IEEE Birzeit University Head-to-Head competitions, and 4th in the CES Club Team Competition
- Maintained a 94.4/100 GPA at Birzeit University, ranked among the top IT students for 7 consecutive semesters
- Built a custom Transformer model from scratch achieving 95.44% accuracy (87.54% macro F1) on the Penn Treebank corpus
- Co-authored a paper on a low-power Conditional-Capture Flip-Flop in 22nm CMOS, achieving a 42.5% reduction in dynamic power versus a benchmark reference design
- Developed a full-stack bookstore management system for a real library client (Al-Bireh Public Library, Ramallah & Al-Bireh)

---

## 📁 Featured Projects

### 📚 [Bookstore Management System](https://github.com/Amjad-Adi/BookStore-System)

*With Waseem Yahya — COMP333 Database Systems*

A full-stack desktop application developed for Al-Bireh Public Library (Ramallah & Al-Bireh), demonstrating layered architecture and secure data handling.

**Highlights:**
- Multi-user system with role-based access control (Admin, Worker, Customer)
- AES encryption utilities and password-hashing helpers for credential security
- MVC-style architecture with a DAO layer abstracting all database access
- JavaFX UI supporting product catalog, cart/orders (sales & rentals), payments/installments, inventory across warehouses, and reporting
- SQL-injection protection via parameterized PreparedStatements throughout the DAO layer

**Tech Stack:** Java, JavaFX, MySQL, Maven

---

### 📱 [Smart University Events App](https://github.com/Amjad-Adi/ENCS5150_Smart_Univetrsity_Event_App)

*With AbdAlrahman Atyani — ENCS5150 Mobile Application Development*

An Android application for university event discovery, reservations, and admin management, built with a repository-based MVC architecture.

**Highlights:**
- MVC-style separation across Activities/Fragments (view), a controller package per feature area, and a model layer with entity + repository classes
- 7 repository classes (User, Admin, Event, Reservation, Favourite, Review, Person) abstracting all SQLite CRUD operations
- Authentication with "Remember Me" and session persistence via SharedPreferences, seeded with a default admin account
- Cloudinary integration for profile and event image uploads, handled asynchronously

**Tech Stack:** Java, Android SDK, SQLite, Cloudinary

---

### 💻 [Operating Systems Process Scheduler](https://github.com/Amjad-Adi/OS_Process_Scheduler)

A Java-based operating system simulator implementing CPU scheduling, resource allocation, and deadlock detection.

**Highlights:**
- Hybrid Priority + Round Robin scheduler with a dynamic, burst-distribution-based time quantum
- Aging mechanism to prevent starvation, plus full process lifecycle modeling (arrival → ready → running → waiting → terminated)
- Resource allocation with Banker-style deadlock detection and priority/allocation-aware victim selection for recovery
- JavaFX visualization of the execution timeline (Gantt chart) alongside average waiting/turnaround time metrics

**Tech Stack:** Java, JavaFX

---

### 🏗️ [32-bit Five-Stage Pipelined RISC Processor](https://github.com/Amjad-Adi/ENCS4370_Pipelined_32-bit_RISC_Processor_Design)

*With Amir and Hanan Alawawda — ENCS4370 Computer Architecture*

A complete five-stage pipelined RISC processor implemented in Verilog, with full datapath, control unit, hazard detection, and data forwarding.

**Highlights:**
- Built the IF/ID/EX/MEM/WB pipeline with dedicated pipeline registers and a custom forwarding unit
- Implemented load-use stall detection and branch/jump instruction flushing
- Designed the ALU (8 operations), register file, control unit, and extender units from scratch
- Verified functionality and hazard handling with dedicated Verilog testbenches (ModelSim & Icarus Verilog)

**Tech Stack:** Verilog, RTL Design, ModelSim, Icarus Verilog

---

### ⚡ [Low-Power Conditional-Capture Flip-Flop (CCFF)](https://github.com/Amjad-Adi/Low-Power-Conditional-Capture-Flip-Flop-CCFF-)

*With Hanan Alawawda and Dana Obaid*

Design, SPICE simulation, and physical layout of a low-power sequential cell for reduced dynamic power consumption in 22nm CMOS.

**Highlights:**
- Achieved a 42.5% reduction in dynamic power versus the Kong et al. reference CCFF design (185.05 µW vs. 322 µW, matched load conditions)
- Implemented transistor-level SPICE circuits using a 22nm High-Performance Predictive Technology Model
- Built a full standard-cell layout in Electric VLSI with hierarchical M1–M6 routing, followed by LVS verification and RC-parasitic extraction
- Validated robustness through temperature (0–60°C) and supply voltage (0.7–1.2V) sensitivity sweeps
- Benchmarked against three literature designs (Kong et al., Zhao & Roy, Roy & Prasad)

**Tech Stack:** SPICE, Electric VLSI, 22nm CMOS PTM

---

### 🔌 [Single-Channel DMA Controller (UART → Memory)](https://github.com/Amjad-Adi/Simplified-Single-Channel-DMA-Controller)

*With Hanan Alawawda — ENCS3310 Advanced Digital Design*

A simplified single-channel DMA controller in Verilog that autonomously moves data from a UART peripheral into memory without continuous CPU involvement.

**Highlights:**
- Designed a 3-state FSM to orchestrate byte-level read/write handshaking between UART and memory
- Built and independently verified three modules — UART, Memory, and the DMA controller FSM — before system-level integration
- Confirmed correct end-to-end behavior across multiple transfers of different sizes and start addresses

**Tech Stack:** Verilog, FSM Design, Digital Design

---

### 🎮 [Socket Programming: HTTP Server & Multiplayer Quiz Game](https://github.com/Amjad-Adi/ENCS3320_1230800_1230892_1230256_Socket_Programming)

*With Mohyi Barghouti and Elyas Ihmud (Team T006) — ENCS3320 Computer Networks*

Two pure-Python, standard-library-only socket programming projects: a bilingual HTTP web server and a multiplayer TCP/UDP quiz game.

**Highlights:**
- **HTTP server:** manual HTTP/1.1 request parsing, English/Arabic routing, MIME-type detection, and custom 403/404 error pages
- **Quiz game:** hybrid TCP (registration, questions, results) + UDP (answer submission, instant feedback) architecture supporting 2–4 concurrent players
- Thread-per-client model with shared game state (scores, player list) synchronized across threads
- Port numbers computed programmatically from student IDs per assignment spec

**Tech Stack:** Python, Socket Programming, Multithreading, HTTP

---

### 🐚 [Online Course Log Analyzer](https://github.com/Amjad-Adi/Online-Course-Log-Analyzer)

*With Hanan Alawawda — ENCS3130 Shell Scripting*

A menu-driven Bash system for analyzing online course attendance logs, built from two modular shell scripts with input validation.

**Highlights:**
- 9 reporting modes: session counts per course, average attendance, absentees, late/early arrivals, per-student session duration, per-instructor attendance, and Zoom vs. Teams usage
- Chains core Linux text-processing tools (`grep`, `cut`, `awk`, `join`, `uniq`, `bc`) to extract and compute statistics directly from raw log files
- Cross-references the log file against a course registration file to identify students who never attended
- Validates the log file path on startup and re-prompts until a readable file is supplied

**Tech Stack:** Bash, Shell Scripting, Linux

---

### 🤖 [Transformer-Based Part-of-Speech Tagger](https://github.com/Amjad-Adi/ENCS5342-Part-of-Speech-POS-tagging)

*With Hanan Alawawda and Halima Hmaid — ENCS5342 Information Retrieval with Applications of NLP*

A custom encoder-only Transformer built entirely from scratch (no `nn.Transformer`, no pretrained weights) for POS tagging on the Penn Treebank corpus.

**Highlights:**
- Two-layer Transformer encoder with 4-head multi-head self-attention, sinusoidal positional encoding, and layer normalization, hand-coded in PyTorch
- BERT subword tokenization with correct word-to-tag alignment (first subword token)
- Incremental ablation study isolating the contribution of dropout, gradient clipping, weight decay, and an LR scheduler
- Achieved 95.44% Micro F1 (accuracy) and 87.54% Macro F1 across 45 POS tags, outperforming a majority-tag baseline and both other ablation configurations

**Tech Stack:** Python, PyTorch, BERT Tokenizer (Hugging Face Transformers)

---

### 🔐 [Sudoku Generator & Solver — CSP & Simulated Annealing](https://github.com/Amjad-Adi/Sudoku-Solver-using-CSP-Simulated-Annealing)

*With Hanan Alawawda — ENCS3340 Artificial Intelligence*

A comparative study of two AI approaches — CSP backtracking and Simulated Annealing — for solving 9×9 and 16×16 Sudoku puzzles.

**Highlights:**
- CSP solver combining MRV, MCV, and LCV heuristics with forward checking, benchmarked against a pure-backtracking baseline
- Simulated Annealing formulation with a cost function penalizing row/column/sub-grid duplicates and empty cells
- Benchmarked both approaches across Easy/Medium/Hard difficulty levels on execution time, completeness, constraint violations, and backtrack/iteration counts

**Tech Stack:** Python, CSP, Simulated Annealing

---

### 🤖 [Arabic Sentiment Analysis Model](https://github.com/Amjad-Adi/Arabic-Sentiment-Analysis)

*With Hanan Alawawdeh*

A comparative study of three model families for three-class Arabic sentiment classification, with Arabic-specific text preprocessing and feature fusion.

**Highlights:**
- Compared Naive Bayes (TF-IDF), an MLP neural network, and a Balanced Random Forest, each on fused TF-IDF + MARBERT embeddings (except Naive Bayes, TF-IDF only)
- Arabic-specific preprocessing pipeline: character/diacritic normalization, emoji/emoticon-to-text mapping, and repeated-character reduction
- Hyperparameter tuning via zoom-optimization (Naive Bayes) and RandomizedSearchCV (MLP, Random Forest)
- Balanced-class handling via BalancedRandomForestClassifier and custom class-prior mixing

**Tech Stack:** Python, PyTorch, Hugging Face Transformers (MARBERT), Scikit-learn, NLTK

---

### 🏥 [Hospital Patient Management System](https://github.com/Amjad-Adi/Hospital_Patient_Management_System)

A Java system modeling healthcare domain objects with an inheritance-based design.

**Highlights:**
- Abstract `PatientBase` class with specialized subclasses for different patient types
- Polymorphic billing calculations that vary by patient type (e.g., emergency vs. long-term)
- Doctor salary computation including overtime, with custom comparator-based sorting across multiple attributes

**Tech Stack:** Java, Collections Framework

---

### 📊 [Palestine MST Road Map](https://github.com/Amjad-Adi/Palestine_MST_RoodMap)

A graph-algorithms project applying Minimum Spanning Tree computation to route planning between Palestinian cities.

**Highlights:**
- Prim's and Kruskal's algorithms implemented for MST computation
- Applied to real geographical/city data for route optimization

**Tech Stack:** C, Graph Algorithms

---

### Additional Projects

*The following don't yet have a detailed README in this profile — descriptions kept brief until documented:*

- **Task Management Systems** — Data structure implementations using Binary Search Trees and linear structures (linked lists, stacks)
- **Arduino Gate System** — IoT automation with proximity sensors for vehicle detection and automated gate control
- **Assembly Task Scheduler** — Low-level systems programming in Assembly

---

## 🎓 Education

**Bachelor's in Computer Engineering**
Birzeit University, Ramallah, Palestine
*Expected Graduation: September 2027*
GPA: 94.4/100 — ranked among the top IT students for 7 consecutive semesters

---

## 📈 Notable Statistics

- 450+ competitive programming problems solved on Codeforces and LeetCode
- 2× IEEE Head-to-Head competition finalist, plus a CES Club Team Competition placement
- 95.44% accuracy (87.54% macro F1) on a from-scratch Transformer POS tagger
- 42.5% dynamic power reduction on a 22nm CCFF design, with a full pre-/post-layout verification flow
- A pipelined 32-bit RISC processor built with complete hazard detection and forwarding
- Multiple team-based projects across hardware (RTL, VLSI), backend systems, mobile, and ML/NLP

---

## 🤝 Let's Connect

I'm interested in opportunities involving:
- Hardware design & digital verification (RTL, FSMs, testbenches)
- Backend and systems software development
- Machine Learning and NLP research
- Full-stack and mobile application development
- Collaborative projects and open-source contributions

Feel free to reach out through [LinkedIn](https://www.linkedin.com/in/amjad-adi-308b06338) or [Email](mailto:amjadqaher@gmail.com)

---

*Last Updated: July 2026*
