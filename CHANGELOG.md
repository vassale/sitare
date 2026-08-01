# Changelog

## [v1.0.2] - 2026-08-01

### Documentation

- **README**: Removed the Bundlephobia badge (Shields.io often rate-limits the upstream API on npm).

## [v1.0.1] - 2026-08-01

### Documentation

- **README logos**: Fixed broken npm README images. Light/dark logo assets now load from `assets/logo-light.png` and `assets/logo-dark.png` via raw GitHub URLs.

## [v1.0.0] - 2026-07-22

### Initial Release

- **@virastack/password**: A fully accessible and customizable password visibility hook for React is now live!
- **Architecture**: Logic is separated from React state, making it adaptable and clean.
- **Hook**: `useViraPassword` provides a simple, robust "React-First" solution.
- **React Server Components**: Added `'use client'` directive for Next.js App Router and TanStack Start compatibility.

### Features

- **Full Type Support**: Enhanced TypeScript definitions for better developer experience.
- **Accessibility First**: Fully ARIA compliant out of the box for better screen reader support.
- **Smart Defaults**: Includes minimal SVG icons by default, so you can start using it immediately.
- **Customizable**: Use your own icons or UI components to match your design system.
- **Prop Merging**: Safely merges user props with hook-generated props to prevent overrides.
- **State Sync**: Automatically handles `disabled` and `readOnly` states for a consistent UX.
