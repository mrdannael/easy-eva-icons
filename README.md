# Easy Eva Icons

![eva-icons](.github/logo.jpeg)

<p align="center">
    <a href="https://github.com/tailwindlabs/heroicons/releases"><img src="https://img.shields.io/npm/v/easy-eva-icons" alt="Latest Release"></a>
    <a href="https://github.com/mrdannael/easy-eva-icons/blob/master/LICENSE"><img src="https://img.shields.io/npm/l/easy-eva-icons.svg" alt="License"></a>
</p>

**Eva Icons** is a pack of more than 480 beautifully crafted Open Source icons for common actions and items.

## React

First, install `@easy-eva-icons/react` from npm:

```
[npm]
npm i @easy-eva-icons/react

[yarn]
yarn add @easy-eva-icons/react
```

Then each icon can be imported individually as a React component:

```jsx
import { Archive } from '@easy-eva-icons/react';

function MyComponent() {
  return (
    <div>
      <Archive />
    </div>
  );
}
```

Outline versions of icons are available under `{IconName}Outline` name:

```jsx
import { ArchiveOutline } from '@easy-eva-icons/react';

function MyComponent() {
  return (
    <div>
      <ArchiveOutline />
    </div>
  );
}
```

Icons accepts common SVG properties.

## Roadmap

- [ ] Icon components for Vue.js
- [ ] Animations for icons (zoom, pulse, shake and flip)

## License

This library is MIT licensed.
