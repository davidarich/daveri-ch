# Development

## Build Tailwind CSS

Run during development to watch for CSS changes and propogate used classes to `public/publish.css`.

```sh
npx @tailwindcss/cli -i ./src/source.css -o ./docs/publish.css --watch
```
