# Distributed Downloader Landing Page

This repository contains a static landing page (`index.html` + `main.css`).

## Development environment

### Prerequisites
- Python 3 (used to run a local static server)

### Run locally
From the repository root:

`python3 -m http.server 4173`

Then open:

`http://127.0.0.1:4173`

## Quick environment verification
Use these checks:

1. Start the server command above.
2. Run:

`curl -I http://127.0.0.1:4173`

Expected result: `HTTP/1.0 200 OK`.

3. Open the page in a browser and confirm:
- Hero heading ("Download faster with cooperative peers.")
- "How it works" cards
- "What is next" and footer sections
