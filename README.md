# Website

This website is built using [Docusaurus](https://docusaurus.io/), a modern
 static website generator. It is mostly used as my playground for docusaurus.

## Installation

Ensure you have [Node.js](https://nodejs.org/en/download/) installed. This
 project uses Node.js version 22 or higher. You can check your version by
 running:

``` bash
node -v
v22.0.0
```

Install the dependencies using npm:

``` bash
npm ci
```

### Local Development

``` bash
npm run build
```

Then, start the local development server:

``` bash
npm run start
```

This command starts a local development server and opens up a browser window.
 Most changes are reflected live without having to restart the server.

## Deployment

This project uses [GitHub Actions](https://docusaurus.io/docs/deployment#deploying-to-github-pages)
 for continuous deployment. When you push changes to the `main` branch, the
 website will be automatically built and deployed to GitHub Pages.