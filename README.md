# Zazoar Turborepo starter

## What's inside?

This Turborepo includes only the skeleton for a common monorepo, including workspaces like: apps, packages and devtools.

### Utilities

This Turborepo has some additional tools already setup for you:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [Biome](https://biomejs.dev/) for code linting and formatting
- [Lefthook](https://lefthook.dev/) for git hook management

### Build

To build all apps and packages, run the following command:

```
# NPM
npm run build

# Turbo
turbo run build
```

You can build a specific package by using a [filter](https://turborepo.com/docs/crafting-your-repository/running-tasks#using-filters):

```
# NPM
npm run build -- --filter=[pkg]

# Turbo
turbo run build --filter=[pkg]
```

### Develop

To develop all apps and packages, run the following command:

```
# NPM
npm run dev

# Turbo
turbo run dev
```

You can develop a specific package by using a [filter](https://turborepo.com/docs/crafting-your-repository/running-tasks#using-filters):

```
# NPM
npm run dev -- --filter=[pkg]

# Turbo
turbo run dev --filter=[pkg]
```
