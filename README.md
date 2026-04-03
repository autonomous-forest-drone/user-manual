# Autonomous Forest Drone — User Manual

This repository contains the user manual for the autonomous forest drone system developed as a bachelor's thesis project in Computer Science and Engineering with a specialization in IoT.

## Authors

- Elina Rosato
- Danielis Maizelis

## About

The user manual is written in LaTeX (`main.tex`) and covers installation, setup, operation, troubleshooting, and technical reference for the autonomous forest drone system.

## Building the Manual

### 1. Install a LaTeX Distribution

**macOS**
```bash
brew install --cask mactex
```

**Windows**

Download and install [MiKTeX](https://miktex.org/download).

**Linux**
```bash
sudo apt install texlive-full   # Debian/Ubuntu
sudo dnf install texlive-scheme-full  # Fedora
```

### 2. VS Code (Recommended)

Install the [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) extension. Once installed, open `main.tex` and click the **Build LaTeX project** button in the top-right toolbar, or use the command palette (`Ctrl+Shift+P` / `Cmd+Shift+P`) and run **LaTeX Workshop: Build LaTeX project**.

### 3. Command Line

```bash
pdflatex main.tex
```

For more guidance on how to run and compile LaTeX locally, watch this video: [Easy LaTeX Documents in VSCode
](https://www.youtube.com/watch?v=Mty0vHb0knI)
