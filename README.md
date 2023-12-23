# Vite Library Starter

## Features

- Vite
- Pnpm
- ESLint
- Prettier
- Vitest
- Husky
- CommitLint

## Installation

If you have node v16 or later then use the below command to install pnpm

```sh
corepack enable
corepack prepare pnpm@latest --activate
```

otherwise see the [pnpm install guide](https://pnpm.io/installation)

Install dependencies

```sh
pnpm install
```

# Developing

## Bundler

Vite is used as the bundler. It is a fast bundler that uses esbuild under the hood. It also supports hot module reloading.

## Package Manager

[pnpm](https://pnpm.js.org/) is used as the package manager.

## Linting

ESLint is used for linting

```sh
pnpm lint
```

## Formatting

Prettier is used for formatting

```sh
pnpm format
```

## Testing

Vitest is used for testing. It is syntax compatible with Jest but is faster and has better error messages.

```sh
pnpm test
```

## Pre-Commit Hook

Husky is used for pre-commit hook. it ensures that the code is linted and formatted before committing. It also ensures that the commit message is formatted correctly

```sh
pnpm prepare
```

## Commit Message Format

CommitLint is used for commit message linting.
[Commit Convention](<[2](https://github.com/conventional-changelog/commitlint/tree/master/%40commitlint/config-conventional)>)

```
<type>(<scope?>): <subject>
```

# Publishing

Set the name of the package in package.json

```json
{
  "name": "my-package"
}
```

Set the author of the package in package.json

```json
{
  "author": { "name": "John Doe", "url": "https://example.com" }
}
```

Set the version of the package in package.json

```json
{
  "version": "0.0.1"
}
```

Set the private field to false in package.json

```json
{
  "private": false
}
```

Publish the package

```sh
pnpm publish
```

# Credits

This project is based on [ts-library](https://github.com/vinomanick/ts-library)
