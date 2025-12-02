# 🌐 Ecosysteme.ai — React + Vite Frontend

This project is the frontend application for **Ecosysteme.ai**, built using **React**, **Vite**, **TailwindCSS**, and **ESLint**.  
It provides a minimal, fast, and scalable setup to build modern UI with support for Hot Module Replacement (HMR).

---

## ⚙️ Tech Stack

- **React 19** — UI components and rendering
- **Vite** — Dev server + build tool with blazing performance
- **TailwindCSS** — Utility-first CSS framework
- **ESLint** — Code consistency and linting

Currently, one official plugin is used:

- [`@vitejs/plugin-react`](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react)  
  Uses **Babel** (or **oxc** via Rolldown) for Fast Refresh

---

## 🔥 React Compiler

The React Compiler is **not enabled** in this template by default due to development and build performance considerations.  
To enable it, follow the official guide:  
📌 https://react.dev/learn/react-compiler/installation

---

## 📦 Installation & Scripts

```bash
# Install dependencies
npm install

# Run local dev server
npm run dev     # http://localhost:5173

# Build for production
npm run build

# Preview production build
npm run preview

# Lint code
npm run lint
