# Lumache documentation

This site is built with [Docusaurus](https://docusaurus.io/) and serves as the
example documentation site for the
[Read the Docs Docusaurus tutorial](https://docs.readthedocs.io/en/stable/tutorial/docusaurus.html).

## Local development

```bash
npm install
npm start
```

This starts a local development server and opens a browser window.
Most changes are reflected live without having to restart the server.

## Build

```bash
npm run build
```

This generates static HTML into the `build/` directory.
Read the Docs runs the same command in CI, then copies the contents
of `build/` into its publish directory (see `../.readthedocs.yaml`).