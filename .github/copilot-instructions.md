# Copilot Instructions for LABO 4 Web Project

## Project Overview
This is a static web project for a web design laboratory. The main structure includes HTML files, CSS stylesheets, and image assets. There is no build system, backend, or package management—just direct editing of files.

## Directory Structure
- `Index.html`: Main entry point for the site.
- `CSS/style.css`: Main stylesheet for the homepage and general styles.
- `GridStuff/`: Contains grid-related HTML pages and their own CSS (`stylesGrid.css`).
- `Images/` and `GridStuff/image pour labo 4/`: Image assets for use in the site.

## Key Patterns & Conventions
- **Images:** Use relative paths for images. Example: `<img src="Images/top.jpg" alt="...">` for the main banner.
- **Full-width Banner:** To create a top banner image that spans the full width, use CSS:
  ```css
  .banner {
    width: 100%;
    display: block;
  }
  ```
  And in HTML:
  ```html
  <img src="Images/top.jpg" class="banner" alt="Banner">
  ```
- **Grid Pages:** Grid-related pages (`avatarGrid.html`, `Favoris.html`, `grid.html`) use their own CSS in `GridStuff/css/stylesGrid.css`.
- **No JavaScript:** The project is currently pure HTML/CSS—no scripts or dynamic logic.

## Editing Workflow
- Edit HTML and CSS files directly. No compilation or build steps.
- Use the provided images for banners, avatars, and other visual elements.
- For new pages, follow the structure of existing HTML files and link to the appropriate CSS.

## Custom Conventions
- Images for the grid are stored in `GridStuff/image pour labo 4/`.
- Main site images (e.g., banners) are in `Images/`.
- CSS for the homepage is in `CSS/style.css`; grid pages use their own stylesheet.

## Example: Adding a Full-Width Top Image
1. Place your image in `Images/` (e.g., `top.jpg`).
2. In `Index.html`, add:
   ```html
   <img src="Images/top.jpg" class="banner" alt="Banner">
   ```
3. In `CSS/style.css`, add:
   ```css
   .banner {
     width: 100%;
     display: block;
   }
   ```

## References
- `Index.html` for homepage structure
- `CSS/style.css` for main styles
- `GridStuff/` for grid page examples

---
If any conventions or workflows are unclear, please provide feedback so this guide can be improved.