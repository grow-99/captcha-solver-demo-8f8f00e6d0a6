# captcha-solver-demo

A minimal static page for task **captcha-solver-demo**.

## How to run locally

1. Serve files (from repo root):
   - Using Node: `npx http-server . -p 8080`
   - Or Python: `python -m http.server 8080`
2. Open: `http://localhost:8080/?url=/assets/sample.png`

## What it does

- Reads `?url=` query parameter and displays the image in `#captcha-img`.
- Writes a solved token into `#captcha-solution` after image load (simple deterministic logic).

## License

MIT - see LICENSE file.
