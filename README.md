# Congressional App Challenge Showcase

A community showcase for apps built by high school students participating in the Congressional App Challenge, with individual project pages connected through an interactive landing page.

## Overview

Participants can submit projects through a GitHub Issue or build a customized showcase page in their fork. The repository provides a template, project metadata, shared navigation, and contribution guidance.

## Features

- Individual participant showcase pages
- Interactive project landing page and map
- GitHub Issue submission workflow
- Reusable page template
- Project metadata in `projects.json`
- Shared CSS and navigation components

## Add a Project

### Option A: Submit an Issue

1. Open the repository's Issues tab.
2. Select the **Add My Project** issue template.
3. Provide your name, app information, demo video, and location.
4. Submit the issue for maintainer review.

### Option B: Create a Page

1. Fork the repository.
2. Create `sites/XX-00/index.html`, using your congressional district.
3. Copy the provided template and replace its `TODO` values.
4. Add the project to `projects.json`.
5. Open a pull request.

Only modify your own `sites/XX-00/` directory and the project metadata required for your submission.

## Project Structure

```text
Congressional-Showcase/
├── sites/              # Participant pages
├── template/           # Page template and guidance
├── projects.json       # Project metadata
└── index.html          # Showcase landing page
```

## Guidelines

- Keep submissions under 5 MB.
- Use YouTube/Vimeo for videos rather than committing large media files.
- Do not modify other participants' pages.
- Keep the shared navigation and stylesheet references intact.

## Support

Use the repository's help issue template for questions or problems with a submission.

## License

MIT
