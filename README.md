<div align="center">

# ⌨️ Mert Studio Code · Web Edition

**The first editor for the DORUK language, a Turkish-keyword code editor built with React and Electron**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-desktop-47848F?style=flat-square&logo=electron&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white)

[Features](#-features) · [Run it](#-run-it) · [Türkçe](#-türkçe) · [➡️ v2 (C++ engine + Qt IDE)](https://github.com/Soap2647/Mert-Studio-Code-v2)

</div>

---

This is version 1 of **Mert Studio Code**, a lightweight editor for **DORUK**, a programming language
whose keywords are Turkish (`eğer`, `döngü`, `yazdır` …). It runs in the browser through Vite or as a
desktop app through Electron.

> [!TIP]
> The language later got a full C++ implementation (lexer, parser, semantic analyzer, interpreter) and a
> native Qt IDE. See **[Mert-Studio-Code-v2](https://github.com/Soap2647/Mert-Studio-Code-v2)**.

## ✨ Features

- **Turkish syntax highlighting** tuned for DORUK keywords.
- **Themes**: switch between dark and light editor themes.
- **Settings modal** for font and editor preferences.
- **Web and desktop**: the same React code runs in a browser tab or as an Electron window.

## 🚀 Run it

```bash
npm install
npm run dev            # web version on http://localhost:5173
npm run electron:dev   # desktop app (Electron + Vite dev server)
npm run electron:dist  # packaged desktop build
```

## 📁 Project structure

```
src/
├── components/   TurkceKodEditoru (editor), ThemeSelector, SettingsModal, editorUtils
├── App.jsx
└── main.jsx
electron/         main.cjs, preload.cjs
```

## 🇹🇷 Türkçe

**Mert Studio Code**'un ilk sürümü: Türkçe anahtar kelimeli **DORUK** dili için React, Vite ve Electron ile
yazılmış bir kod editörü. Sözdizimi renklendirme, tema seçimi ve ayarlar içerir. Hem tarayıcıda hem masaüstünde
çalışır. Dilin C++ motoru ve Qt IDE'si için: [Mert-Studio-Code-v2](https://github.com/Soap2647/Mert-Studio-Code-v2).

---

<div align="center"><sub>Built by <a href="https://github.com/Soap2647">Mert Yasin Yılmaz</a></sub></div>
