# Tracpoint monorepo powered by turborepo, React, and TypeScript.

## What's inside?

This monorepo includes the following packages/apps:

### Shared "Packages"

- `@repo/api`: API functions used throughout the monorepo using `@tanstack/react-query`
- `@repo/assets`: Shared assets used throughout the monorepo
- `@repo/config`: Configuration files used throughout the monorepo
- `@repo/react-hooks`: React hooks used throughout the monorepo
- `@repo/types`: Type declarations used throughout the monorepo
- `@repo/utils`: Utility functions used throughout the monorepo
- `@repo/stylesheets`: Tailwind setup and global theme styles
- `@repo/storybook`: Shared components used throughout the monorepo

Each package/app is 100% [TypeScript](https://www.typescriptlang.org/).

### Utilities

This Turborepo has some additional tools already setup for you:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Prettier](https://prettier.io) for code formatting

### Tailwind CSS (4.0.0-alpha.15 at the time of writing)

To enable support for VS code extension "Tailwind CSS IntelliSense" you need to do the following:

1. Switch the extension to pre-release version
2. In your project vscode settigns .vscode -> settings.json add

```json
{
  "tailwindCSS.experimental.configFile": "./packages/stylesheets/tailwind.css"
}
```

### Build

To build all apps and packages, run the following command:

```
npm run build
```

### Develop - Local

To develop all apps and packages in a "local" way, run the following command:

```
npm run dev
```

### Develop - Module Federation

To develop all apps and packages with module federation, run the following command:

```
npm run preview
```

## Useful Links

- [Deployed Site](https://uat.tracpoint.app/)

Learn more about the power of Turborepo:

- [Tasks](https://turbo.build/repo/docs/core-concepts/monorepos/running-tasks)
- [Caching](https://turbo.build/repo/docs/core-concepts/caching)
- [Remote Caching](https://turbo.build/repo/docs/core-concepts/remote-caching)
- [Filtering](https://turbo.build/repo/docs/core-concepts/monorepos/filtering)
- [Configuration Options](https://turbo.build/repo/docs/reference/configuration)
- [CLI Usage](https://turbo.build/repo/docs/reference/command-line-reference)
