# microhooks

A handful of React hooks I keep copy-pasting between projects

Started as a weekend hack, grew on me.

## Examples

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Highlights

- useLocalStorage with JSON serialization
- useMediaQuery SSR-safe
- Tiny: no dependencies besides React
- useDebounce with leading/trailing options

## Installation

```bash
npm install
npm test
```

## Project structure

```text
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
└── package.json
```

## Development

```bash
npm install
```

## License

MIT licensed, see LICENSE.
