<h1 align="center">🔗 CoreIT - Compute Without Limits</h1>

<p align="center">
  <b>A decentralized distributed job execution system</b><br>
  <i>Rent & utilize idle compute power securely for AI, 3D rendering, and large-scale tasks.</i>
</p>

---

## 🚨 Problem

> Access to high-performance computing is **expensive**, **centralized**, and **inaccessible** for many — especially students, indie developers, and under-resourced regions.

💡 **60% of personal devices** stay **idle most of the day**, wasting potential compute resources.

---

## 💡 Solution: CoreIT

CoreIT bridges the compute gap by enabling users to:

- 📤 Upload jobs (AI, graphics, compute-heavy)
- 🧠 Execute them securely on idle machines (lenders)
- 🔐 Ensure privacy using **Zero Knowledge Proofs**
- 💸 Reward providers via **Solana Blockchain**

---

## 📘 Real-World Scenarios

### 👩‍🎓 Aisha – The Struggling Student

> Aisha is building a **Blender animation** and an AI model on **neural style transfer**.  
> Her **4GB RAM laptop crashes** frequently, and **Google Colab times out**.

✅ With **CoreIT**, Aisha:
- Uploads code securely
- Leverages a high-end lender's GPU
- Gets results fast, at low cost — **without exposing her code**

---

### 👨‍💻 Arnav – The Idle GPU Owner

> Arnav owns a **powerful RTX 4080 PC** that's idle during the day.  
> He wants to **earn passively** but values **security and privacy**.

✅ With **CoreIT**, Arnav:
- Accepts containerized jobs
- Executes tasks in an **encrypted sandbox**
- Earns micro-payments securely without seeing any client code

---

## 🧠 System Architecture

<p align="center">
  <img src="assets/architecture.png" width="80%" alt="Architecture Overview">
</p>

### 🔐 Client Flow
1. Authenticate & upload code
2. Code is zipped & containerized
3. Stored temporarily on **Google Cloud**
4. Pushed to **Docker Hub**
5. Metadata is logged on **Solana Blockchain**
6. Encrypted sandbox is created & verified

### 🖥️ Lender Flow
1. Lender authenticates & accepts job
2. Pulls container from Docker Hub
3. Executes inside sandbox
4. Results returned securely to client
5. Job queue managed via **Redis**

---

## ⚙️ Tech Stack

<p align="center">
  <img src="assets/techstack.png" width="80%" alt="Tech Stack">
</p>

### 🧑‍💻 Frontend
- **React.js**, **Three.js**, **Zustand**

### 🔧 Backend
- **Python**, **Node.js**, **FastAPI**, **Flask**
- **MongoDB** – Sessions & logs
- **Redis** – Job queueing

### ☁️ DevOps & Infra
- **Docker**, **Google Cloud**, **Docker Hub**
- **OpenCV** – GPU health via webcam

### 🔐 Security & Blockchain
- **Zero-Knowledge Proofs (ZKP)**
- **Solana** – On-chain reward & verification

### 🤖 AI Tools
- **Gemini**, **Groq** – AI risk scoring
- **Chroma** – Code/data embeddings

---

## 🌟 Core Features

| 🚀 Feature                | 💬 Description                                                                 |
|--------------------------|--------------------------------------------------------------------------------|
| 🔁 Remote Execution       | Removes dependency on cloud platforms like AWS or Colab                        |
| 🔒 ZKP Security           | Guarantees code privacy even during 3rd-party execution                       |
| 📦 Containerized Jobs     | Enables consistency, sandboxing, and platform independence                    |
| 💸 Incentivization        | Allows idle hardware owners to earn income securely                           |
| 🧑‍💻 Dev Tooling           | Seamless VS Code integration, no complex setup                                |

---

## ✨ What Makes CoreIT Unique?

- ✅ **Zero Knowledge Execution**: Lender never sees client’s raw code
- ⛓️ **Blockchain Logging**: Immutable job history stored on Solana
- 💻 **Monetize Idle PCs**: Turn unused GPUs into income streams
- 🧠 **AI-Ready Design**: Built for training, rendering, and heavy compute
- 🕹️ **Web2 UX + Web3 Security**: Fast, modern UI with cryptographic backend

---

## 🛠️ How to Run (Coming Soon)

We’re working on open-sourcing the CoreIT repo. Stay tuned for:

- 📦 Local setup guide
- 🖥️ Lender job execution
- 🔁 Docker push/pull flows
- 🔐 Blockchain integration steps

---

## 👥 Team ILLUMINATI – HackOrbit 2025

| Name           | Role                      |
|----------------|---------------------------|
| 🧑‍💻 Zodrick John | Team Lead & Blockchain Dev |
| 🧑‍💻 Mohd Aanas    | Backend Dev   |
| 🧑‍💻 Farahim       | Frontend Dev |

---

## 🎬 Demo

📺 _Coming Soon — Stay Tuned!_

---

## 📜 License

Licensed under the [MIT License](LICENSE).

---

> 💬 *"Compute is the new oil — let's make it accessible to all."*
