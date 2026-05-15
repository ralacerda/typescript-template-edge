# Node Typescript Playground Template (Edge)

A modern, high-performance template for Node.js with TypeScript.
This "Edge" version uses the latest tools and Node.js features.

## Features

- **Node.js 26**: Utilizing the latest runtime features.
- **TypeScript 6**: Cutting-edge type safety and performance.
- **Oxlint**: Ultra-fast linting (replacing ESLint).
- **Oxfmt**: Ultra-fast formatting (replacing Prettier).
- **pnpm 11**: The latest in fast, disk-efficient package management.

## How to use

Use the command to [`giget`][giget] download the latest commit.

```sh
npx giget gh:ralacerda/typescript-template-edge new-project-name
```

You can include the `--install` flag to install dependencies after cloning.

```sh
npx giget --install gh:ralacerda/typescript-template-edge new-project-name
```

### Installation

```sh
pnpm i
```

### Development

```sh
# Start in watch mode
pnpm dev

# Run the code once
pnpm start
```

### Linting & Formatting

```sh
# Lint with oxlint
pnpm lint

# Format with oxfmt
pnpm format
```

[giget]: https://github.com/unjs/giget
