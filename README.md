# Congressional App Challenge Showcase

A static map and gallery of student projects organized by congressional district. This repository is a fork; retain the upstream contribution context when presenting it.

## Get the source

```sh
git clone --filter=blob:none https://github.com/TanishC4444/Congressional-Showcase.git
cd Congressional-Showcase
```

## Preview

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000`. `projects.json` supplies gallery records; participant pages live in `sites/` and shared images in `assets/`.

## Contribution and status

The source includes submission scripts and a participant-page template. Describe a specific contribution or participant entry in a portfolio; do not claim ownership of the entire upstream showcase.

The static entry point and data structure were inspected. Map loading, submission automation, and all participant links were not exhaustively tested. There is no root license file in this checkout; verify upstream terms before redistributing inherited code.

[Detailed project notes](docs/project-guide.md)
