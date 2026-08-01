<div align="center">

<a href="https://github.com/virastack/password" target="_blank" rel="noreferrer">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/virastack/password/main/assets/logo-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/virastack/password/main/assets/logo-light.png">
    <img src="https://raw.githubusercontent.com/virastack/password/main/assets/logo-light.png" alt="ViraStack Password" height="120" style="max-width: 100%;" />
  </picture>
</a>

*Fully accessible and customizable password visibility hook for React.*

[![ViraStack Password](https://img.shields.io/badge/ViraStack-Password-%23ff2056)](https://virastack.com/password/)
[![npm version](https://img.shields.io/npm/v/@virastack/password)](https://www.npmjs.com/package/@virastack/password)
[![npm downloads](https://img.shields.io/npm/dt/@virastack/password)](https://www.npmjs.com/package/@virastack/password)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/virastack/password/blob/main/LICENSE)
[![@virastack](https://img.shields.io/badge/-%40virastack-black?logo=x&logoColor=white)](https://x.com/virastack)

</div>

---

### [Read the full documentation →](https://virastack.com/password/)

## Why ViraStack Password?

- **Accessibility First:** Fully ARIA compliant out of the box for better screen reader support.
- **Framework Agnostic:** Logic is separated from React state, making it adaptable and clean.
- **Smart Defaults:** Includes minimal SVG icons by default, so you can start using it immediately.
- **Prop Merging:** Safely merges user props with hook-generated props to prevent overrides.
- **State Sync:** Automatically handles `disabled` and `readOnly` states for a consistent UX.

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

Licensed under the [MIT License](https://github.com/virastack/password/blob/main/LICENSE).

## Maintainer

A project by [**Ömer Gülçiçek**](https://omergulcicek.com)

[![Follow Ömer Gülçiçek](https://img.shields.io/github/followers/omergulcicek?label=Follow&style=social)](https://github.com/omergulcicek)
