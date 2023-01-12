# Nuxt 3 content module - SSG issue reproduction

Minimal project that showcases the issue of rendering md pages from the content directory when building the app as SSG using the generate command.
When running the app locally everything works as expected, but after generating and either running a local server or deploying it anywhere, it doesn't work - it fails with an error that says it can't find the resource it's trying to fetch.

## Setup

Make sure to install the dependencies:

```bash
# yarn
yarn install
```

## Development Server

Start the development server on http://localhost:3000

```bash
yarn dev
```

## Production

Locally preview production build:

```bash
npm run preview
```
