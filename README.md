# rbishop.github.io

This project is a simple static GitHub Pages site. There is no build step or Docker setup required.

## Run locally

From the project root, start a local web server:

```bash
cd /path/to/rbishop3757.github.io
python3 -m http.server 8000
```

Then open this in your browser:

```text
http://localhost:8000
```

To stop the server, press `Ctrl + C` in the terminal.

If `python3` is not available on your machine, try:

```bash
python -m http.server 8000
```

This serves the files directly as a static website, which matches how GitHub Pages serves the site.
