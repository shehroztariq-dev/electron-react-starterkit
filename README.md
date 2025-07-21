# ⚡ Electron React Starterkit

![Electron Version](https://img.shields.io/badge/Electron-29.0.0-blue.svg?logo=electron)
![React Version](https://img.shields.io/badge/React-18.0.0-61DAFB?logo=react)
![Vite Version](https://img.shields.io/badge/Vite-5.0.0-646CFF?logo=vite)
![Platform Support](https://img.shields.io/badge/Windows|macOS|Linux-green.svg?logo=github)
![License](https://img.shields.io/github/license/your-repo-name/electron-react-starterkit)

---

## 🎯 Project Overview

**Electron React Starterkit** is a **blazing-fast desktop application boilerplate** built using:

- ⚡ **Electron** for cross-platform desktop runtime
- ⚡ **Vite** for super-fast frontend bundling
- ⚛️ **React** for building interactive UIs
- 🛠️ **Electron Forge** for easy packaging & distribution

**Keywords:**
Electron React Starter Kit, Vite Electron React Boilerplate, Cross-Platform Desktop App, Electron Vite Setup, Electron React Template

---

## 🗂️ Directory Structure

```
electron-react-starterkit/
├── src/
│   ├── main.js        # Electron Main Process (JavaScript)
│   └── renderer.jsx    # React Renderer Process (Frontend)
├── public/          # Static files
├── forge.config.js  # Electron Forge Configuration
├── package.json
└── README.md
```

---

## 🚀 Quick Start

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/shehroztariq-dev/electron-react-starterkit.git
cd electron-react-starterkit
```

---

### 2️⃣ Install Dependencies

```bash
npm install
```

---

### 3️⃣ Run in Development

```bash
npm run dev
```

- Starts **Vite Dev Server** (React frontend)
- Launches **Electron** with hot reload

---

### 4️⃣ Build for Production

```bash
npm run build
npm run electron:package
```

---

## ⚙️ Scripts

| Command                    | Description                             |
| -------------------------- | --------------------------------------- |
| `npm run dev`              | Run Electron + Vite in development mode |
| `npm run build`            | Build the React frontend                |
| `npm run electron:package` | Package the app via Electron Forge      |
| `npm run lint`             | Run ESLint                              |

---

## 📦 Features

- 🔥 **Vite-Powered React Development** (Fast HMR & builds)
- 🖥️ **Cross-Platform Desktop Support** (Windows, macOS, Linux)
- 📦 **Electron Forge Packaging** (Easy installers & distribution)
- ⚡ **Modern JavaScript (ES6+)**
- 🔧 **Hot Reload in both Main and Renderer processes**

---

## 💡 Why Use This Starter Kit?

- 🚀 **Instant Setup** for Electron + React with Vite
- 🧰 **Minimal Boilerplate**, Easy Customization
- 💻 **Developer-Friendly**, No TypeScript (pure JS)

---

## 🌐 SEO & Meta

This boilerplate is ideal for:

- Electron React JS Desktop App Development
- Cross-Platform Desktop UI with Vite + React
- Quickstart Electron Forge App Template
- Vite Electron Starter with Hot Reload

---

## 🧩 Customization

### Modify Electron Main Process

Edit:
`src/main.js`

### Modify React Renderer

Edit:
`src/renderer.jsx`

---

## 🛠️ Troubleshooting

### Electron `.js` Extension Error?

Ensure **Electron Forge Vite Plugin** is installed correctly:

```bash
npm install --save-dev @electron-forge/plugin-vite
```

Electron Forge automatically handles `.js` in `main.js`.
If issues persist, check `forge.config.js` for correct plugin setup.

---

## 📝 License

[MIT License](LICENSE)

---

## ✨ Credits

- [Electron](https://www.electronjs.org/)
- [Vite](https://vitejs.dev/)
- [React](https://react.dev/)
- [Electron Forge](https://www.electronforge.io/)

---

## 🔗 Connect

For contributions, issues, or feature requests, [open an issue here](https://github.com/your-username/electron-react-starterkit/issues).

---

### ✅ Done!

Would you like me to export this into a ready-to-download `README.md` file or help you set up GitHub repo with correct badges/links?
