<p align="center">
  <a href="https://uptop.xyz/" target="_blank">
    <img src="./.github/uptop.png" alt="Uptopicons" width="300">
  </a>

</p>

<p align="center">
  <a href="https://uptop.xyz"><strong>Browse at Uptop.xyz &rarr;</strong></a>
</p>

## Basic Usage

Both icon styles are preconfigured to be stylable by setting the `color` CSS property, either manually or using utility classes like `text-gray-500` in a framework like [Tailwind CSS](https://tailwindcss.com).

## React

First, install `@uptopicons/react` from npm:

```sh
npm install @uptopicons/react
```

Now each icon can be imported individually as a React component:

```js
import { HistoryIcon } from '@uptopicons/react/20/solid'

function MyComponent() {
  return (
    <div>
      <HistoryIcon className="h-6 w-6 text-blue-500" />
      <p>...</p>
    </div>
  )
}
```

Solid icons can be imported from `@uptopicons/react/20/solid`.

Icons use an upper camel case naming convention and are always suffixed with the word `Icon`.

[Browse the full list of icon names on UNPKG &rarr;](https://unpkg.com/browse/@uptopicons/react/20/solid/)

## License

This library is MIT licensed.
