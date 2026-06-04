# Static Web Application

## Overview
This project is a simple static landing page for **Leafnet LTD**, focused on online learning and eLearning services.

The page is built with plain HTML and CSS, with no framework or build step required. It includes:

- a top navigation-style row
- a hero section with the main message
- an about section describing the company
- a visual section using a large background image
- a dark timeline/story section

## Project Structure

- `index.html` - the page markup and content
- `main.css` - all styling for layout, typography, and spacing
- `VERSIONS.md` - change log and version notes
- `agent.md` - project guidance for future work

## How to Run

Because this is a static site, you can open `index.html` directly in a browser.

If you want a local server, use any simple static server, for example:

```bash
python3 -m http.server
```

Then open the local address shown in the terminal, usually `http://localhost:8000`.

## Design Notes

- The page uses a serif-style font stack for a more editorial look.
- The layout is currently built with fixed widths and absolute positioning in several places.
- The large image in `div.back` is loaded from an external URL in `main.css`.
- The content is written as a polished marketing-style landing page for an education company.

## Current Version

Version tracking starts at `1.0.0` in `VERSIONS.md`.

## Known Improvements

- Replace fixed positioning with a more responsive layout system.
- Consider using CSS Grid or Flexbox for better adaptability across screen sizes.
- Review the external image dependency if offline or local hosting is preferred.

## Version History

See `VERSIONS.md` for the detailed change log.
