# gatsby-plugin-favicon
Generates all favicons for Web, Android, iOS, ...

## Install
`yarn add gatsby-plugin-favicon`

## How to use
1. Include the plugin in your `gatsby-config.js` file.
2. Add a `favicon.png` file in your `src` folder.

```javascript
// in gatsby-config.js
plugins: [
  {
    resolve: `gatsby-plugin-favicon`,
    options: {
      android: true,
      appleIcon: true,
      appleStartup: true,
      coast: false,
      favicons: true,
      firefox: true,
      twitter: false,
      yandex: false,
      windows: false
    }
  }
]
```
