# Git Viz — Interactive Git Visualizer 🚀

A tiny, single-page HTML/CSS/JS app to help beginners understand Git concepts visually — commits, branches, merges, and HEAD — with simple animations. Everything is in English and designed for clarity and cleanliness.

![Git Viz Interface](https://img.shields.io/badge/Status-Active-success)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-blue)
![Pure JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow)

---

## 🎯 Why Git Viz?

- **Learning Git is easier** with visuals and playful interactions
- **Great for first-time coders** and vibe coders who learn by exploring
- **One page, immediate feedback**, friendly explanations
- **No build tools, no framework** — open in a browser and play

---

## ✨ Features (Consolidated)

This repository consolidates the best contributions from multiple development branches:

### 🎯 **Auto-Switch on Branch Creation**
When you create a new branch, Git Viz automatically switches to it — just like `git checkout -b` in real Git. No more manual checkout!

**Origin:** `genspark_ai_developer` branch

### 📊 **Repository Statistics**
Real-time statistics showing:
- Total number of commits
- Total number of branches

**Origin:** Master branch enhancement

### 🎨 **Dynamic HEAD Color Indicator**
The HEAD indicator changes color based on the current branch, making it visually clear which branch you're on.

**Origin:** Master branch enhancement

### 💬 **Interactive Commit Message Dialog**
Click any commit to edit its message with:
- **Quick defaults:** fix, feature, docs, refactor, chore, test
- **Keyboard shortcuts:** Enter to save, Esc to cancel
- **Visual commit IDs** displayed inside commit circles

**Origin:** `chore/change-accent` branch

### 📜 **Independent Right Panel Scroll**
The command history panel scrolls independently from the graph, making it easier to review long histories.

**Origin:** `feature/right-panel-scroll` branch

---

## 🚀 Getting Started (No Build Required!)

### Option 1: Direct Open
Simply open `index.html` in your browser — no server needed!

### Option 2: Local Server
```bash
# Clone the repository
git clone https://github.com/danielbarboni/git-viz.git
cd git-viz

# Start a simple HTTP server
python3 -m http.server 8000

# Open in browser
open http://localhost:8000
```

Or use any VS Code "Live Server" extension.

---

## 🎮 How to Use

### Basic Operations

1. **Add Commit** — Creates a new commit on the current branch
2. **Create Branch** — Creates and automatically switches to a new branch
3. **Checkout** — Switch between existing branches
4. **Merge** — Merge another branch into the current branch
5. **Reset** — Clear the repository and start fresh
6. **Undo Last** — Undo the most recent operation

### Interactive Features

- **Click any commit** to open the edit dialog and change its message
- **Use quick defaults** for conventional commit formats
- **View command history** in the right panel
- **Watch the graph animate** as you perform operations

---

## 🏗️ Technical Stack

- **Pure HTML5** — No templating engines
- **Vanilla CSS3** — No preprocessors
- **Plain JavaScript (ES6)** — No frameworks
- **SVG Graphics** — For the commit graph (easy to animate and style)

### Why No Dependencies?

This project is intentionally simple to:
- Maximize accessibility for beginners
- Minimize complexity for learning
- Ensure it works anywhere, instantly
- Demonstrate pure web technologies

---

## 📂 Project Structure

```
git-viz/
├── index.html      # Single page app shell, toolbar, and graph container
├── styles.css      # Layout, palette, micro-interactions
├── app.js          # State management + rendering + interactions
├── specs.md        # Original project specifications
└── README.md       # This file
```

---

## 🎨 Visual Model

- **Nodes** = commits
- **Lanes** = branches (e.g., `master`, `feature/x`)
- **HEAD pointer** shows current branch with dynamic color
- **Merge** = two lines joining into one node
- **Commit IDs** displayed inside circles for clarity

---

## 🔄 Consolidation History

This repository underwent a professional branch consolidation process to integrate the best features from multiple development branches:

### Integrated Branches

| Branch | Feature | Status |
|--------|---------|--------|
| `genspark_ai_developer` | Auto-switch on branch creation | ✅ Merged |
| Master enhancements | Repository statistics + HEAD color | ✅ Integrated |
| `chore/change-accent` | Commit message dialog | ✅ Cherry-picked |
| `feature/right-panel-scroll` | Independent panel scroll | ✅ Previously merged |

### Excluded Branches

| Branch | Reason |
|--------|--------|
| `feat/claude-redesign` | Removed important features (stats, HEAD color) |

The consolidation ensured:
- ✅ No feature conflicts
- ✅ No code duplication
- ✅ Clean merge history
- ✅ All functionality preserved

---

## 🎯 Target Audience

- **Beginners** starting with Git and version control
- **Vibe coders** who prefer discovery over dense docs
- **Instructors** who want a quick visual demo
- **Visual learners** who benefit from interactive examples

---

## 🤝 Contributing

Contributions are welcome! To maintain the project's simplicity:

1. Keep it vanilla (no frameworks/build tools)
2. Focus on educational value
3. Test in multiple browsers
4. Follow the existing code style
5. Update documentation

### Development Workflow

```bash
# Create a feature branch
git checkout -b feature/your-feature-name

# Make your changes
# ... code ...

# Commit with conventional commits
git commit -m "feat: add your feature description"

# Push to your fork
git push origin feature/your-feature-name

# Create a Pull Request
```

---

## 📜 License

This project is open source and available for educational purposes.

---

## 🙏 Acknowledgments

- Original concept by Rafael Quintanilha
- Multiple contributors from various feature branches
- Consolidated and maintained by Daniel Barboni

---

## 📞 Support

- **Issues:** Report bugs or request features via GitHub Issues
- **Discussions:** Share ideas in GitHub Discussions
- **Fork:** Feel free to fork and customize for your needs

---

## 🔗 Links

- **Repository:** [github.com/danielbarboni/git-viz](https://github.com/danielbarboni/git-viz)

---

**Made with ❤️ for Git learners everywhere**

