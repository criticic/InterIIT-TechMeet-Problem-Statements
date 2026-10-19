# Inter-IIT Tech Meet Problem Statements

A year-by-year archive of problem statements from the Inter-IIT Tech Meet, with concise summaries and links to the original PDFs. The 2026 edition (15.0), hosted by IIT Guwahati, is themed **Asymptotic Synapses**. The archive links 62 PDFs across seven editions; 27 entries are retained without a public PDF and marked *Not available*.

## Table of Contents

- [2026 (15.0) - IIT Guwahati - Asymptotic Synapses](#2026-150---iit-guwahati---asymptotic-synapses)
- [2025 (14.0) - IIT Patna - Resonating Cascades](#2025-140---iit-patna---resonating-cascades)
- [2024 (13.0) - IIT Bombay - The Timeless Technopolis](#2024-130---iit-bombay---the-timeless-technopolis)
- [2023 (12.0) - IIT Madras - Shores of Discovery](#2023-120---iit-madras---shores-of-discovery)
- [2022 (11.0) - IIT Kanpur - A Respawned Reality](#2022-110---iit-kanpur---a-respawned-reality)
- [2021 (10.0) - IIT Kharagpur - To Newer Horizons: In the Wake of the Pandemic](#2021-100---iit-kharagpur---to-newer-horizons-in-the-wake-of-the-pandemic)
- [2020 (9.0) - IIT Guwahati - Pandemic, Paranoia, and Possibilities](#2020-90---iit-guwahati---pandemic-paranoia-and-possibilities)

### 2026 (15.0) - IIT Guwahati - Asymptotic Synapses

**Theme:** Asymptotic Synapses · **Dates:** 11–14 December 2026

#### Prep Level: HIGH

##### IMC Trading

- **Prep Level:** HIGH
- **Summary:** Build an autonomous dealer bot that prices customer RFQs, competes with other dealers in a shared auction, and manages inventory risk to maximise net PnL across nine rounds in three difficulty tiers. A single Python `Dealer` class must quote and hedge under hidden customer limits, published settlement relationships, market impact and position limits, with scoring split across net PnL, customer volume and filled orders.
- **Domain:** Quantitative Finance, Market Microstructure, Algorithmic Trading, Market Making, Inventory Risk Management, Python
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2026_HighPrep_IMCTrading.pdf)

##### Sarvam AI

- **Prep Level:** HIGH
- **Summary:** Build a reproducible Hindi speech-to-speech data pipeline, then fine-tune a streaming model that translates live Hindi, mixed with English, into English speech while the speaker is still talking. Part A covers up to 200 hours of verbatim IndicVoices transcripts, word-level alignments and streaming-friendly English targets; Part B fine-tunes a shared checkpoint with Bulbul v3 (`shubh`, en-IN) audio and deploys it as a low-latency WebSocket service scored on intent, entities, latency, translation quality and naturalness.
- **Domain:** AI/ML, Speech-to-Speech Translation, Streaming Speech Processing, Hindi/Hinglish, Dataset Engineering, Model Fine-Tuning, Low-Latency Systems
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2026_HighPrep_Sarvam.pdf)

##### ideaForge

- **Prep Level:** HIGH
- **Summary:** Given a UAV image, an approximate location within 5 km, and camera/attitude/altitude metadata, determine the image centre's coordinates by matching it to satellite imagery for both daytime electro-optical (EO) and thermal infrared (IR), returning "no match" when unsure. The system must run offline on an NVIDIA Jetson Orin NX 16 GB after a 24–48 hour pre-processing window over a 100 km × 100 km evaluation region, judged on position-error bands, minimum availability and latency.
- **Domain:** Computer Vision, UAV Geo-Localisation, Cross-View and Cross-Modal Matching, Thermal Imagery, Deep Learning, Edge AI (Jetson Orin NX), GNSS-Denied Navigation
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2026_HighPrep_ideaForge.pdf)

##### Rime.ai

- **Prep Level:** HIGH
- **Summary:** An open research challenge on four failures of Indian voice technology: scarce clean data, cross-lingual cloning, misreading Hinglish/IDs/amounts, and the lack of automatic quality metrics. Teams choose one of two tracks and nominate a lead part. Track 1 builds a four-part multilingual system covering a low-resource data pipeline, 30-second cross-lingual cloning, learned text normalisation and a jury-free evaluator; Track 2 builds a recursive loop in which a Hindi/Tamil speech captioner and description-conditioned generator improve each other over at least two rounds.
- **Domain:** AI/ML, Text-to-Speech (TTS), Cross-Lingual Voice Cloning, Multilingual NLP, Speech Evaluation, Speech Captioning, Iterative Self-Improvement, Low-Resource Languages, Indian Voice Technology
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2026_HighPrep_Rime.pdf)

### 2025 (14.0) - IIT Patna - Resonating Cascades

**Theme:** Resonating Cascades

#### Prep Level: HIGH

##### LAT Aerospace

- **Prep Level:** HIGH
- **Summary:** Design a powered-lift fixed wing that combines a fixed wing with a thrust-producing device to reach very high lift coefficients, without tilt-wing, tilt-rotor or VTOL configurations. Teams must target CL 6.5 (bonus above 8), L/D above 5 with flaps and above 20 clean, 15 kg of lift at 20 m/s, and thrust-to-weight between 0.5 and 0.65, backing the design with analytical models, mesh-converged CFD and/or wind-tunnel validation. Judged 30% midterm, 50% endterm and 20% presentation.
- **Domain:** STOL Aircraft, Powered Lift, Aerodynamics, Computational Fluid Dynamics, Wind Tunnel Testing, Aircraft Design
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2025_HighPrep_LATAerospace.pdf)

##### Ebullient Securities

- **Prep Level:** HIGH
- **Summary:** Build a systematic intraday trading strategy over two anonymised one-second time-series datasets, EBX and EBY, each with a core price-like series and hundreds of masked price, volatility, volume and alternate-data features. Strategies must avoid look-ahead bias, square off daily, and generalise across both instruments, with the Calmar ratio staying stable when days are reordered. Midterm restricts teams to given features and ±1 unit trades; endterm allows derived features and sized trades. Minimum 20% annualised return and at most 10% drawdown.
- **Domain:** Algorithmic Trading, Quantitative Finance, Time Series Analysis, Backtesting, Risk Management
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2025_HighPrep_EbullientSecurities.pdf)

##### Pathway

- **Prep Level:** HIGH
- **Summary:** Build a production-grade, streaming-native agentic application for financial services on the Pathway framework, which must serve as the streaming data engine. Systems should ingest live or simulated streams, maintain up-to-date metrics, incrementally updated deterministic models and live retrieval indexes, and run ambient agents that act without prompts, with guardrails, MCP/A2A interoperability, observability and evaluation. Use cases are open, spanning investment decisions, credit risk, fraud monitoring, customer 360 and KYC, but must be validated and demonstrated end to end.
- **Domain:** Streaming Data Pipelines, Agentic AI, Retrieval-Augmented Generation, Financial Services, Real-Time Analytics, MLOps
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2025_HighPrep_Pathway.pdf)

##### Arista Networks

