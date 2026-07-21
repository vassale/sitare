<div align="center">
  <img src="./public/password.jpg" alt="Vira Stack Password" />
</div>

<br />

<div align="center">
  <a href="https://www.npmjs.com/package/@virastack/password">
    <img src="https://img.shields.io/npm/v/@virastack/password" alt="npm version" />
  </a>
  <a href="https://www.npmjs.com/package/@virastack/password">
    <img src="https://img.shields.io/npm/dt/@virastack/password" alt="npm downloads" />
  </a>
  <a href="https://bundlephobia.com/package/@virastack/password">
    <img src="https://img.shields.io/bundlephobia/minzip/@virastack/password" alt="bundle size" />
  </a>
</div>

<br />

# ViraStack Password Toggle

Fully accessible and customizable password visibility hook for React.

- ♿ **Accessibility First:** Fully ARIA compliant out of the box for better screen reader support.
- 🧩 **Framework Agnostic:** Logic is separated from React state, making it adaptable and clean.
- 🎨 **Smart Defaults:** Includes minimal SVG icons by default, so you can start using it immediately.
- 🔄 **Prop Merging:** Safely merges user props with hook-generated props to prevent overrides.
- 🔒 **State Sync:** Automatically handles `disabled` and `readOnly` states for a consistent UX.

### [Read the docs →](https://virastack.com/password/)

## Quick Start

```bash
npm install @virastack/password
```

```tsx
import { useViraPassword } from '@virastack/password';

function App() {
  const { inputProps, btnProps } = useViraPassword();

  return (
    <div>
      <input {...inputProps} placeholder="Enter password" />
      <button {...btnProps} />
    </div>
  );
}
```

## Explore the ViraStack Ecosystem

Discover all ViraStack tools, libraries, and boilerplates at [**virastack.com**](https://virastack.com).

## License

Licensed under the <a href="https://github.com/virastack/password/blob/main/LICENSE">MIT License</a>.

## Maintainer

A project by [**Ömer Gülçiçek**](https://omergulcicek.com)

[![Follow Ömer Gülçiçek](https://img.shields.io/github/followers/omergulcicek?label=Follow&style=social)](https://github.com/omergulcicek)
