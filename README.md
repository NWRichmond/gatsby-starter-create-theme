# Gatsby Starter Create Theme

This Gatsby starter helps you scaffold a [Gatsby theme ](https://www.gatsbyjs.org/docs/themes) connected to an example project.

This starter is inspired by [gatsby-starter-theme-workspace](https://github.com/gatsbyjs/gatsby-starter-theme-workspace), which uses [Yarn workspaces](https://classic.yarnpkg.com/en/docs/workspaces) to connect your theme to an example project. Instead of Yarn workspaces, this starter uses [Lerna](https://github.com/lerna/lerna) handle the coupling of your theme and example project.

## Quick Start

```bash
# connect the theme and the example site
npm run connect

# spin up the example site
cd example
npm run develop
```

If you encounter any issues with the connection between the theme and the example site:

```
npm run disconnect

npm run connect
```

This will break and re-establish the link between the theme and the example site.

## Project Structure

```text
.
├── README.md
├── gatsby-theme-minimal
│   ├── README.md
│   ├── gatsby-config.js
│   ├── index.js
│   └── package.json
├── example
│   ├── README.md
│   ├── gatsby-config.js
│   ├── package.json
│   └── src
├── package.json
└── lerna.json
```

### `gatsby-theme-basic`

This directory is home to a basic, flavorless Gatsby theme. But your big ideas are far from basic, so you'll want to rename this to `gatsby-theme-{something-better}`.

**IMPORTANT**: When you change the name of the theme directory, be sure to also change the theme name referenced in:

- `lerna.json`
- `example/package.json`

### `example`

This is an example site which uses your theme. What you see here should reflect what any user sees when they install your theme from npm.