- **Prep Level:** HIGH
- **Summary:** Design and validate RRM-Plus, an AI-assisted, client-aware radio resource management system for enterprise Wi-Fi that exploits Arista's dedicated additional radio for continuous spectrum sensing. Teams must build adaptive sensing with multi-armed-bandit dwell scheduling, a non-Wi-Fi classifier, 802.11k/v client telemetry, Bayesian optimisation and safe reinforcement learning for channel, power, width and OBSS-PD decisions, all under change budgets and rollback guardrails. Targets include 15–20% higher median edge-client throughput, P95 retries down 20% and sensing airtime below 2%.
- **Domain:** Wi-Fi, Radio Resource Management, Spectrum Sensing, Reinforcement Learning, Network Optimisation, 802.11 Standards
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2025_HighPrep_Arista.pdf)

#### Prep Level: MID

##### Eternal

- **Prep Level:** MID
- **Summary:** Build an autonomous mobile robot that navigates warehouse aisles and scans racks up to 1.8 m tall, capturing 1920×1080 imagery of QR-coded inventory in real time. It must hold ±10 cm horizontal and ±2 cm vertical positioning, detect obstacles at 5 m, plan paths within 3 s, stop within 500 ms, traverse a rack in under 3 minutes and decode 5×5 cm QR codes above 90%, within a 600×450 mm, 25 kg chassis. Judged on X-Y and Z motion, scanning, SLAM and live demo.
- **Domain:** Autonomous Mobile Robots, SLAM, Warehouse Automation, Computer Vision, Embedded Systems, Inventory Management
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2025_MidPrep_Eternal.pdf)

##### Adobe

- **Prep Level:** MID
- **Summary:** Design and prototype a lightweight, mobile-first AI image editor for 2030 that keeps creators in control while running small generative models on limited compute. Teams deliver a 5–7 screen medium-fidelity mobile wireframe with design rationale, a market brief mapping which editing operations are already automated, and two working AI workflows built on open-source diffusion backbones such as SDXL Inpainting, Flux 1.1 or Kandinsky, using LoRA or quantised weights and SAM-style region selection, demonstrated as a Streamlit or web prototype.
- **Domain:** Generative AI, Diffusion Models, Mobile UI/UX, Image Editing, Model Quantisation, Human-AI Interaction
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2025_MidPrep_Adobe.pdf)

##### ISRO (GeoNLI)

- **Prep Level:** MID
- **Summary:** Build a hosted natural-language interface that lets non-experts interpret satellite imagery, covering captioning, query-based grounding with oriented bounding boxes, and visual question answering on geometric and semantic attributes. Solutions must describe small and large objects accurately, handle images up to 2k×2k, and generalise across 0.5–10 m/pixel sampling, with SAR, infrared or false-colour inputs earning innovation credit. Evaluation uses BLEU against expert captions, IoU@0.7 for grounding and a three-question VQA set, plus codebase, documentation and presentation.
- **Domain:** Vision-Language Models, Remote Sensing, Satellite Imagery, Visual Question Answering, Object Grounding, Geospatial AI
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2025_MidPrep_ISRO_VLM.pdf)

##### ISRO (Delta-Sigma ASIC)

- **Prep Level:** MID
- **Summary:** Study, model and implement a 20-bit delta-sigma ADC that raises ENOB at higher Nyquist rates, targeting 16–19 ENOB over roughly 0.5–2 ksps. Teams compare discrete-time, continuous-time and hybrid modulators and SINC/IIR/FIR decimation filters in MATLAB/Simulink, analyse flicker noise and chopping, then write the decimation filter in Verilog/VHDL and carry it through simulation, synthesis, place-and-route and post-layout simulation on a 180 nm PDK. Judged 35% modelling, 35% RTL, 20% ASIC flow and 10% presentation.
- **Domain:** Delta-Sigma ADCs, VLSI Design, RTL Design, Digital Signal Processing, ASIC Flow, Mixed-Signal Circuits
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2025_MidPrep_ISRO_VLSI.pdf)

##### Observe.AI

- **Prep Level:** MID
- **Summary:** Build a system that answers natural-language questions about business events in contact-centre conversations, such as escalations, refunds and churn, with evidence-based causal explanations rather than simple correlations. It must ingest large transcript corpora, model dialogue dynamics, surface the turns that contributed to an event, and support contextual follow-up queries. Teams deliver a dockerised implementation of both tasks, a technical report with baselines and ablations, and a curated set of 50–100 simulated or real queries with system outputs.
- **Domain:** Causal Inference, Conversational Analytics, Large Language Models, Retrieval-Augmented Generation, Speech Transcripts, Explainable AI
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2025_MidPrep_ObserveAI.pdf)

#### Prep Level: LOW

##### QTrino Labs

- **Prep Level:** LOW
- **Summary:** Build a post-quantum-secure DTLS 1.3 channel with mutual authentication between a server and a bare-metal RISC-V IoT device running without an operating system. Teams integrate PQC key exchange such as Kyber and signatures such as Dilithium into wolfSSL/wolfCrypt, run firmware on a LiteX + Verilator simulated SoC, and optimise handshake latency, throughput, ROM/RAM footprint and CPU cycles. Judging weights latency at 25%, throughput 20%, memory 15%, correctness 15%, reliability 10%, report 10% and presentation 5%.
- **Domain:** Post-Quantum Cryptography, DTLS 1.3, RISC-V, Bare-Metal Firmware, wolfSSL, Embedded Security
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2025_LowPrep_Qtrino.pdf)

##### Drona Aviation

- **Prep Level:** LOW
- **Summary:** Build an on-board stabilisation and precision-motion system for the MagisV2 nano-drone that holds position and altitude without GPS or pilot input. Teams fuse optical flow, ToF, IMU and barometer data into real-time velocity estimates and close cascaded position-velocity-attitude loops, executing stick-triggered 10-20 cm displacements to within +/-2 cm and hovering up to 2 metres. Deliver modular firmware plus documentation and a demonstration video; stability and precision carry 40% of the score.
- **Domain:** Drone Control, Sensor Fusion, Optical Flow, Embedded Firmware, Cascaded Control
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2025_LowPrep_Drona.pdf)

##### Game Connect (GDAI)

- **Prep Level:** LOW
- **Summary:** Design and build a three-level platformer game in 2D or 3D, with exactly three distinct levels showing a deliberate difficulty curve and progressive mechanic introduction. Any sub-genre is allowed, including puzzle, action, narrative, speedrun or exploration, using jumping, traps, enemies, collectibles and physics interactions under one unified theme, with a meaningful win condition after level 3. Deliver a Windows, Android or browser build plus a short deck and two-minute video; judging covers creativity, level design, gameplay feel and completeness.
- **Domain:** Game Design, Level Design, Platformer Mechanics, Unity/Godot, Playtesting
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2025_LowPrep_GDAI.pdf)

#### Prep Level: NO PREP

##### Jilo Health

- **Prep Level:** NO PREP
- **Summary:** Compete in a 12-hour on-site AI/ML in Healthcare hackathon, building an end-to-end system that spans mobile app to cloud backend. Teams are expected to work with computer vision and CNNs, fine-tune open-source LLMs on public datasets, and fuse multimodal AI, using vibe-coding tools such as Lovable alongside an agentic backend and database such as Supabase, with data from Hugging Face. The top five teams present their solutions on day two.
- **Domain:** Healthcare AI, Multimodal AI, Computer Vision, LLM Fine-Tuning, Full-Stack Development, Hackathon
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2025_NoPrep_JiloHealth.pdf)

