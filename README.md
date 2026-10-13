# Food, LLC — redesigned Module 3 solution

This is a redesigned, more polished take on the **graded** Module 3 Bootstrap assignment. It preserves the required structure and behavior rather than switching to the separately described optional three-grid-section exercise.

## Requirements preserved

- Exactly **one outer content `<section>`**, with class `col-xs-12`, inside a Bootstrap `.container-fluid > .row`.
- The single section is tall enough to scroll and has a different background from the overall page.
- The navbar says **Food, LLC**, is aligned left, and **scrolls offscreen** with the rest of the page.
- Only on mobile (`xs`): the three-bar Bootstrap toggle opens a **full-width**, differently colored menu with **Chicken, Beef, Sushi**. The links jump to headings within the one section.
- On tablet (`sm`) and desktop (`md`), the navbar shows only Food, LLC.
- The page heading **Our Menu** uses Bootstrap's `.text-center`.
- Uses local **Bootstrap 3.4.1** and jQuery, plus custom CSS in `css/styles.css` only (no inline styles). It runs offline.

**Design note:** There are two smaller *article cards* for Beef and Sushi **inside the one required section**. They are not additional Bootstrap grid sections. This provides working jump targets while preserving the graded assignment's one-section structure.

## Local preview

Open `index.html` in a browser, and resize to under 768px to view the mobile dropdown.

## Publish to GitHub Pages

Upload the **contents** of this folder (`index.html`, `css/`, `js/`) to the root of the GitHub Pages repository, or place them inside any subfolder of your repository. Keep the relative folder paths intact. The root URL or subfolder URL will display the page, respectively.

If you already have an earlier Food, LLC site published, replace its `index.html` and `css/styles.css` with the new versions while preserving the `css/bootstrap.min.css` and `js/` files.
