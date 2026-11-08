# shard.team

The SHARD company website: a multilingual (EN/RU/KZ) single-page site about our services, tech stack and contacts.

**Live:** <https://shard.team>

## Stack

- [Alpine.js](https://alpinejs.dev) for reactivity, no build step
- Vanilla CSS (custom properties, no framework)
- JSON i18n dictionaries (`i18n/*.json`), client-side language switch
- Deployed to GitHub Pages via `.github/workflows/static.yml`

## Develop

Open `index.html` in a browser or serve the folder statically:

    python3 -m http.server 8000

Translation strings live in `i18n/`. Add a language by adding a JSON file and registering it in `js/i18n.js`.

## License

MIT
