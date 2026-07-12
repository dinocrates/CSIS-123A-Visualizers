# CSIS 123A Visualizers

Interactive, step-by-step visualizers for CSIS 123A (C++ Programming Fundamentals). Each tool is a single self-contained HTML file — no build step, no dependencies.

**Live site:** https://dinocrates.github.io/CSIS-123A-Visualizers/

## Tools

| Unit | Tool | File |
|------|------|------|
| Unit 11 — Recursion | Recursion Explorer (DEBUG.EXE) | [visualizers/recursion-explorer.html](visualizers/recursion-explorer.html) |

The landing page ([index.html](index.html)) shows a tile for each tool with a description, the list of included demos, a launch link, and copy-able iframe embed code for Canvas or any web page.

## Adding a new visualizer

1. Drop the self-contained HTML file into `visualizers/`.
2. Add an entry to the `TOOLS` array near the top of the `<script>` in `index.html` (unit, title, file path, description, demo list). The tile, embed code, and tool count are generated from that entry automatically.
