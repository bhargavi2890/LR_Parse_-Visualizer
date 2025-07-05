# LR_Parse_-Visualizer
LR Parser Visualizer is an interactive tool designed to help users understand how LR(0), SLR, and LR(1) parsing works under the hood. It visually breaks down the parsing process, state transitions, and conflict resolutions—making compiler design concepts far more intuitive and hands-on.

This project is a visual companion for learning and debugging LR parsing techniques, including LR(0), SLR(1), and LR(1) parsers. Designed for students, educators, and language enthusiasts, it transforms parsing theory into dynamic animations and state-driven visuals.

## 🚦 Features

- 🧠 **Grammar Input Support**: Enter your own context-free grammar to generate parsing tables and automata.
- 🔄 **LR(0), SLR, and LR(1) Modes**: Toggle between parser types to understand their structural differences.
- 👁️ **State-by-State Visualization**: Watch how the parser builds its state machine and handles shift/reduce actions.
- ⚠️ **Conflict Detection**: Instantly see when and where conflicts arise, with contextual explanations.
- 💾 **Export Options**: Save parsing tables or automata graphs for offline analysis or report generation.

## 🛠 Tech Stack

- **Frontend**: HTML, CSS, JavaScript (React.js or Vanilla JS with D3.js for graph rendering)
- **Backend (optional)**: Node.js / Flask (for grammar validation or extended parsing logic)
- **Visualization Tools**: D3.js, Cytoscape.js or Mermaid for state machine and table rendering
