# 🧩 Interactive Sudoku Web Application

A complete, self-contained, responsive Sudoku web app built with pure HTML5, CSS3, and vanilla JavaScript (zero external libraries or dependencies). Designed and developed for an HCI (Human-Computer Interaction) usability testing study.

---

## 🌟 Key Features

### 📐 Pre-Game Setup Screen
- Select between **3 Grid Sizes** before starting:
  - **4×4 Mini**: 2×2 subgrids, digits 1–4 *(fast, beginner and kid-friendly)*
  - **6×6 Junior**: 2×3 subgrids, digits 1–6 *(intermediate challenge)*
  - **9×9 Classic**: 3×3 subgrids, digits 1–9 *(traditional standard Sudoku)*
- Select between **3 Difficulty Tiers**: Easy, Medium, and Hard.
- Uniquely solvable generated puzzles via backtracking solver with uniqueness validation.
- Switch grid size or difficulty at any time using the in-game **⚙️ Setup** button.

### 🚨 Real-Time Multi-Sensory Conflict Feedback
- Highlights duplicate numbers in the same row, column, or subgrid block immediately.
- **Color-Blind Accessible (WCAG 1.4.1)**: Uses red background tint, dashed border outline, and a bold **!** badge in the cell corner.
- **Audio Feedback**: Synthesized Web Audio chime plays when a conflicting move is introduced.
- Clears immediately when conflicts are resolved.

### ✏️ Candidate Pencil / Notes Mode
- Toggle with the on-screen **✏️ Pencil** button or press keyboard shortcut **P**.
- Displays small candidate notes in a mini-grid inside each cell.
- Placing a confirmed number automatically clears candidate marks for that cell.

### ⏱️ Timer & Reset
- Accurate elapsed time counter in `MM:SS` format.
- Instant **↺ Reset** button resets player entries while keeping the current puzzle.

### 🎉 Victory Celebration
- **Web Audio Fanfare**: Harmonious, celebratory ascending arpeggio and triumph chord.
- **Fullscreen Confetti**: Dynamic HTML5 canvas particle explosion.
- **Board Ripple Animation**: Coordinated wave pop effect across all solved cells.
- **Victory Modal**: Displays total completion time with options to **Play Again** or **Change Setup**.

### 🎨 7 Animated Background Themes
Switch themes anytime using the **🎨 Theme** picker:
1. ☀️ **Classic**: Clean white/blue aesthetic
2. 🌙 **Midnight**: Dark slate with twinkling stars
3. 🌊 **Ocean**: Shifting deep blue gradients and ocean waves
4. 🌿 **Forest**: Layered greenery with floating leaf particles
5. 🌅 **Sunset**: Warm orange/pink sweep with horizontal rays
6. ✨ **Galaxy**: Deep space purple with nebula pulse and floating stars
7. 🌸 **Blossom**: Soft cherry pink with drifting petals

### 📖 Accessible "How to Play" Instructions Modal
- Opens automatically on first visit and accessible anytime via the **❓ Help** button.
- Fully keyboard accessible (`Escape` to close, modal focus trap).

---

## 🚀 Getting Started

Simply open `sudoku.html` in any modern web browser (Chrome, Edge, Firefox, Safari). No web server, Node.js, or build step required.

```bash
# Clone the repository
git clone <your-repo-url>

# Open directly in your browser
open sudoku.html       # macOS
start sudoku.html      # Windows
xdg-open sudoku.html   # Linux
```

---

## 📱 HCI Class Usability Activity

This project was built for usability evaluation under the DNSCIT HCI curriculum (**#ThisIsDNSCIT #HCI2**).
- Includes ready-to-test prototypes.
- Social media feedback questions tailored to conflict highlighting, pencil mode, setup screens, and win celebrations.

---

## 📄 License
MIT License

