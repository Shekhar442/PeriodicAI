# Periodic Table of AI Technologies

A single-page reference that presents AI technologies in a periodic-table style layout. Explore **54 elements** across models, techniques, architectures, training methods, applications, tools, metrics, and core concepts—all in one place.

## Features

- **Periodic-style grid** — 54 AI “elements” arranged by category (Foundation Models, Techniques, Architectures, Training, Applications, Tools, Metrics, Core Concepts)
- **Search** — Filter by name or symbol (e.g. GPT, RAG, BERT, Embeddings)
- **Category filters** — All, Models, Techniques, Architectures, Training, Applications, Tools, Metrics, Concepts
- **Legend** — Color-coded categories for quick scanning
- **Detail modal** — Click any element for:
  - Definition and use cases  
  - Key features  
  - Related concepts  
  - **Understand the concept** — Official link to documentation, papers, or articles (OpenAI, Google, Hugging Face, arXiv, Wikipedia, etc.)
- **Architecture diagrams** — Category-level diagrams when viewing an element or a filter
- **Responsive** — Layout adapts to screen size; table scrolls horizontally on narrow viewports
- **No build step** — Pure HTML, CSS, and JavaScript in one file

## How to Run

1. Open `index.html` in a modern browser (double-click or **File → Open**).
2. Or serve the folder locally, for example:
   ```bash
   python3 -m http.server 8000
   ```
   Then visit `http://localhost:8000`.

No npm, Node, or other dependencies are required.

## Tech

- Single self-contained **HTML** file
- **CSS** (custom properties, grid, flexbox, responsive breakpoints)
- **Vanilla JavaScript** (no frameworks)
- Fonts: [Outfit](https://fonts.google.com/specimen/Outfit), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts

## Project Structure

```
PeriodicAI/
├── index.html   # App (HTML + CSS + JS)
└── README.md    # This file
```

## License

Use and modify as you like.
