# DKeeper

DKeeper is a decentralized note‑keeping application built with **Motoko** on the **Internet Computer (IC)**.  
It demonstrates how to combine a Motoko backend with a React/Webpack frontend, enabling persistent storage of notes on the blockchain.

---

## 📖 Table of Contents
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Prerequisites](#-prerequisites)
- [Setup & Development](#-setup--development)
- [Deployment](#-deployment)
- [Troubleshooting](#-troubleshooting)
- [License](#-license)

---

## 🚀 Features
- Motoko actor (`Dkeeper`) storing notes as a list
- React frontend with Webpack bundling
- CSS integration via `style-loader` and `css-loader`
- Local development using `dfx` replica
- Deployable to Internet Computer mainnet

---

## 📂 Project Structure
src/
dkeeper/            # Motoko backend (main.mo)
dkeeper_assets/     # Frontend React app + CSS
declarations/       # Auto-generated canister bindings (created by dfx build)
dfx.json              # Canister configuration
webpack.config.js     # Webpack bundling rules
package.json          # Node dependencies


---

## ⚙️ Prerequisites
- [DFINITY SDK (dfx)](https://internetcomputer.org/docs/current/developer-docs/setup/install)
- Node.js (v16+ recommended)
- npm or yarn

---

## 🛠️ Setup & Development

1. **Install dependencies**
   ```bash
   npm install
2. dfx start --background
3. dfx build
3.2 dfx deploy
4. npm start

