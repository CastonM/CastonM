### Welcome to my page

I build and deploy enterprise AI systems, and I'm spending the next year going deep on the infrastructure that runs them.

**Day job:** Senior consultant at EY, leading the technical delivery of AI and data platforms for Fortune 500 healthcare and life sciences companies.

**Currently learning:** GPU hardware/software and High Performance Computing in Georgia Tech's MS CS (Systems specialization). Most of what I'm working on right now lives in private school repos, client accounts, and older profiles. I'm in the process of building out public versions and personal projects alongside coursework.

---

### Coursework

**Current focus**
- **HPC** — High Performance Computing: parallel programming with OpenMP and MPI, performance analysis of distributed/shared-memory systems, and scaling experiments on the PACE cluster
- **GPU HW/SW** — GPU Hardware/Software: GPU architecture, CUDA programming model, memory hierarchy, kernel optimization, and the performance fundamentals behind modern accelerated computing

**Systems foundation**
- **AOS** — Advanced Operating Systems (CS 6210): distributed systems, RPC, barrier synchronization, scheduling, and the systems primitives underneath modern cloud infrastructure
- **GIOS** — Graduate Introduction to Operating Systems (CS 6200): processes, threads, IPC, synchronization, virtualization, and the OS internals every systems engineer should have in their hands
- **SDCC** — System Design for Cloud Computing: scalable system design across compute, storage, and networking layers — what it actually takes to build cloud-scale infrastructure
- **CN** — Computer Networks (CS 6250): routing, congestion control, SDN, and the protocols that hold the internet together

**AI / Data**
- **BD4H** — Big Data for Health Informatics: large-scale healthcare data pipelines, predictive modeling with deep learning (MLPs, CNNs, RNNs in PyTorch), and applied ML on real clinical datasets

**Seminars**
- **C Langauge**
- **TinyML**
- **Agentic AI**
- **LLM Systems**

---

### Notable Projects

**Distributed File System (C++ / gRPC / Protocol Buffers)** · *CS 6200*
Designed and implemented a distributed file system with client-side caching, write-lock coordination, and asynchronous callbacks via gRPC. Built metadata synchronization and cache-consistency mechanisms across multiple concurrent clients, with deadline-based timeout handling and inotify-driven sync threads. Real exposure to the consistency, concurrency, and failure-handling tradeoffs that live underneath production storage systems.

**MapReduce Infrastructure (C++ / gRPC)** · *CS 6210*
Implemented a simplified MapReduce framework with a master-worker architecture: file sharding, worker pool management, intermediate key partitioning, and reducer coordination. Master tracks worker state (AVAILABLE / BUSY) and reassigns tasks on failure or slow workers. The hands-on version of the system every distributed-systems interview asks about.

**OpenMP + MPI Barrier Synchronization (C / OpenMP / MPI)** · *CS 6210*
Implemented multiple spin barrier algorithms (including tree-based barriers from the MCS paper) across OpenMP shared-memory and MPI distributed-memory models, plus a combined MPI+OpenMP hybrid barrier. Ran scaling experiments on the PACE cluster (up to 24 nodes × 12 cores) and analyzed where cache-line contention and network latency dominate — the kind of measurement work that informs real HPC tuning.

**SDN/NFV Controller (Python / OS-Ken / OpenFlow)** · *CS 6211*
Built an NFV orchestration layer with an SDN controller managing service function chaining across Dockerized network functions. Implemented packet routing, NAT connection-affinity, ARP handling, and flow-based round-robin load balancing using OpenFlow rules. Networking-meets-systems work that sits closer to how modern cloud infrastructure actually routes traffic than most coursework gets you.

---

### Where my code actually lives

Most of my engineering output sits in environments I can't make public:

- **Work repos** at EY (client systems, AI/data platforms)
- **School repos** in Georgia Tech's GitHub Enterprise (OMSCS Systems specialization coursework)
- **Client engagements** under NDAs

---

### Background

- **Enterprise AI delivery:** 4+ years shipping AI/data platforms to F500 — forecasting, federated learning, quote-to-cash, agentic AI, RAG systems
- **Systems engineering:** OMSCS Systems track — Operating Systems, Advanced OS, Distributed Systems, Computer Networks, System Design for Cloud Computing, HPC, GPU Hardware/Software
- **Languages:** Rust, C, C++, Python, SQL
- **Infrastructure:** AWS, Azure, Kubernetes, Docker, gRPC

---

### Interested in

GPU systems · LLM inference · HPC · distributed AI infrastructure · forward-deployed / Applied AI

---

### Find me

[LinkedIn](https://www.linkedin.com/in/castonmcdonald) · castonmcdonald@gmail.com
