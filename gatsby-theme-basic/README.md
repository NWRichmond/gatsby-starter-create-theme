# A Flavorless, Empty Theme

## Using the Theme

To create a new (minimal) Gatsby project which uses this theme:

```bash
mkdir my-website
cd my-website
npm init
touch gatsby-config.js

# install gatsby-theme-basic and its dependencies
npm install gatsby react react-dom gatsby-theme-basic
```

Next, add `gatsby-theme-basic` to the site's `gatsby-config.js`:

```js
module.exports = {
  plugins: [
    {
      resolve: "gatsby-theme-basic",
      options: {}
    }
  ]
};
```

Now start the development server:

```bash
npm run develop
```

## Publishing Your Theme

After developing your theme, you may want to share it with the rest of the Gatsby community. To do so, please refer to the [Gatsby docs](https://www.gatsbyjs.org/contributing/submit-to-plugin-library/#publishing-a-plugin-to-the-library).
