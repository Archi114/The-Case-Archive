# The Detective Archive

A small static website exploring a mystery-themed archive and case file experience. The repository includes HTML pages, visual assets, and a C practice file.

## Project contents

- `story.html` — story/case-file page for **Case File No. 001: The Mystery of the Locked Study**.
- `project.html` — archive landing/content page.
- `prototrpe.html` — prototype navigation layout (filename retained as originally supplied).
- `practice.c` — simple C `hello world` program.
- Image files — source visuals used by the HTML pages.

## Run locally

No build step is required. From this folder, start a local web server:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000> and navigate to the HTML pages. (There is no `index.html` in this project yet.)

Some pages load Bootstrap and Google Fonts from CDNs, so those parts require an internet connection.

## Development notes

- Keep image filenames and relative paths in sync when renaming or moving assets.
- Open the HTML files in a browser or use a local server for testing.
- `practice.c` can be compiled with `cc practice.c -o practice` and run as `./practice`.

## License
This project is licensed under the MIT License. See [`LICENSE`](LICENSE).

## Contributions
Issues and pull requests are welcome. See [`CONTRIBUTING.md`](CONTRIBUTING.md) for guidelines.

## Credits
Visual assets and code in this repository are maintained by the project author. Third-party libraries are loaded from their respective CDNs and remain under their own licenses.
