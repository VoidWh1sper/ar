# ar — Advanced Directory Tree Visualization Tool

A powerful command-line utility for displaying directory structures with syntax highlighting and export capabilities. Designed for developers and system administrators who need clear, customizable filesystem visualization.

## ✨ Key Features

- **Professional Syntax Highlighting**:
  - 🔵 Cyan — Directories
  - 🟡 Yellow — Regular files
  - 🟢 Green — Executable files (marked with `*`)
- **Recursive Traversal** with intelligent indentation
- **Export Functionality** — Save directory trees to `~/structure.txt` using `-f` flag
- **Path Flexibility** — Supports absolute and relative paths
- **Tree-Compatible Formatting** — Familiar `tree` command style with enhanced visuals

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/VoidWh1sper/ar.git
cd ar

# Make executable
chmod +x ar

# (Optional) Install system-wide
sudo cp ar /usr/local/bin/ar
