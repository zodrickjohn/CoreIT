# 🔗 CoreIT - Compute Without Limits

**CoreIT** is a decentralized distributed job execution system that allows users to rent and utilize idle compute power securely and efficiently for AI, 3D rendering, and large-scale data tasks. 

---

## 📘 Real-World Scenarios: Why CoreIT is Needed

### 👩‍🎓 Person X – The Struggling Student

> Aisha is a university student passionate about AI and 3D graphics. She’s building a neural style transfer model for her thesis and a Blender animation for her portfolio.  
> But there’s a problem:  
> - Her laptop only has **4GB RAM** and no GPU.  
> - **Google Colab keeps timing out**, and upgrading to paid cloud services like AWS or Azure is **unaffordable**.  
> - Her progress is stuck due to infrastructure limits.

✅ With **CoreIT**, Aisha uploads her code securely, and it’s executed on a lender’s powerful machine. She gets results in minutes — encrypted, containerized, and at micro-cost.

---

### 👨‍💻 Person Y – The Underutilized Developer

> Arnav is a freelance developer with a high-end PC: **RTX 4080, 64GB RAM**, but it stays idle most of the day while he works on his laptop.  
>
> He’s looking for passive income without risking his device or data. Trusting strangers with access is out of the question.

✅ With **CoreIT**, Arnav authenticates as a lender and accepts compute jobs inside a **sandboxed, encrypted container**.  
He earns credits or micro-payments securely — **without ever seeing the client’s code**, thanks to **Zero Knowledge Proofs**.

---

### 🚀 Problem

Access to high-performance computing is **expensive**, **centralized**, and **inaccessible** for many — especially students, indie developers, and under-resourced regions. 

Over 60% of personal devices stay **idle** most of the time, wasting potential compute resources.

---

## 💡 Solution: CoreIT

CoreIT bridges the compute gap by enabling users to:

- 📤 Upload jobs (AI, graphics, or compute-heavy tasks)
- 🧠 Securely execute them on idle machines (lenders)
- 🔐 Ensure privacy with **Zero Knowledge Proofs**
- 💸 Reward providers using **Solana Blockchain**

---

## ⚙️ Architecture Overview

![Architecture](architecture.png)

### 👨‍💻 Client Side

1. **Client Authenticates** via CoreIT
2. **Uploads Code** securely
3. CoreIT applies **Zero Knowledge Proofs (ZKP)** for secure verification
4. Code is temporarily stored in **Google Cloud**, then:
   - 📦 Zipped
   - 📦 Containerized
   - 📤 Pushed to **Docker Hub**

5. **Metadata stored on Solana blockchain**
6. **Encrypted Sandbox** is created
7. **Verification** of the environment and data

---

### 💻 Lender Side (Compute Providers)

1. **Lenders Authenticate** and **Accept Jobs**
2. Pull containerized jobs from Docker Hub
3. Jobs are **executed** securely
4. Execution is scheduled via **Redis**
5. Final **results are returned securely** to the client

---

## 🧰 Tech Stack

![Techstack](techstack.png)

### 🌐 Frontend
- `React.js` – User Interface
- `Zustand` – State Management
- `Three.js` – 3D job visualization

### ⚙️ Backend
- `Python`, `Node.js`
- `FastAPI`, `Flask` – REST APIs
- `Redis` – Job Scheduling
- `MongoDB` – Sessions, logs

### 🔐 Security & Blockchain
- `Zero-Knowledge Proofs (ZKP)`
- `Solana` – Immutable on-chain storage and rewards

### ☁️ Infrastructure
- `Docker` – Job Containerization
- `Google Cloud` – Temporary Storage
- `Docker Hub` – Image Hosting
- `OpenCV` – GPU health checks (via webcam)

### 🤖 AI/Utility Tools
- `Gemini`, `Groq` – AI code auditing, scoring
- `Chroma` – Code/data embeddings

---

## 🌟 Core Features

| Feature | Description |
|--------|-------------|
| 🔁 Remote Execution | Removes need for expensive cloud platforms |
| 🔒 ZKP Security | Lender can’t see client’s raw code |
| 📦 Containerized Jobs | Platform-agnostic, consistent executions |
| 💸 Incentivization | Providers earn by sharing idle GPU/CPU |
| 🧑‍💻 Dev Tooling | Seamless VS Code Extension integration |

---

## 🌐 What Makes CoreIT Unique?

- ✅ **Zero Knowledge Execution** (no raw code exposure)
- ⛓ **On-Chain Audit Trail** with Solana
- 💰 **Micro-Earnings** for hardware lenders
- 🧠 **Designed for AI/Graphics**, not just basic scripts
- 🕹️ **Web2 UX**, powered by Web3 infra

---

## 🔧 How to Run (Coming Soon)

We’re working on open-sourcing the CoreIT repo with setup instructions and VS Code integration. Stay tuned for:

- Local development setup
- Lender-side job execution instructions
- Secure container push/pull examples
- Blockchain interaction via Solana

---

## 👥 Team ILLUMINATI - HackOrbit 2025

- 🧑‍💻 Zodrick John – Team Lead  
- 🧑‍💻 Mohd Aanas – Backend & Blockchain  
- 🧑‍💻 Farahim – Frontend & AI Integration

