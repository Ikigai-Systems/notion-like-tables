# 📋 Tabulara

**Notion-style tables, made easy.**  
Beautiful, flexible, and lightweight JavaScript tables for modern web apps.

## ✨ Features

- 🖌️ **Notion-like aesthetics** — Clean, minimal, and delightful by default.
- ⚡ **Lightweight** — Zero external dependencies.
- 🎛️ **Fully customizable** — Themes, column types, custom cell renderers.
- ✏️ **Editable tables** — Enable inline editing with one config switch.
- 🔥 **Fast performance** — Handles large datasets smoothly.
- 🎯 **Developer-friendly API** — TypeScript support included.

## 🚀 Installation

Using npm:

```bash
npm install tabulara
```

Or via CDN:
```html
<script src="https://cdn.jsdelivr.net/npm/tabulara"></script>
```

## 🛠️ Quick Start

```javascript
import { Table } from 'tabulara';

const table = new Table({
  element: '#my-table',
  columns: [
    { name: 'Task', type: 'text' },
    { name: 'Status', type: 'select', options: ['Todo', 'In Progress', 'Done'] },
    { name: 'Priority', type: 'tags' },
  ],
  data: [
    { Task: 'Fix login bug', Status: 'In Progress', Priority: ['High'] },
    { Task: 'Write docs', Status: 'Todo', Priority: ['Medium'] },
  ],
});
```

In your HTML
```html
<div id="my-table"></div>
```

## 📚 Documentation
Full documentation is coming soon!
In the meantime, check out:

- [Quickstart Guide (Coming Soon)]()
- [API Reference (Coming Soon)]()
- [Live Demo (Coming Soon)]()

## 📅 Current Status
🚧 **Tabulara is currently in pre-release development.**
Subscribe to updates [here](https://tabulara.ikigai.systems/get-started) to be notified when we launch!

## 📣 Stay Tuned!
"Tabulara is built for developers who care about great user experiences.
Join us on this journey — and build better tables today. 🚀"
