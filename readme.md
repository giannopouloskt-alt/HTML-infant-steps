# HTML Infant Steps

A small static web page project for practicing basic HTML and CSS layout. The current page presents a Leafnet LTD themed landing/about page with navigation, a hero section, an image block, company introduction text, and a dark timeline section.

## Project Structure

```text
.
├── index.html   # Main HTML page
├── main.css     # Styles for layout, typography, colors, and image display
├── agent.md     # Development note for AI/code assistant guidance
├── .gitignore   # Web development ignore rules
└── readme.md    # Project documentation
```

## How to View the Page

This project does not require a build step or a development server. Open `index.html` directly in a browser.

You can also use a local static server if you prefer:

```bash
npx serve .
```

Then open the local URL shown in the terminal.

## Main Files

### `index.html`

Defines the page content and structure:

- A top navigation area with links such as Home, About, Services, and Portfolios.
- A hero section introducing the page with the heading “Transforming Education Through Innovative Online Learning”.
- An image container using the `back` class.
- A “Who We Are” content section about Leafnet LTD.
- A dark “Our Journey” section with timeline-style company history text.

### `main.css`

Controls the visual presentation:

- Global typography is set on the `body`.
- `.upper` styles the navigation row.
- `.start`, `.hold`, `.bot`, and `.top` style the hero area.
- `.back` displays the project image as a CSS background image.
- `.right` styles the company introduction text beside the image.
- `.black`, `.journey`, and `.yap` style the dark timeline section.

## Image Handling

The image is currently applied in CSS through the `.back` class:

```css
div.back {
  background-image: url("https://www.leafnet.com.cy/wp-content/uploads/2025/09/pexels-photo-8472864.jpeg");
}
```

This keeps the HTML simple because the image is decorative/presentational. If the image becomes meaningful content that needs alt text for accessibility, it should be changed to an `<img>` element inside `index.html`.

## Notes for Development

- Keep HTML structure in `index.html`.
- Keep styling in `main.css`.
- Use clear class names when adding new sections.
- Add responsive styles if the page needs to work well on smaller screens.
- Avoid committing generated folders such as `node_modules`, `dist`, or environment files.
