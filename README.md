# FlowchartStudio
A simple Flowchart studio which generates the flowchart using mermaid markdown in your browser


# 🎨 Flowchart Studio

Welcome to the **Flowchart Studio**! This is a minimal, lightweight, and offline-capable interactive web application built to create, preview, and export high-resolution Mermaid.js diagrams. 

It is styled using a modern, cozy dark mode palette (`#0f172a` midnight navy and `#1e293b` slate) designed to stay easy on the eyes during late-night charting sessions.

---

## ✨ Features

* **Real-Time Auto Rendering:** The diagram updates instantly as you type. No manually hitting a refresh button.
* **Intelligent Markdown Uploads:** Click the **📁 Upload .md** button to drop in any standard Markdown file. The app automatically scans the file, extracts the text inside the ` ```mermaid ` code block, and loads it into the editor.
* **Multi-Color Arrow Styling:** Supports custom link overrides natively using Mermaid's `linkStyle` grammar. 
* **High-Resolution PNG Export:** Click **💾 Save PNG** to download a crisp image of your flowchart with a matching dark background background, ready to use in your presentations or documentation.
* **Typo Protection:** If there is a formatting or syntax layout issue in your Mermaid string, the compiler catches it gracefully behind the scenes rather than breaking the UI.

---


🛠️ Built With
Mermaid.js (v9.4.3) - Generation & layout engine.

Cloudflare CDN - High-availability global asset distribution.

Pure HTML5, CSS3, and Vanilla JavaScript.