##### Genuity

- **Prep Level:** NO PREP
- **Summary:** Solve four progressively harder rounds of low-level coding tasks from scalable AI and synthetic-data systems: data structure transformations over graphs, JSON, sparse matrices and distributed logs; custom loss functions with topological, geometric or structural constraints; autonomous knowledge-graph construction; LLM decision and control utilities; privacy-aware noise injection; and micro-pipeline helpers. Each round lasts 3-4 hours, with all teams in rounds 1-2, the top 12 in round 3 and the top four in round 4. Basic familiarity with topological data analysis, simplicial complexes and persistent homology is expected.
- **Domain:** Algorithms, Topological Data Analysis, Knowledge Graphs, LLM Systems, Data Engineering, Optimization
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2025_NoPrep_Genuity.pdf)

##### STEMvibe (Math Bowl)

- **Prep Level:** NO PREP
- **Summary:** Compete across four mathematics rounds over two days against an undergraduate olympiad syllabus covering algebra, number theory, geometry, differential and integral calculus, games and counting. Day one holds two olympiads of three and four hours with four questions each, open to all teams; day two adds a numerical round judged on speed and precision for shortlisted teams, followed by a final round whose format is disclosed on the day.
- **Domain:** Mathematics, Olympiad Problem Solving, Number Theory, Geometry, Combinatorics
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2025_NoPrep_MathBowl.pdf)

#### Prep Level: NA

##### Students' Academic Conference

- **Prep Level:** NA
- **Summary:** Present previously published or conference-presented research aligned with the Atmanirbhar Innovation theme, competing in three disciplinary categories spanning computer science, AI and electrical engineering; mechanical, civil, chemical and materials engineering; and pure sciences, management and humanities. Each IIT may submit one paper per category, capped at three overall, with a currently enrolled first author, a poster, slide deck and proof of publication. Scoring totals 40 points, while a 100-point rubric weights methodology and originality at 30 each.
- **Domain:** Academic Research, Research Presentation, Science and Technology, Innovation Policy, Poster Design
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2025_NA_SAC.pdf)

##### Engineers' Conclave

- **Prep Level:** NA
- **Summary:** Showcase student-built engineering projects addressing contemporary challenges under the Atmanirbhar Innovation theme, with eligibility through a filed patent, a student technical team, faculty collaboration or a submitted patent application. Each IIT may submit up to two projects, delivered as a slide deck, poster and working prototype with proof of patent filing or industry collaboration. Scoring out of 60 covers submission compliance (10), presentation and poster (20), prototype maturity (20) and two five-point bonuses.
- **Domain:** Engineering Innovation, Prototyping, Patent Filing, Technology Transfer, Project Showcase
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2025_NA_EC.pdf)

### 2024 (13.0) - IIT Bombay - The Timeless Technopolis

**Theme:** The Timeless Technopolis

#### Prep Level: HIGH

##### ISRO (URSC)

- **Prep Level:** HIGH
- **Summary:** Build a global lunar elemental-ratio map from the full archive of Chandrayaan-2 CLASS X-ray fluorescence spectra. Teams must identify flare spectra containing XRF lines, model line fluxes for elements such as Mg, Al, Si and Ca, project ratios including Mg/Si, Al/Si and Ca/Si onto a lunar albedo base map at roughly 12 km resolution, and quantify uncertainties. Judging covers mid-term line catalogues and coverage maps, then end-term ratio maps, sub-pixel resolution and open-source Python code.
- **Domain:** Lunar Geochemistry, X-Ray Fluorescence, Remote Sensing, Spectral Modeling, Planetary Science
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2024_HighPrep_ISRO.pdf)

##### Pathway Technology Inc.

- **Prep Level:** HIGH
- **Summary:** Create an agentic RAG system on Pathway that autonomously retrieves, analyses and synthesises information from multiple data sources to answer simple and multi-hop queries. Agents must choose retrieval strategies, control token usage, preserve answer accuracy and apply corrective or multi-agent techniques, with the index built on a Pathway VectorStore or DocumentStore. Judging weighs use-case novelty, technical implementation including resilience to API failures, architecture simplicity, reports and a GitHub repository with demo video.
- **Domain:** Agentic RAG, Generative AI, Retrieval Systems, Pathway Framework, Multi-Agent Systems
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2024_HighPrep_Pathway.pdf)

##### Zelta Automations

- **Prep Level:** HIGH
- **Summary:** Develop and backtest two algorithmic trading strategies for the BTC/USDT and ETH/USDT markets using historical data from 1 January 2020 to 31 December 2023. Teams must clean the data, design statistical or machine-learning signals, account for transaction costs of 0.15% per trade, and add risk controls. Submitted notebooks must use Zelta's SDK and no external backtesting libraries; judging covers performance, strategy logic, risk management, code quality, reports and presentation.
- **Domain:** Algorithmic Trading, Cryptocurrency Markets, Backtesting, Risk Management, Quantitative Finance
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2024_HighPrep_ZeltaAutomations.pdf)

##### ideaForge Technology

- **Prep Level:** HIGH
- **Summary:** Design and implement a PX4 control algorithm that lets a standard quadrotor implicitly detect a single motor failure and recover using only the remaining three motors. Solutions progress from controlled landing to stable hover and return-home navigation, tested in Gazebo with the IRIS model and limited to accelerometer, gyroscope, magnetometer, barometer and GPS sensing. Deliverables are documented code, a technical report and mandatory simulation videos, with bonus points for physical flight demonstration.
- **Domain:** UAV Control, Fault Tolerance, PX4 Autopilot, Gazebo Simulation, Flight Dynamics
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2024_HighPrep_ideaForge.pdf)

#### Prep Level: MID

##### Adobe Research

- **Prep Level:** MID
- **Summary:** Build a model that detects AI-generated images and explains the artifacts behind each classification. Task 1 classifies real versus synthetic images using the 60,000-sample CIFAKE dataset; Task 2 identifies and describes distinguishing artifacts such as texture irregularities, lighting inconsistencies and blending errors. The hidden test set uses different generative techniques and adversarial perturbations. Evaluation weights accuracy metrics at 50%, approach novelty and generalisability at 35% and presentation at 15%, with code and a 10-page LaTeX report required.
- **Domain:** AI-Generated Image Detection, Computer Vision, Explainable AI, Artifact Analysis, Diffusion Models
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2024_MidPrep_Adobe.pdf)

##### Dream11

- **Prep Level:** MID
- **Summary:** Build a Python fantasy-cricket tool for Dream11 with two interfaces: a Product UI that recommends an 11-player team for an upcoming match and a Model UI that retrains, evaluates and exports predictions. Models must predict player fantasy points from Cricsheet data, use no data after 30 June 2024, respect squad composition rules and provide explainable, GenAI-assisted audio or video guidance. Judging covers model accuracy and explainability (60%), UI (20%) and documentation (20%).
- **Domain:** Fantasy Sports, Player Performance Prediction, Explainable ML, Generative AI, UI/UX
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2024_MidPrep_Dream11.pdf)

##### FedEx

