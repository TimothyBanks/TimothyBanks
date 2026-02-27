# **Timothy Banks**  
**Principal Engineer — Blockchain Protocols | High-Performance C++ Systems | Distributed Architecture**  
Charlotte, NC • (260) 445-3389  
timothyaaronbanks@gmail.com  
[GitHub](https://github.com/TimothyBanks) • [LinkedIn](https://www.linkedin.com/in/timothy-b-8175935b/)

---

# **SUMMARY**
Principal Engineer with 25+ years designing and delivering mission-critical, high-performance distributed systems across blockchain protocols, custody systems, consensus algorithms, developer-tooling ecosystems, GIS engines, UAV video pipelines, IoT/edge compute, and defense programs.  
Career-long C++ engineer with deep expertise in **C++11/14/17/20/23**, runtime architecture, WASM internals, compiler/LLVM tooling, PBFT-style consensus, deterministic state machines, MPC signing flows, and large-scale architectural redesigns.

Recognized for:
- Solving complex system-level problems quickly and permanently  
- Architecting systems that eliminate entire classes of bugs or engineering effort  
- Building internal tooling that dramatically elevates team productivity  
- Raising engineering standards through strong mentorship and deep code-review culture  
- Delivering critical systems under extreme deadlines and shrinking resources  
- Owning end-to-end system design across multiple domains simultaneously  

---

# **CORE COMPETENCIES**
**Languages:** C++11/14/17/20/23, C, Python, Java  
**Blockchain:** PBFT/Autobahn, CometBFT, Concord-BFT, EOSIO/DPoS, EVM, WASM, Bitcoin PoW  
**Protocols & Runtimes:** Deterministic state machines, VM internals, execution layers  
**Tooling:** LLVM/Clang AST tooling, static analyzers, WASM coverage (gcov/lcov), code-gen pipelines  
**Distributed Systems:** Consensus correctness, validation rules, data pipelines, RPC, event systems  
**GIS:** Raster/vector preprocessing, terrain algorithms, projections, OpenGL pipelines  
**Leadership:** Architecture direction, mentoring, review-culture enforcement, cross-team alignment  

---

# **NOTABLE SYSTEMS & PROJECTS**

### **Blockchain & Protocol**
- **Somnia PBFT/Autobahn L1 blockchain:** Principal engineer across consensus, execution, Hardhat compatibility, performance, and protocol safety.  
- **Hardhat Cheatcode RPC Support:** Enabled Somnia to function as a Hardhat node, unlocking >7,000 test cases.  
- **WASM VM context switching:** Added synchronous multi-contract calls to EOSIO-style runtimes.  
- **Patent-pending SQL→KV semantic mapper:** SQL-style access to blockchain KV state; eliminated integration barriers.  
- **Oracle networks:**  
  - Somnia — decentralized HTTP-outcall + consensus validation  
  - Bullish — rapid listing oracle minimizing infrastructure debt.
              Allowed for chain indexing, transaction creation and signing per on boarded protocol.  

### **Developer Productivity & Tooling**
- **WASM gcov/lcov coverage system:** Added true coverage metrics to WASM contracts — solved after multiple engineers failed.  
- **Native macOS EOSIO builds:** Removed Docker/cloud VM dependency entirely.  
- **Clang static analysis tools:** Automatically prevented migration-breaking contract patterns.  
- **Clang AST binding generator (ESRI):** Multi-language automatic SDK binding tool saving months every release.

### **Defense, GIS & Visualization**
- **DoD high-performance GIS engine:** Outperformed ESRI ArcObjects and FalconView on underpowered hardware.  
- **UAV low-bandwidth streaming system:** Real-time drone video to iOS over extremely constrained tactical networks.  
- **Chromalyzer:** 2D/3D palette engine w/ Lab/XYZ/HSV/RGB conversion, palette coverage algorithms, and image-based color matching.  
- **Photosphere (co-founder):** Paint, flooring, and lighting simulation platform (later acquired by Chameleon Power).

---

# **EXPERIENCE**

---

# **Somnia Protocol — Principal Protocol Engineer**  
**2025 – Present**

### **Autobahn PBFT Consensus & Protocol Architecture**
- Principal engineer responsible for the protocol execution environment, validator rules, consensus message flows, block finality paths, and performance characteristics.  
- Implemented multiple layers of deterministic guarantees, fork-safety checks, replay protection, and validator-sanity rules.

### **Hardhat Cheatcode RPC Support**
- Added full cheatcode coverage for Somnia, enabling the chain to act as a Hardhat node.  
- Result: >7,000 automated Hardhat tests now run against Somnia, dramatically expanding compatibility and developer confidence.

### **Decentralized HTTP-Outcall Oracle**
- Designed and implemented an oracle network enabling EVM contracts to securely request off-chain data.  
- Achieved consensus-verified results and safe on-chain callbacks.

### **Performance, Reliability & Engineering Culture**
- Introduced protocol-level anti-DDoS mechanisms and validation safeguards.  
- Championed **rigorous code-review culture** — no rubber-stamping, cross-team review participation, and a culture of open technical questioning.

---

# **Bullish — Principal Software Engineer, Custody**  
**2023 – 2024**

### **Custody Architecture Ownership**
- Technical lead across custody pipelines, MPC signing, WASM contract execution, deterministic state machines, and cross-chain integrations.  
- Delivered complete custody system under **fixed, funding-critical deadline**, despite declining team size.

### **Smart Contract Architecture Redesign**
Delivered a full redesign of the custody contract stack (C++ targeting EOSIO/WASM), achieving:  
- All future business requirements satisfied **with zero new contract code**  
- Nearly zero bugs post-launch  
- Vastly reduced maintenance & triage load  
- Predictable, easily audited system behavior

### **Developer Tooling Breakthroughs**
- Built **Clang AST–based static analyzers** identifying migration-danger patterns before they could enter production.  
- Designed and integrated **WASM gcov/lcov coverage** instrumentation.  
- Added **WASM VM context switching** to support synchronous contract → contract calls.

### **Protocol & Blockchain Integrations**
- Built **rapid-listing oracle** simplifying the onboarding of new assets, dramatically reducing engineering overhead.

### **macOS Native EOSIO Toolchain**
- Ported EOSIO to compile natively on macOS — completed in one morning after engineering management estimated three months.  
- Eliminated Docker/cloud VM dependence → significantly faster iteration cycles.

### **Engineering Leadership**
- Actively enforced a high-standard review culture, stepping in when review quality regressed.

---

# **Bullish — Lead Software Engineer, Smart Contracts**  
**2021 – 2023**

- One of the first engineers implementing custody smart contracts in C++/WASM.  
- Built deterministic state machines for onboarding, compliance checks, custodial flows, and controlled execution.  
- Led team of 5 engineers to deliver the **January 2022 Bullish Exchange launch**.  
- Enhanced debugging, build systems, contract execution flows, and developer ergonomics.

# **Block.one — Blockchain Engineer**  
**2020 – 2021**

### **EOSIO Protocol Engineering**
- Maintained and enhanced the EOSIO core engine: WASM execution pipeline, deterministic state transitions, multi-index DB behavior, and block validation rules.  
- Implemented protocol upgrades and performance improvements across Chainbase, fork-choice logic, and execution determinism guarantees.  
- Diagnosed subtle race conditions, replay inconsistencies, VM faults, and corrupted state transitions across multiple execution paths.

### **RocksDB Storage Integration**
- Integrated **RocksDB** as an alternative backend to Chainbase, enabling more flexible disk-based storage, lower RAM pressure, and improved operational reliability for resource-constrained deployments.

### **Review Culture & Debugging Leadership**
- Set high standards for correctness in consensus-critical code reviews.  
- Stepped in to evaluate complex defects spanning VM execution, networking, serialization, and on-chain determinism.

---

# **Amazon — Software Engineer (AWS Greengrass / IoT Edge)**  
**2019 – 2020**

### **SCIF / Offline Compute**
- Built secure offline-capable IoT computation layers used in SCIF-restricted environments with no outbound network access.  
- Designed predictable, reproducible execution models for edge devices with intermittent connectivity.

### **Runtime & Language Migration**
- Ported Python 2.x systems to Python 3.x while maintaining compatibility across embedded Linux targets.  
- Maintained C/C++ integration layers enabling low-latency device communication.

### **Reliability & Platform Hardening**
- Improved dependency resolution, sandboxing, and isolation for AWS Greengrass components.  
- Streamlined build and packaging pipelines for multiple architectures.

---

# **ESRI — Principal Software Engineer**  
**2013 – 2019**

### **C++ Runtime SDK Architecture**
- First engineer on the modern C++ Runtime SDK rewrite, replacing legacy code with a cross-platform, modular architecture supporting Windows, Linux, macOS, Android, iOS, and Qt.

### **LLVM/Clang AST Binding Generator**
- Designed and built an advanced AST-driven tool to automatically generate high-level bindings for:
  - Java  
  - Swift  
  - .NET  
  - Objective-C  
  - Qt  
  - Python  
- This eliminated months of manual engineering effort every release, ensuring consistency across platforms.

### **Rendering & Data Layers**
- Architected async operation models, error propagation frameworks, and rendering subsystems for 2D/3D maps.  
- Contributed to performance-critical components in geometry, features, layers, and networked GIS workflows.

---

# **Chameleon Power — Lead Software Engineer**  
**2013 – 2014**

### **C++ Visualization Engine (8× Performance Boost)**
- Completely rewrote the company's visualization engine in modern C++.  
- Delivered **8× speedup** enabling high-resolution, interactive room visualization on commodity hardware.

### **Visual Transformation Capabilities**
- Implemented:
  - Paint recoloring  
  - Tile and flooring replacement  
  - Lighting transformations (noon, dusk, incandescent, fluorescent)  
  - Material blending & masking  
- Created accurate reflectance and illumination simulation models for photorealistic results.

---

# **Chromalyzer — Lead Software Engineer**  
**2013 – 2014**

### **Color-Science Engine**
Built a professional-grade color-analysis and visualization suite featuring:

- **2D and 3D color-space visualization**  
- Conversions between **Lab, XYZ, HSV, RGB**  
- Ability to import photos and perform nearest-color matching  
- Palette coverage algorithms ensuring good distribution across perceptual space  
- Tools to help paint manufacturers design color lines with optimized perceptual spacing

---

# **General Dynamics — Staff Software Engineer**  
**2004 – 2012**

### **High-Performance GIS Engine (C++)**
Lead engineer and architect for a **complete GIS engine** built in modern C++ for multiple DoD situational-awareness programs.

Supported:
- Dozens of raster formats: **ASRP, CADRG, CIB, DTED, GeoTIFF, JPEG2000, MrSID, NITF**, etc.  
- Vector formats: **VPF, KML, GPX**, military overlays, tactical symbology  
- Projections: **WGS84, Mercator, Transverse Mercator, Equirectangular, UTM, UPS, BNG**  
- Grid systems: **MGRS**, full precision and conversion routines

### **Benchmark Superiority**
Independently benchmarked to outperform:
- **ESRI ArcObjects**  
- **FalconView**

while running on **resource-constrained military hardware**.

### **Terrain & Spatial Analysis**
Implemented advanced spatial algorithms:
- Intervisibility / line-of-sight  
- Dead-ground detection  
- Terrain-based routing  
- Raster pyramiding & tiling  
- Raster/vector fusion  
- Preprocessing pipelines for massive datasets

### **OpenGL Renderer**
- Built custom real-time rendering engine: GDI → DirectDraw → OpenGL migration  
- Enabled smooth pan/zoom, multi-layer overlays, tactical symbology, and hardware acceleration

### **UAV Low-Bandwidth Video System**
- Architected a system for streaming drone video over extremely constrained tactical networks  
- Delivered real-time feeds to **iOS devices**  
- Designed adaptive bitrate / resilience mechanisms for unstable battlefield links

### **Android Platform Migration**
- Proposed and led migration from **Windows CE → Android**  
- Solved severe development and deployment limitations  
- Produced an Android mapping SDK that **outperformed ESRI’s mobile SDK** in independent testing

### **Program Support**
Supported and delivered across multiple major systems:
- **ComBAT**  
- **Spartan**  
- **TiGR**  
- **TWV**  

Work spanned:
- Mapping engines  
- Video systems  
- Tactical overlays  
- Data-exchange formats  
- Field tests and validation with military units  

# **EDUCATION**

**Purdue University**  
- **M.S. Mathematics**  
- **B.S. Computer Science**  
- **B.S. Information Systems**

---

# **Photosphere — Co-Founder / Lead Engineer**  
**2002 – 2004**

### **Early Photographic Visualization Platform**
Co-founded Photosphere to build an advanced photo-based visualization engine enabling:

- Wall-colors to be changed from an uploaded photo  
- Flooring materials to be swapped (wood, carpet, tile)  
- Lighting conditions to be simulated (incandescent, fluorescent, daylight progressions)

### **Acquired by Chameleon Power**
Technology became the basis for Chameleon Power’s visualization suite used by major paint and construction brands.

---

# **SolutionPoint — Software Engineer**  
**1999 – 2002**

### **Web 2.0 Applications**
- Built dynamic ASP.NET, JavaScript, and C++ applications during early adoption of interactive "Web 2.0" design.  
- Developed data-driven architectures, UI components, and workflow systems for enterprise customers.

---

# **TECHNOLOGIES**
**Languages & Systems:**  
C++11/14/17/20/23, C, Python, Java, Rust  

**Blockchain / Protocol / Cryptography:**  
EOSIO, EVM, WASM, PBFT/Autobahn, CometBFT, Concord-BFT, Bitcoin PoW, MPC signing, deterministic runtimes, RocksDB, Chainbase, merkle proofs, replay protection  

**Tooling / Compiler / Build Systems:**  
LLVM, Clang, AST tooling, static analysis, gcov, lcov, CMake, Ninja, sanitizers, AST-driven code generation  

**GIS / Graphics / Imaging:**  
OpenGL, GDAL, raster/vector pipelines, terrain analysis, routing, projections, color-space transformations (Lab, XYZ, HSV, RGB), segmentation, illumination models  

**Cloud / DevOps / Infrastructure:**  
AWS, GCP, Kubernetes, Docker, Linux, macOS, CI pipelines, distributed systems monitoring  

**Other:**  
Hardhat testing framework integration, Android architecture, iOS streaming, UAV telemetry, low-bandwidth adaptive protocols

---

# **KEYWORDS**
C++11 • C++14 • C++17 • C++20 • C++23 • Modern C++ • C • Python • Java • Rust • Blockchain • Protocol Engineering • PBFT • Autobahn • CometBFT • Concord-BFT • WASM • EOSIO • EVM • Solidity Integration • Smart Contracts • MPC Signing • Consensus Algorithms • Deterministic Execution • RocksDB • LLVM • Clang • AST • Static Analysis • WASM Coverage • gcov • lcov • Developer Tooling • SQL→KV • Oracle Networks • Blockchain Indexing • High-Performance Computing • Distributed Systems • Runtime Architecture • Virtual Machines • GIS • UAV Streaming • Raster/Vector • OpenGL • Debugging • Performance Optimization • Memory Management • Multithreading • Real-Time Systems • Defense Software • Tactical Systems • Android • iOS • Edge Compute • IoT • SCIF Environments • Cloud Platforms • Kubernetes • Docker • cmake • Linux • macOS
