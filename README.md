# Kanban Board

A modern and interactive Kanban board application built with React, TypeScript, and Vite. This project implements drag-and-drop functionality using `@dnd-kit` and features a clean, responsive design with Tailwind CSS.

## Features

- 📋 Drag and drop tasks between columns
- ✨ Modern and responsive UI
- ➕ Add new tasks to any column
- 🗑️ Delete tasks
- 🎨 Clean design with Tailwind CSS
- 🚀 Built with performance in mind

## Tech Stack

- **Framework:** React 19
- **Build Tool:** Vite
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Drag & Drop:** @dnd-kit/core & @dnd-kit/sortable
- **Utility:** tailwind-merge

## Getting Started

### Prerequisites

- Node.js (Latest LTS version recommended)
- npm or yarn

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Jv2350/kanban
   cd kanban
   ```

2. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open your browser and visit `http://localhost:5173`

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the project for production
- `npm run lint` - Run ESLint to check code quality
- `npm run preview` - Preview the production build locally

## Project Structure

```
src/
├── components/        # React components
│   ├── KanbanBoard.tsx
│   ├── ColumnContainer.tsx
│   └── TaskCard.tsx
├── icons/            # SVG icons as React components
├── assets/           # Static assets
├── App.tsx           # Main application component
└── types.ts          # TypeScript type definitions
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