- **Prep Level:** MID
- **Summary:** Solve a three-dimensional packing problem by assigning cuboidal packages to a given set of Unit Load Devices on one flight and specifying each package's coordinates and axis-aligned orientation. Solutions must respect ULD weight and dimension limits, ship every Priority package, and minimise total cost from delayed Economy packages plus a fixed cost K per ULD containing Priority freight. Deliverables are a plain-text packing output, dependency-free code and a report.
- **Domain:** Bin Packing, Combinatorial Optimization, Air Cargo Logistics, Heuristics, Operations Research
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2024_MidPrep_FedEx.pdf)

#### Prep Level: LOW

##### Albatross Energetics

- **Prep Level:** LOW
- **Summary:** Model a vapor compression air-conditioning system in MATLAB/Simulink using a single scroll compressor, balancing cooling, dehumidification and energy efficiency under varying loads. Teams select one of four compressors and a suitable refrigerant (R290, R410A or blends), design the evaporator and condenser, and implement control logic varying compressor RPM and fan speeds. The room must reach 27°C dry-bulb and 19°C wet-bulb within 10 minutes; scoring weights average EER and ISEER, plus documentation, presentation and a low-GWP refrigerant bonus.
- **Domain:** HVAC Modelling, Vapor Compression, MATLAB/Simulink, Refrigerant Selection, Control Logic, Energy Efficiency
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2024_LowPrep_AlbatrossEnergetics.pdf)

##### Bharat Forge

- **Prep Level:** LOW
- **Summary:** Design and train a multi-agent "Singular Brain" for a robot swarm that plans optimal paths in GPS-denied, dynamic indoor environments. The system must avoid static and moving obstacles, rank navigation tasks dynamically by travel time, and persist memory so robots label and share environmental changes in a continuously updating database. Teams deliver ROS-compatible simulation code in Isaac Sim or Gazebo and at least four videos covering a 10x10 m environment with four or more robots, ten unique objects and three dynamic obstacles.
- **Domain:** Multi-Agent Systems, Path Planning, SLAM, ROS, Reinforcement Learning, Scalability
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2024_LowPrep_BharatForge.pdf)

##### IGDC

- **Prep Level:** LOW
- **Summary:** Design and develop a playable 2D or 3D game built around at least two or three of five themes: Hidden Networks, Autonomous Worlds, Algorithmic Campuses, Digital Archeology and Evolving Landscapes. Teams may use any engine or assets with clear licensing and must ship an executable build, preferably Windows .exe, Android .apk or browser, requiring no payment, subscription or advertising data collection. Judging weighs originality, engaging gameplay and completeness, supported by a short presentation and roughly two-minute development video.
- **Domain:** Game Design, Game Development, Level Design, Narrative Themes, Playable Prototype
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2024_LowPrep_igdc.pdf)

##### Insolation Energy (INA Solar)

- **Prep Level:** LOW
- **Summary:** Develop a predictive framework for solar panel waste in India and propose cost-effective, environmentally sustainable recycling solutions. Teams estimate future waste volumes from installation targets, adoption rates and 25-30 year panel lifespans, map infrastructure and rural logistics gaps, assess soil and water risks from cadmium and lead, and evaluate mechanical, chemical and bio-recycling options. Deliverables are a data-driven prediction model, recycling solution proposals, an environmental impact report and a policy roadmap covering EPR and circular-economy incentives.
- **Domain:** Solar Waste, Recycling Technology, Predictive Modelling, Circular Economy, Policy Analysis, Environmental Impact
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2024_LowPrep_InsolationEnergy.pdf)

#### Prep Level: NONE

##### RoboQuest (Rigbetel Labs)

- **Prep Level:** NONE
- **Summary:** Compete in RoboQuest, a two-round robotics challenge held at IIT Bombay, first in simulation and then on hardware provided by Rigbetel Labs. Teams implement ROS 2 Humble code on Ubuntu 22 covering SLAM, localization, sensor fusion and navigation, then deploy it on the provided robot to execute assigned tasks. The top ten teams from the simulation qualifier advance to the hardware round; entries are judged on accuracy, performance across parameters and problem-solving approach.
- **Domain:** Robotics, SLAM, Localization, Sensor Fusion, ROS 2, Autonomous Navigation
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2024_NoPrep_RigbetelLabs.pdf)

##### Messier Marathon

- **Prep Level:** NONE
- **Summary:** Compete in a two-round astronomy contest at IIT Bombay, beginning with a subjective pen-and-paper test of five to seven questions at Astronomy Olympiad (IAO/IOAA) difficulty. Topics include orbital mechanics, spherical trigonometry, optics and stellar observations, with partial marks awarded but no credit for answers lacking justification. The top ten teams advance to a night-time round using Newtonian telescopes on equatorial mounts, identifying stars, solar system and deep-sky objects and performing related calculations.
- **Domain:** Astronomy, Orbital Mechanics, Spherical Trigonometry, Optics, Telescopic Observation, Olympiad Problem Solving
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2024_NoPrep_MessierMarathon.pdf)

##### Math Bowl

- **Prep Level:** NONE
- **Summary:** Solve a four-hour subjective pen-and-paper mathematics examination comprising six questions of increasing difficulty, from pre-Olympiad level to roughly IMO Problem 2/5 standard. Topics span pre-college and first-year material including basic linear algebra, discrete mathematics and calculus. Each IIT submits one answer booklet, with partial marks available but no credit for solutions lacking proper reasoning or justification; answers are expected to be as rigorous as possible.
- **Domain:** Mathematics, Linear Algebra, Discrete Mathematics, Calculus, Olympiad Problem Solving
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2024_NoPrep_MathBowl.pdf)

#### Prep Level: NA

##### Students' Academic Conference

- **Prep Level:** NA
- **Summary:** Present previously published or conference-presented research aligned with the Viksit Bharat@2047 theme at the Students' Academic Conference. Undergraduate and postgraduate authors submit a paper with proof of publication or presentation, a poster and a presentation; each IIT may enter one paper per category and five overall across aerospace, chemical, bio-science, computing and basic-science categories. A poster round shortlists three papers per category for a five-minute talk plus three minutes of questions, scored out of 30 with bonus points.
- **Domain:** Academic Research, Research Communication, Poster Presentation, Science and Engineering, Peer Review
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2024_NA_SAC.pdf)

##### Engineers' Conclave

- **Prep Level:** NA
- **Summary:** Showcase a student-built engineering project that addresses a real-world problem and aligns with the Viksit Bharat@2047 vision. Eligible projects require a filed patent, faculty attestation or proof of a patent application, and each IIT may submit up to three. Teams provide a report of at most six pages covering motivation, survey and solution with test results, plus a poster and an optional prototype fitting within 50x50x50 cm³. Judges score the prototype out of 20 against the poster, with bonus points for patent filing.
- **Domain:** Engineering Innovation, Prototyping, Patent Filing, Technical Communication, Poster Presentation
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2024_NA_EC.pdf)

### 2023 (12.0) - IIT Madras - Shores of Discovery

**Theme:** Shores of Discovery

#### Prep Level: HIGH

##### DevRev

