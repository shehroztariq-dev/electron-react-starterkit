# Electron React Starterkit

A **cross-platform desktop application** built with **Electron**, **Vite**, and **React**.
This setup uses **Electron Forge** for streamlined packaging and distribution, combined with Vite for blazing-fast development.

---

## 🚀 Tech Stack

| Technology         | Purpose                              |
| ------------------ | ------------------------------------ |
| **Electron Forge** | Desktop app packaging & tooling      |
| **Electron**       | Desktop runtime (Chromium + Node.js) |
| **React**          | UI library                           |
| **Vite**           | Fast frontend bundler                |
| **React Refresh**  | Instant hot-reload in development    |

---

## 🗂️ Project Structure

```
├── src/
│   ├── main/       # Electron Main Process
│   │   └── main.ts
│   └── renderer/   # React Frontend (Renderer Process)
│       └── App.tsx
├── forge.config.js # Electron Forge Configuration
├── package.json
├── README.md
```

---

## ⚙️ Getting Started

### 1️⃣ Install Dependencies

```bash
npm install
```

---

### 2️⃣ Run in Development Mode

```bash
npm run dev
```

This will:

- Start **Vite dev server** for React with HMR.
- Launch **Electron** with your `main.ts` entry point.

---

### 3️⃣ Build for Production

```bash
npm run build
npm run electron:package
```

- **`npm run build`**: Builds React with Vite.
- **`npm run electron:package`**: Packages the app using Electron Forge.

---

## 📦 Scripts Overview

| Script                     | Description                        |
| -------------------------- | ---------------------------------- |
| `npm run dev`              | Run Electron + Vite in development |
| `npm run build`            | Build the React frontend           |
| `npm run electron:package` | Package app for distribution       |
| `npm run lint`             | Run ESLint                         |

---

## 🔧 Customization

### Modify the Electron Main Process:

Edit `src/main/main.ts` for Electron app logic.

### Modify the Renderer (React):

Edit `src/renderer/App.tsx` for your React UI.

---

## 🧩 Features

- ✅ **Hot Module Replacement** (React via Vite)
- ✅ **Native Desktop Integration** (Electron APIs)
- ✅ **Cross-Platform Packaging** (Windows, macOS, Linux)
- ✅ **Fast Build Times** (Vite bundler)

---

## 🛠️ Troubleshooting

### Unknown file extension `.ts` error?

Ensure `ts-node` and `electron-forge-plugin-vite` are configured correctly to handle TypeScript in Electron’s main process.
Use `ElectronForge + Vite` plugins to avoid manual `ts-node` setups.

---

## 📄 License

[MIT](LICENSE)

---

## ✨ Credits

- [Electron](https://www.electronjs.org/)
- [Vite](https://vitejs.dev/)
- [React](https://reactjs.org/)
- [Electron Forge](https://www.electronforge.io/)

---

If you want, I can help you generate this as a downloadable `README.md` file or customize it further (like adding badges, GIFs, or example screenshots). Would you like that?
