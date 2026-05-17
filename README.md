# Markdown Viewer

![License](https://img.shields.io/badge/license-MIT-green)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

> A lightweight, offline-capable Markdown viewer with Mermaid diagram support, running entirely in a single HTML file.

## Features

- **Single HTML File** - No server required, just open and run
- **Offline Capable** - All dependencies bundled locally
- **Markdown Parsing** - Full support for standard Markdown syntax
- **Mermaid Diagrams** - Render flowcharts, sequence diagrams, pie charts, and more
- **Syntax Highlighting** - Code blocks with language-specific highlighting
- **Table of Contents** - Auto-generated navigation panel on the right side
- **Dark Mode** - Toggle between light and dark themes
- **i18n Support** - Switch between English and Chinese interface
- **Drag & Drop** - Open .md files by dragging them into the editor
- **Real-time Preview** - Live rendering as you type

## Quick Start

### Usage

1. Download or clone this repository
2. Open `markdown-viewer.html` in any modern browser
3. Start editing or drag & drop a `.md` file

### Try the Example

Open `example.md` to see all supported features in action.

## Interface

```
┌──────────────────────────────────────────────────────────────────────┐
│  Markdown Viewer    [Open File] [TOC] [EN/中文] [Theme]              │
├─────────────────────┬─────────────────────┬──────────────────────────┤
│                     │                     │                          │
│      Editor         │       Preview       │      Table of Contents   │
│                     │                     │        (Right Side)      │
│                     │                     │                          │
└─────────────────────┴─────────────────────┴──────────────────────────┘
```

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl/Cmd + O` | Open file |
| `Ctrl/Cmd + B` | Toggle navigation panel |

## Project Structure

```
markdown-viewer/
├── markdown-viewer.html    # Main application (single file)
├── example.md              # Example Markdown file
├── LICENSE                 # MIT License
├── js/
│   ├── marked.min.js       # Markdown parser
│   ├── mermaid.min.js      # Diagram renderer
│   └── highlight.min.js    # Syntax highlighter
└── css/
    └── github.min.css      # Code highlighting theme
```

## Supported Mermaid Diagrams

| Diagram Type | Syntax |
|--------------|--------|
| Flowchart | ` ```mermaid graph TD ... ``` ` |
| Sequence Diagram | ` ```mermaid sequenceDiagram ... ``` ` |
| Pie Chart | ` ```mermaid pie showData ... ``` ` |
| Class Diagram | ` ```mermaid classDiagram ... ``` ` |
| State Diagram | ` ```mermaid stateDiagram-v2 ... ``` ` |
| ER Diagram | ` ```mermaid erDiagram ... ``` ` |

## Technology Stack

| Component | Library | Purpose |
|-----------|---------|---------|
| Markdown Parser | [marked.js](https://marked.js.org/) | Parse Markdown to HTML |
| Diagram Renderer | [Mermaid](https://mermaid.js.org/) | Render diagrams from text |
| Syntax Highlighter | [highlight.js](https://highlightjs.org/) | Code block highlighting |

## Browser Support

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## License

[MIT License](LICENSE) © 2026 cheney