- **Prep Level:** HIGH
- **Summary:** Build "AI Agent 007", a tool-composing agent that takes a conversational query plus a dynamic toolbox of DevRev APIs (works_list, summarize_objects, prioritize_objects, get_sprint_id and others) and outputs JSON listing ordered tools, argument names and values, chaining results with $$PREV[i] references. The agent must handle follow-up turns, adapt when tools are added, modified or removed, and return an empty list when no composition answers the query; bonus credit for conditional logic and iteration. Deliver code with setup and tool-addition instructions plus mid-term and end-term experiment reports.
- **Domain:** LLM Tool Use, Conversational Agents, Agent Orchestration, JSON Schema, Customer Support, API Integration
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2023_HighPrep_DevRev.pdf)

##### Jaguar Land Rover

- **Prep Level:** HIGH
- **Summary:** Design a chiplet strategy for Jaguar Land Rover's safety-critical automotive compute. Analyse why and where chiplets add most value across at least two major in-car applications, draw micro-architecture diagrams showing all interconnects, and decide which package elements JLR should design versus buy to differentiate from other OEMs. Then survey die-to-die interconnect IP, select and justify a fast, secure, reliable technology with quantified latency and efficiency, and propose packaging and cooling. Submit a report, presentation and simulation files; mid-term 20%, final 80%.
- **Domain:** Chiplets, Automotive Semiconductors, SoC Architecture, Die-to-Die Interconnect, Thermal Management, Hardware Security
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2023_HighPrep_JaguarLandRover.pdf)

##### WorldQuant BRAIN

- **Prep Level:** HIGH
- **Summary:** Build "alphas" — mathematical models that predict future price movements — on the WorldQuant BRAIN web simulation platform, drawing on more than 100,000 available data points to develop, test and run signals. The qualifying stage is individual: reach 10,000 points in the WorldQuant Challenge and be conditionally approved as a BRAIN Research Consultant. Qualifying institutes then field teams of one to eight for a new final-stage problem statement released on 20 November, with mid-frequency alpha research and Python as key skills; the top seven teams present offline at IIT Madras.
- **Domain:** Quantitative Finance, Alpha Research, Financial Modelling, Python, Market Simulation
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2023_HighPrep_WorldQuantBrain.pdf)

##### Trumio

- **Prep Level:** HIGH
- **Summary:** Ideate, prototype and plan the go-to-market for standalone mobile or web apps built on Trumio's AI-powered University Project Ecosystem and App Store, addressing alumni engagement, student AI upskilling and client project quality. The 100-point response has three tiers: ideation (35) requiring at least three ideas, five slides each, feedback from 50+ alumni or clients and a business case with 3-5 year forecast; development (35) of a working UX prototype with three AI features; and a final presentation (30) with a seven-minute demo and go-to-market plan.
- **Domain:** Product Ideation, Go-to-Market Strategy, Generative AI, UX Prototyping, Platform Apps, Business Modelling
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2023_HighPrep_Trumio.pdf)

#### Prep Level: MID

##### Adobe

- **Prep Level:** MID
- **Summary:** Build models for two tasks on 300,000 sampled tweets from enterprise brand accounts: behaviour simulation, predicting user likes from tweet text, company, username, media URLs and timestamp, and content simulation, generating tweet text from metadata that includes likes. Both are tested on unseen brands and unseen time periods with 10,000-sample sets. Task 1 is scored by RMSE, Task 2 by BLEU 1-4, ROUGE and CIDEr, with metrics worth 50%, approach 35% and presentation 15%; submit a GitHub repository and a three-page ACL-format report.
- **Domain:** Engagement Prediction, Text Generation, Multimodal Learning, Marketing Analytics, NLP Evaluation Metrics
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2023_MidPrep_Adobe.pdf)

##### Aptos

- **Prep Level:** MID
- **Summary:** Build one of four projects on the Aptos Layer 1 blockchain using the Move language: a MetaMask Snap giving EVM users full Aptos account and asset control, a non-custodial futures platform for 24-hour contracts with instant settlement and automated liquidation, on-chain Wordle/Qwordle built around blockchain terminology, or a permissionless on-chain radio protocol with wallet connectivity and real-time revenue sharing. Submit a final presentation and a public or private GitHub repository with README, setup instructions and a hosted or locally runnable build; Aptos utilisation carries 30% of the score.
- **Domain:** Aptos Blockchain, Move Language, Smart Contracts, MetaMask Snaps, Web3 UX, DeFi
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2023_MidPrep_Aptos.pdf)

##### Mphasis

- **Prep Level:** MID
- **Summary:** Build a business-rules engine that re-accommodates airline passengers after planned schedule changes. It must identify impacted flights and PNRs, optimise suitable alternate flights including connections, rank flight options by time to destination and ancillary-service impact, and rank passengers by priority factors such as unaccompanied minors, on-duty employees, loyalty tier and paid class of service. Rules must be configurable, individually enable-able and scored by airline agents, producing a default flight-level solution file and a PNR-level exception list; IATA schedule, inventory, reservation and ticketing schemas are accepted.
- **Domain:** Airline Operations, Optimization, Business Rules Engine, PNR and IATA Data, Constraint Modelling
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2023_MidPrep_MPHASISfoundation.pdf)

##### Zelta Labs

- **Prep Level:** MID
- **Summary:** Develop algorithmic trading strategies for the BTC/USDT pair using historical price and volume data from 1 January 2018 to 31 December 2022, covering preprocessing, strategy design (trend-following, mean-reversion, momentum or machine learning), backtesting with 0.10% transaction costs and slippage, risk management and parameter optimisation. Deliver Colab or Jupyter code, backtest results with Sharpe, Sortino and drawdown metrics, a risk plan, presentation and report. Scoring weights performance at 40 points and rewards strategies holding drawdowns near 7-8%.
- **Domain:** Algorithmic Trading, Cryptocurrency Markets, Backtesting, Risk Management, Statistical Modelling, Python
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2023_MidPrep_ZeltaLabs.pdf)

#### Prep Level: LOW

##### IGDC

- **Prep Level:** LOW
- **Summary:** Build a 2D or 3D game that incorporates at least two or three of five themes: everything's breakable, landing on things, misdirection, symmetry and puzzles, backed by a scoring mechanism and a local leaderboard. Any engine, SDK or licensed asset may be used, provided the result is freely distributable and playable without payment or accounts. Deliver an executable build (Windows .exe, Android APK or browser) plus a presentation under 10 slides or a video under two minutes; judging weighs originality, engaging gameplay and completeness.
- **Domain:** Game Design, Game Development, Level Design, Interactive Media
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2023_LowPrep_igdc.pdf)

##### Ministry of Panchayati Raj

- **Prep Level:** LOW
- **Summary:** Develop a SimCity/Farmville-style 3D game in which players plan a hypothetical Gram Panchayat using SVAMITVA GIS data and the Gram Panchayat Development Plan. Teams must convert 1:10,000-scale panchayat imagery and 1:500-scale habitat imagery into simplified maps of buildings, streets, fields, trees and water bodies, then spend a configurable wallet of 5 lakh to 1 crore rupees on roads, drains, schools, health centres, sanitation and utilities. Asset placement drives a happiness and citizen-morale index, and evaluation rewards user-friendliness, design, research depth and originality.
- **Domain:** Serious Games, GIS Mapping, Rural Planning, Simulation, 3D Environment
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2023_LowPrep_Ministry%20of%20Panchayati%20Raj.pdf)

