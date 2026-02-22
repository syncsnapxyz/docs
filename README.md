# Syncsnap Docs

Mintlify documentation for Syncsnap. Content is written in MDX and configured in `docs.json`.

## Local development

**Requirements:** Node.js v20.17.0+

1. Install the Mintlify CLI:
   ```bash
   npm i -g mint
   ```

2. From this directory, run:
   ```bash
   mint dev
   ```

3. Open [http://localhost:3000](http://localhost:3000) to preview.

## Project structure

- **docs.json** — Site config (name, theme, colors, navigation)
- **\*.mdx** — Documentation pages (e.g. `index.mdx`, `quickstart.mdx`)
- **favicon.svg** — Favicon

Add new pages as `.mdx` files and register them under `navigation` in `docs.json`.

## Deploying

Connect this repo at [mintlify.com/start](https://mintlify.com/start) and install the Mintlify GitHub app. Pushes to the default branch will deploy automatically.

## Resources

- [Mintlify docs](https://mintlify.com/docs)
- [Mintlify components](https://mintlify.com/docs/components)
