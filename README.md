#  GPU Registry dApp on Sui Blockchain

A decentralized application for managing GPU resources and tracking ML model execution on the Sui blockchain. Built using Move for smart contracts and React/Next.js for the frontend.

> ⚠️ Project is currently in active development. Smart contracts have been deployed to a local Sui network for initial testing.

---


---

## 🚀 Features (in progress)

### ✅ Smart Contracts (Move)
- GPU Registry Module
  - Register GPU
  - Update availability
  - Transfer ownership
  - Emit GPURegistered, GPUAvailabilityChanged events

- Model Execution Module
  - Create execution
  - Update execution status
  - Track executions by GPU/model
  - Emit ExecutionCreated, ExecutionCompleted events

### 🧪 Status
- [x] Localnet setup and deployed smart contracts
- [x] Basic contract functions implemented
- [ ] Unit tests (in progress)
- [ ] Devnet deployment

---

## 💻 Frontend (Next.js + TypeScript)

### Planned Pages
- GPU Registry Dashboard
- Add GPU Form
- Model Execution Interface
- Execution History
- User Profile

📌 Tech Stack:
- Next.js 13+
- TypeScript
- Tailwind CSS
- React Query
- @mysten/sui.js
- Chart.js (for analytics)

---

## 🧰 Getting Started

# 🛠️ Sui Blockchain CLI Setup Guide (macOS/Linux with Homebrew)

This guide walks you through installing the Sui CLI using Homebrew.

---

## 📦 Step 1: Install Homebrew (if not installed)

If you don't have Homebrew installed yet, run:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