##### Solinas

- **Prep Level:** LOW
- **Summary:** Design a telescopic shaft for an agitator that homogenises solid waste with water or wastewater into pumpable slurry inside 5 m deep, 0.4 m diameter tanks. The shaft must extend to 5 m and retract to 1 m without affecting other components, remain waterproof and spark-proof, and expand or retract through a single switch while staying light enough to carry by hand. Judged on depth capability (20 points), flexibility and weight (15), user-friendliness (10), water-proofing (10), portability (15) and working assembly and part design (30).
- **Domain:** Mechanical Design, Telescopic Mechanisms, Agitator Systems, Waterproofing, Portability
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2023_LowPrep_Solinas.pdf)

##### CERT-In

- **Prep Level:** LOW
- **Summary:** Address three CERT-In cybersecurity briefs: design, rather than develop, a tool that improves audit quality and process for auditors, auditees and regulators; develop a security baseline safeguarding different application dimensions through proactive vulnerability prevention; and propose elements or techniques, with an implementation action plan, that let applications detect, report and respond to attacks. Solutions are judged on relevance, clarity of presentation, implementability, extent of objective fulfilment, depth of research, clarity of illustrations and originality.
- **Domain:** Cybersecurity, Security Auditing, Application Security, Threat Detection, Security Baselines
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2023_LowPrep_certIN.pdf)

#### Prep Level: NONE

##### Math Bowl

- **Prep Level:** NONE
- **Summary:** Compete in a four-hour subjective pen-and-paper mathematics examination of five questions rising in difficulty from pre-olympiad level to roughly IMO problem 2/5 standard. Topics span pre-college mathematics through first-year linear algebra, discrete mathematics and calculus. Each IIT fields one team of at most two members and submits a single answer booklet, with partial marks awarded only where solutions carry rigorous reasoning and justification.
- **Domain:** Mathematics, Olympiad Problem Solving, Linear Algebra, Discrete Mathematics, Calculus
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2023_NoPrep_MathBowl.pdf)

#### Prep Level: NA

##### Engineers' Conclave

- **Prep Level:** NA
- **Summary:** Present a student-built engineering project aligned with India's G20 priorities under the LiFE theme, spanning green development, inclusive growth, SDGs, digital public infrastructure, multilateral institutions or women-led development. Each IIT may submit up to three projects involving at least one registered student, as a six-page report, a poster and an optional prototype fitting within 50x50x50 cm. Every project earns 30 points, with up to 20 from judges for relevance, prior work, improvement, implementability and research depth, plus 5 for a filed patent.
- **Domain:** Engineering Innovation, Sustainable Development, Prototyping, Technical Poster, Research Translation
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2023_NA_EC.pdf)

##### Students' Academic Conference

- **Prep Level:** NA
- **Summary:** Present previously published or conference-presented research aligned with India's G20 priorities, with the first author a current student. Each IIT may submit one paper in each of five discipline categories, up to five overall, supplying publication or presentation proof, a 200-word report, a poster and a five-minute presentation followed by three minutes of questions. Judged on scientific significance, originality, knowledge of prior work, organisation, clarity and completeness, with the top three papers per category earning bonus points and Best Paper awards.
- **Domain:** Academic Research, Conference Presentation, Scientific Writing, Poster Design, Peer Review
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2023_NA_SAC.pdf)

### 2022 (11.0) - IIT Kanpur - A Respawned Reality

**Theme:** A Respawned Reality

#### Prep Level: HIGH

##### Drona Aviation

- **Prep Level:** HIGH
- **Summary:** Develop a Python wrapper for the Pluto educational nano drone, replacing mobile-app control with direct MSP and socket communication so the drone can be flown from a PC. Add webcam ArUco-tag pose estimation and a PID loop to hover at a fixed height and trace a 1x2 m rectangle, then extend the code to two-drone swarming with leader-follower paths. Submit a documented Python package, algorithm explanations and recorded videos; scoring is 150 points for the wrapper, 180 for hover and control, and 70 for swarming.
- **Domain:** Drone Swarming, PID Control, ArUco Pose Estimation, Python SDK, MSP Protocol
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2022_HighPrep_DronaAviation.pdf)

##### DevRev

- **Prep Level:** HIGH
- **Summary:** Build an extractive question-answering system that, given a question and themed paragraphs, first predicts whether an answer exists and returns the matching paragraph, then extracts the answer text and its start index. Round 1 tests an unseen theme; Round 2 gives two hours to fine-tune on sample pairs. Submit Colab training and inference notebooks plus a CSV of Question, Paragraph, Answer_start and Answer_text. Scoring uses F1 for paragraph search and QA, with 200 ms average inference and 4 GB memory limits.
- **Domain:** Extractive QA, Domain Adaptation, Model Fine-Tuning, Information Retrieval, F1 Evaluation
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2022_HighPrep_DevRev.pdf)

##### Grow Simplee

- **Prep Level:** HIGH
- **Summary:** Design a two-part last-mile delivery system for Bangalore: a scanner that estimates each item's length, breadth, height, volumetric weight and dead weight using images or depth sensing and flags out-of-range items, and a multi-pickup route planner that clusters n orders across at most m riders, builds capacity-aware bags and reroutes for k dynamically added pickups. Maximise on-time delivery while minimising distance, delivered as a documented codebase plus a web or app platform with map navigation. Scoring is 25% weighing tool, 55% routing and 20% platform.
- **Domain:** Route Optimization, Volumetric Weight Estimation, Fleet Scheduling, Dynamic Pickups, Logistics Platform
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2022_HighPrep_GrowSimplee.pdf)

##### gradCapital

- **Prep Level:** HIGH
- **Summary:** Pitch a game-changing startup idea: teams submit a one-liner problem statement with its purpose, validate the problem through interviews with real potential customers, then build a simple working prototype and a dynamic timeline of technologies that will keep the solution viable. A 0.5-1 page Stage 1 PDF and a 2-5 page Stage 2/3 PDF (11 pt, 1.5 spacing) accompany the prototype before a final panel defence. Scoring: 10% problem definition, 40% customer insight, 40% technical solution and 10% presentation.
- **Domain:** Startup Ideation, Customer Discovery, Prototyping, Technology Roadmapping, Pitch Presentation
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2022_HighPrep_gradCapital.pdf)

#### Prep Level: MID

##### Consensys

- **Prep Level:** MID
- **Summary:** Build a MetaMask Snap, a program running in an isolated environment that extends the wallet with functionality impossible for a plain dapp, and submit it as a hosted or locally runnable monorepo. Repositories need a README with setup and run steps, a React front-end is encouraged, and a fox.txt file must contain the phrase "What does the fox say?". Judging rewards novelty, user impact and whether the solution actually works; simple use cases that could exist without a Snap are excluded.
- **Domain:** MetaMask Snaps, Wallet Extensibility, Web3, Monorepo Tooling, React
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2022_MidPrep_Consensys.pdf)

##### Cloudphysician

