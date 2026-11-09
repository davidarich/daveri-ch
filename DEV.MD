# Development

## Build Tailwind CSS

Run during development to watch for CSS changes and propogate used classes to `public/publish.css`.

```sh
npx @tailwindcss/cli -i ./src/source.css -o ./docs/publish.css --watch
```

On Windows, a PowerShell script policy bypass may be required to run the script

```powershell
Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope Process
```
