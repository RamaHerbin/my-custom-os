# My Custom OS

A web-based operating system that delivers a full desktop experience in the browser.

## Concept

My Custom OS simulates a desktop environment directly in the browser, with window management, a taskbar, a file system, and built-in applications.

## Core Features

- **Desktop** - Wallpaper, icons, right-click context menu
- **Window Manager** - Draggable, resizable, minimizable, maximizable windows with z-index management
- **Taskbar** - Running apps, system tray, clock, start menu
- **File System** - Virtual file system (in-memory or localStorage-based)
- **Built-in Apps** - Terminal, text editor, file explorer, settings, browser

## Tech Stack

- **Framework**: React + TypeScript
- **Styling**: Tailwind CSS
- **State Management**: Zustand
- **Build Tool**: Vite

## Getting Started

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build
```

## Project Structure

```
src/
  components/
    Desktop/        # Desktop surface, icons, wallpaper
    Window/         # Window chrome, drag/resize logic
    Taskbar/        # Taskbar, start menu, system tray
    Apps/           # Built-in applications
  store/            # Zustand stores (windows, files, settings)
  hooks/            # Custom React hooks
  types/            # TypeScript type definitions
  utils/            # Helpers and utilities
```

## Roadmap

1. Desktop shell (desktop + taskbar + window manager)
2. Virtual file system
3. Built-in apps (terminal, text editor, file explorer)
4. Theming and settings
5. App SDK for third-party apps