- **Prep Level:** MID
- **Summary:** Extract heart rate, SpO2, respiratory rate, systolic and diastolic blood pressure and MAP from photographs of patient monitors, handling the four different screen types in the dataset. Teams receive 2,000 images with monitor segmentation boundaries, 1,000 classified images (250 per monitor type) and 7,000 unlabelled images for semi-supervised training. Accuracy of extracted values carries 60% of the score, novelty 30% and pipeline inference time 10%, with bonus points for detecting and digitising the heart-rate graph.
- **Domain:** Medical Monitor OCR, Vital Sign Extraction, Image Segmentation, Semi-Supervised Learning, ICU Telehealth
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2022_MidPrep_Cloudphysician.pdf)

##### ISRO

- **Prep Level:** MID
- **Summary:** Develop an AI/ML model that super-resolves medium or low resolution (5 m/10 m) Chandrayaan-2 TMC-2 lunar terrain imagery to roughly 30 cm, matching OHRC resolution, and train it on publicly available overlapping OHRC and TMC-2 coverage. The model must remain amenable to further training, be validated on a separate overlapping dataset, and then generate a global digital lunar atlas from TMC-2 data. Accuracy is measured with the Spectral Angle Mapper (SAM).
- **Domain:** Lunar Remote Sensing, Super-Resolution, Generative AI/ML, Spectral Angle Mapper, Chandrayaan-2
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2022_MidPrep_ISRO.pdf)

##### Jaguar Land Rover

- **Prep Level:** MID
- **Summary:** Design a ground-mounted robot that detects a vehicle's CCS2 charging port within its bounding box, reaches it and latches the plug, then unplugs and returns to rest after a 30-second charging cycle. The end effector must move and rotate in X, Y and Z while staying within speed and 5 deg/sec rotation limits, using off-the-shelf Indian-market components and accounting for cable bend radius. Deliver a MATLAB/Simulink Simscape model, plots or 3D animation, CAD views, BOM and per-cycle power consumption.
- **Domain:** Robotic Charging, CCS2 Connector, Pose Detection, MATLAB Simscape, Mechanism Design
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2022_MidPrep_JaguarLandRover.pdf)

#### Prep Level: LOW

##### QuantInsti

- **Prep Level:** LOW
- **Summary:** Test the efficacy of price action trading strategies in the Indian equities market by building automated signal detection, forming a clear hypothesis, and coding a low-frequency Python strategy on the Blueshift platform. Strategies may trade cash equities and equity or index futures, remain long-only for equities, and must run between 10 trades a month and 100 a day. Backtest from July 2018 to July 2021 with detailed performance data, transaction logs, and a report.
- **Domain:** Algorithmic Trading, Price Action, Indian Equities, Python, Blueshift, Backtesting
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2022_LowPrep_QuantInsti.pdf)

##### Cognitive Garage

- **Prep Level:** LOW
- **Summary:** Not available in this repository.
- **Domain:** Not available
- **PDF:** Not available

##### IGDC

- **Prep Level:** LOW
- **Summary:** Not available in this repository.
- **Domain:** Not available
- **PDF:** Not available

##### paradime.io

- **Prep Level:** LOW
- **Summary:** Not available in this repository.
- **Domain:** Not available
- **PDF:** Not available

##### Saptang Labs

- **Prep Level:** LOW
- **Summary:** Not available in this repository.
- **Domain:** Not available
- **PDF:** Not available

#### Prep Level: NONE

##### Students' Academic Conference

- **Prep Level:** NONE
- **Summary:** Not available in this repository.
- **Domain:** Not available
- **PDF:** Not available

##### Engineers' Conclave

- **Prep Level:** NONE
- **Summary:** Not available in this repository.
- **Domain:** Not available
- **PDF:** Not available

### 2021 (10.0) - IIT Kharagpur - To Newer Horizons: In the Wake of the Pandemic

**Theme:** To Newer Horizons: In the Wake of the Pandemic

#### Prep Level: HIGH

##### Digital Alpha

- **Prep Level:** HIGH
- **Summary:** Create a common bottom-up framework to retrieve and parse data efficiently from the SEC's EDGAR database, which contains vast quantities of documents including press releases, annual corporate filings, executive employment agreements and investment company holdings. Address the long-standing difficulty researchers face in using this material, caused by the absence of a standardised retrieval and parsing method.
- **Domain:** Document Processing, Data Retrieval, Financial Analysis, Natural Language Processing, Machine Learning
- **PDF:** Not available

##### Bosch

- **Prep Level:** HIGH
- **Summary:** Understand and demonstrate model extraction attacks on AI algorithms, with a specific focus on video-based deep learning models. Show how valuable AI models, treated as digital assets, can be breached and extracted by attackers, exposing organisations to potential financial loss, reputational damage and loss of competitive advantage in the process.
- **Domain:** Cybersecurity, Model Security, Deep Learning, Video Classification, Artificial Intelligence
- **PDF:** Not available

##### BlueYonder

- **Prep Level:** HIGH
- **Summary:** Address the critical need for efficient and sustainable supply chain models, especially as increased consumer demand and environmental impact in the form of carbon footprint have been exacerbated by the COVID-19 pandemic. Design supply chain solutions that are both efficient and environmentally responsible, responding directly to these combined pressures.
- **Domain:** Supply Chain Management, Logistics, Optimization, Sustainability, Data Science
- **PDF:** Not available

##### Silicon Labs

- **Prep Level:** HIGH
- **Summary:** Explore how the Internet of Things (IoT) can foster social entrepreneurship through its high connectivity. Leverage that connectivity to design profit-making business models that also create a positive societal impact, thereby contributing to the growth of socially conscious associations and showing how commercial ventures can serve social ends.
- **Domain:** Internet of Things, Social Entrepreneurship, Business Innovation, Technology for Good
- **PDF:** Not available

#### Prep Level: MID

##### ISRO

- **Prep Level:** MID
- **Summary:** Design a standalone web-based application, built with open-source software, that automatically identifies and categorises solar bursts based on X-ray energy data from cosmic sources, including the Sun. Build the system to simplify analysis of intermittent X-ray bursts, whose amplitude and duration vary depending on the source, making this data easier to interpret.
- **Domain:** Astronomy, Space Science, Web Development, Data Analysis, Signal Processing
- **PDF:** Not available

##### DRDO

- **Prep Level:** MID
- **Summary:** Develop a combined system of an Unmanned Ground Vehicle (UGV) and a guiding Unmanned Aerial Vehicle (UAV) capable of mapping and navigating challenging mountainous terrain. Ensure the combined platform avoids stability issues or 'collapsing', aiming to create robust autonomous navigation solutions suited to such demanding environments.
- **Domain:** Robotics, Unmanned Aerial Vehicles, Unmanned Ground Vehicles, Navigation, Mapping, Control Systems
- **PDF:** Not available

##### Mudrex

- **Prep Level:** MID
- **Summary:** Create a profitable automated trading bot using the Mudrex Visual Builder, with profitability as the competition's central objective. Participants gain access to Premium Mudrex accounts to develop, backtest and refine their trading strategies for predefined assets on specific exchanges, working through the full cycle of strategy creation, testing and refinement.
- **Domain:** Algorithmic Trading, Quantitative Finance, Financial Technology, Automation, Backtesting
- **PDF:** Not available

##### Bosch

- **Prep Level:** MID
- **Summary:** Develop a system that estimates the gender and age of individuals from surveillance video feeds, accounting for practical challenges such as low-quality cameras and cameras placed at a height. These conditions are common in environments like malls, retail stores or hospitals, and the solution must still produce usable estimates.
- **Domain:** Computer Vision, Machine Learning, Deep Learning, Image Processing, Surveillance
- **PDF:** Not available

