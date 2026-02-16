---
title: Obsidian Mobile
---
# Obsidian Mobile Plugin

> Mobile UX enhancer for Obsidian: FAB gestures, context-aware toolbars, optimized search, and tab management. Built for seamless mobile note-taking.

![Obsidian Mobile Plugin](https://via.placeholder.com/800x400?text=Mobile+Plugin+Demo)

## About
Created by Justice Vellacott (Im The Justice Man), this plugin refines Obsidian's mobile experience with intuitive gestures and adaptive UI. Inspired by my coding roots and GUI standards passion, making high-abstraction tools that feel natural. v1.0: Focus on productivity without bloat.

- **GitHub**: [TheJusticeMan/obsidian-mobile-plugin](https://github.com/TheJusticeMan/obsidian-mobile-plugin) (Stars: 28 | Forks: 7)
- **License**: MIT
- **Install**: Via BRAT beta (Community Plugins → Add from GitHub URL)

## Key Features

### Gestures & FAB
- **Custom Gestures**: Draw shapes on FAB → Assign/execute commands (e.g., new note, search).
- **FAB Actions**: Tap (primary cmd), long-press (secondary), smart positioning.
- **Haptic Feedback**: Vibrate on interactions.

### Context-Aware Toolbars
Dynamic bottom bars for editing contexts (Selection, List, Task, Heading, Code, Table, etc.).

- **Library & Bindings**: Build reusable command sets; auto-merge for contexts.
- **Icons & Scroll**: Lucide icons, horizontal scrolling, swipe-to-expand.
- **Smart UI**: Hides unavailable cmds; preserves focus/keyboard.

### Mobile Search
- Infinite scroll previews with dates/context menus.
- **Selection Mode**: Bulk ops (select all, delete, plugin extensibility).
- **Folder Toggle**: Backspace for file/folder filter.
- Open tabs integration; auto-focus.

### Tabs & Navigation
- **Tabs View**: List with icons/close buttons; drag-drop reorder.
- **Gestures**: Swipe right to close; swipe edges for sidebar tabs.
- **Tablet Mode**: Force UI on phones; wake lock toggle.

## Commands
- **Core**: Open mobile search, toggle tablet mode, FAB press/long-press.
- **Navigation**: Up/down/left/right cursor moves.
- **Selection**: Expand/contract, select word/sentence/line, progressive "Select More".

## Installation (BRAT)
1. Install BRAT plugin in Obsidian.
2. BRAT: Add beta → `https://github.com/TheJusticeMan/obsidian-mobile-plugin`.
3. Enable & configure in Settings.

**Settings Highlights**:
- Toggle toolbars/FAB; assign FAB cmds.
- Gesture management; icons/haptics.
- Toolbar library/bindings.

## Examples
- **Gesture**: Draw circle on FAB → Toggle bold.
- **Toolbar**: In list context → Quick bullet/task cmds.
- **Search**: Long-press result → Bulk select/delete.
- **Tabs**: Swipe tab → Close; drag → Reorder.

## Development
Node.js 16+: `npm install` → `npm run dev/build`.  
Structure: `src/main.ts`, `features/fab.ts`, `views/SearchLeaf.ts`.

## Why It Matters
Streamlines mobile workflows for creators like me, pair with Pure Chat LLM for AI-enhanced notes. Ethical, accessible: Focus on user control and positive impact.

[GitHub Issues](https://github.com/TheJusticeMan/obsidian-mobile-plugin/issues/new)

Oct 2024 | Justice Vellacott | 🇨🇦