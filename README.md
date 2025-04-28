# 📋 Tabulara

**Notion-style tables, made easy.**  
Beautiful, flexible, and lightweight JavaScript tables for modern web apps. More at https://tabulara.ikigai.systems.

![illustration.png](https://tabulara.ikigai.systems/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fnotion-table-example1.23bf1622.png&w=1080&q=75)

## ✨ Features

- 🖌️ **Notion-like aesthetics** — Clean, minimal, and delightful by default.
- ⚡ **Lightweight** — Zero external dependencies.
- 🎛️ **Fully customizable** — Themes, column types, custom cell renderers.
- ✏️ **Editable tables** — Enable inline editing with one config switch.
- 🔥 **Fast performance** — Handles large datasets smoothly.
- 🎯 **Developer-friendly API** — TypeScript support included.

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

## 📅 Current Status
🚧 **Tabulara is currently in pre-release development.**
Subscribe to updates [here](https://tabulara.ikigai.systems/get-started) to be notified when we launch!

## 📣 Stay Tuned!
"Tabulara is built for developers who care about great user experiences.
Join us on this journey — and build better tables today. 🚀"