#### Prep Level: LOW

##### Jaguar Land Rover

- **Prep Level:** LOW
- **Summary:** Conceptualise and design a powered bonnet for electric vehicles (EVs), using the space freed up at the front, or frunk, by the absence of an engine. Create an automated opening and closing mechanism for the front boot or trunk that enhances user convenience and adds a luxury feature.
- **Domain:** Mechanical Engineering, Automotive Design, Electric Vehicles, Automation, Product Design
- **PDF:** Not available

##### BlueYonder

- **Prep Level:** LOW
- **Summary:** Optimise next-generation delivery ecosystems, particularly those incorporating drone technology, with an eye toward mass adoption. Develop a sustainable drone deployment plan, including flight path and routing details, to serve customers at the lowest possible cost, supporting mass implementation of automated delivery systems across a wide network.
- **Domain:** Logistics, Drone Technology, Optimization, Route Planning, Supply Chain Management
- **PDF:** Not available

##### GMetri

- **Prep Level:** LOW
- **Summary:** Devise a growth strategy for GMetri, a no-code Metaverse builder, that capitalises on its ability to help businesses create immersive VR experiences for training modules, online stores and product showcases. Target the strategy at boosting retention and cutting training time within the learning industry, turning these capabilities into a route to growth.
- **Domain:** Metaverse, Virtual Reality, Business Strategy, Product Marketing, EdTech, No-Code Development
- **PDF:** Not available

##### Mercari

- **Prep Level:** LOW
- **Summary:** Focus on large-scale system design in this hackathon, inspired by Mercari's community-powered C2C marketplace. Develop a geographically scalable and accessible Hospital Management System (HMS), drawing inspiration from India's National Digital Health Mission (NHM), to digitise and manage patient data, prescriptions and reports at a national scale across the healthcare system.
- **Domain:** System Design, Scalability, Healthcare IT, Database Management, Software Architecture, Digital Transformation
- **PDF:** Not available

### 2020 (9.0) - IIT Guwahati - Pandemic, Paranoia, and Possibilities

**Theme:** Pandemic, Paranoia, and Possibilities

#### Prep Level: HIGH

##### Bosch

- **Prep Level:** HIGH
- **Summary:** Tackle traffic sign recognition, a key challenge in achieving L5 fully autonomous vehicles, where accurate perception of the surrounding environment is essential. Develop a solution that enables autonomous vehicles to perceive and interpret traffic signs accurately in real road settings, moving closer to the goal of completely self-driving transportation.
- **Domain:** Autonomous Vehicles, Computer Vision, Deep Learning, Image Processing, Artificial Intelligence
- **PDF:** Not available

##### Bridge2i

- **Prep Level:** HIGH
- **Summary:** Develop an automated system that generates headlines and analyses sentiment from digital content, combining both capabilities in a single workflow. The system aims to help experts synthesise large volumes of digital information efficiently, thereby supporting faster and more informed decision-making when experts face extensive and varied content streams.
- **Domain:** Natural Language Processing, Sentiment Analysis, Text Generation, Machine Learning, Data Science
- **PDF:** Not available

##### Drishtee

- **Prep Level:** HIGH
- **Summary:** Propose and develop tech-led innovations, whether products or services, aimed at empowering rural entrepreneurs and communities. Use technology to upskill rural youth, improve market linkages, enhance marketing efforts and optimise supply chains for goods and services moving between rural, semi-urban and urban markets, all in a profitable and sustainable manner.
- **Domain:** Social Entrepreneurship, Rural Development, Supply Chain Management, Market Linkages, Product Development
- **PDF:** Not available

#### Prep Level: MID

##### DRDO DRGE

- **Prep Level:** MID
- **Summary:** Design an autonomous drone for search and rescue operations in complex, inaccessible and dynamic environments such as areas affected by flash floods. Equip the drone with vision-based obstacle avoidance so it can navigate efficiently and reach target destinations, improving response rates in disaster scenarios and other difficult conditions.
- **Domain:** Robotics, Drone Technology, Computer Vision, Obstacle Avoidance, Autonomous Navigation, Embedded Systems
- **PDF:** Not available

##### ISRO

- **Prep Level:** MID
- **Summary:** Develop a web-based visualisation tool for AstroSat observations that enables users to identify scientific products from cosmic sources and generate maps displaying their positions. The tool should make AstroSat data publicly accessible and interpretable, presenting the mission's observations through an accessible, interactive interface designed for straightforward exploration.
- **Domain:** Astronomy, Web Development, Data Visualization, Space Science, Data Analysis
- **PDF:** Not available

##### Bosch

- **Prep Level:** MID
- **Summary:** Focus on electric vehicle (EV) simulation within the Indian context, where a significant automobile market, high oil import dependency and alarming pollution levels shape the case for cleaner mobility. Develop simulations related to EVs that support the country's push towards EV adoption across diverse conditions and use cases.
- **Domain:** Electric Vehicles, Simulation, Automotive Engineering, Renewable Energy, Policy Analysis
- **PDF:** Not available

#### Prep Level: LOW

##### QuantInsti

- **Prep Level:** LOW
- **Summary:** Develop and implement a systematic algorithmic trading strategy for US stock markets, using the Alpaca and Blueshift platforms for paper-trading. Focus on automating alpha discovery and risk allocation, and gain practical experience in quantitative trading as you take a strategy from initial design through simulated execution.
- **Domain:** Algorithmic Trading, Finance, Quantitative Finance, Data Analysis, Python, Machine Learning
- **PDF:** Not available

##### The Product Folks and Kaching

- **Prep Level:** LOW
- **Summary:** Analyse a product management case, released on 23 March, and propose solutions as part of this product case study competition. Participants are expected to examine the scenario closely and apply product management thinking, presenting reasoned recommendations that address the case's central product challenge in a structured and practical way.
- **Domain:** Product Management, Case Study, Business Strategy, Product Development
- **PDF:** Not available

##### Saptang Labs

- **Prep Level:** LOW
- **Summary:** Build working proof-of-concept exploits for known real-world CVEs in a 72-hour network-security hackathon. Teams must read each advisory, stand up the vulnerable service in a VM or Docker, reproduce the vulnerability and submit exploit code with a short video and report; the challenges cover Apache mod_status, Apache Tomcat JSP upload and CGI, Windows RDP and Apache Tika, worth 100-200 points each.
- **Domain:** Cybersecurity, Exploit Development, CVE Analysis, Web Server Security, Vulnerability Reproduction, Ethical Hacking
- **PDF:** [View PDF](InterIIT_Tech_Meet_PDFs/2020_LowPrep_SaptangLabs.pdf)

##### Jaguar Land Rover

- **Prep Level:** LOW
- **Summary:** Design a practically feasible method and apparatus for harvesting dissipated energy from a car's suspension dampers, converting vibrational energy that is normally wasted as heat into usable energy. The solution should improve energy efficiency and occupant comfort while remaining practical to implement within a production vehicle.
- **Domain:** Mechanical Engineering, Automotive Engineering, Energy Harvesting, Renewable Energy, Suspension Systems
- **PDF:** Not available
