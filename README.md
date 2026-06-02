# Fetcher

A simple `neofetch` alternative, written in Python.

## Features

1. **Customizability:** Easily add or remove elements and recompile to your liking.
2. **Portability:** Lightweight and comes in at less than 20 Megabytes.
3. **Custom ASCII Art:** Full support for custom ASCII art layouts.

2. **Portability:** Lightweight and comes in at less than 20 Megabytes.
3. **Custom ASCII Art:** Full support for custom ASCII art layouts.

![Preview](./preview.png)

### With ASCII Art
![ASCII Preview](./ascii-preview.png)

---

## How to Use

### 0. Install deps
#### Our deps are 
1. Python
2. pipx
install them on arch (other distros may vary):
```bash
sudo pacman -S python pipx
```
### 1. Clone the repository & enter its directory
```bash
git clone https://github.com/hamzadotjs/Fetcher.git
cd Fetcher
```

### 2. Install with pip
```bash
pip install -e .
```

![Preview](./preview.png)

### With ASCII Art
![ASCII Preview](./ascii-preview.png)

---

## How to Use

### 1. Clone the repository & enter its directory
```bash
git clone https://github.com/hamzadotjs/Fetcher.git
cd Fetcher
```

### 2. Install with pip
```bash
pip install -e .h
pip install -e .

```

### 3. Enjoy!
Simply run `fetcher` in your terminal.

---

## Alternative: Standalone Binary

If you prefer a single executable instead:

### 1. Install PyInstaller
```bash
pipx install pyinstaller
```

### 2. Build Fetcher
```bash
pyinstaller --onefile main.py
```

### 3. Add to PATH
```bash
ln -sf ~/Fetcher/dist/main ~/.local/bin/fetcher
```
