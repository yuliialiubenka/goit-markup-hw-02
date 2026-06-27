# goit-markup-hw-02

WebStudio landing page markup and styles for Homework #2. This project contains a complete static one-page layout with semantic HTML, separated CSS files, images from the mockup, and the required external style resources.

**Project overview**

- **Purpose:** practice building a clean, semantic, and visually accurate page based on the provided design.
- **Scope:** a static WebStudio page with header, hero, features, team, portfolio, and footer sections.
- **Assets:** images, favicon, and all text content are taken from the mockup.

**HTML and CSS structure**

- **index.html** links only to `css/main.css`.
- **main.css** contains only imports of the other style files.
- **CSS files** are split by page parts: `common.css`, `header.css`, `hero.css`, `features.css`, `team.css`, `portfolio.css`, and `footer.css`.
- **Import paths** in `main.css` start with `./`.
- **Common styles** and global rules are placed in `common.css`.

**Project requirements covered**

- The project has an `images` folder for graphics and a `css` folder for styles.
- File names use only English letters, numbers, and hyphens where needed.
- The code is formatted with Prettier.
- `modern-normalize` is connected in its minified version.
- The layout follows the Code Guide and uses class selectors for styling.
- Interactive elements have hover and focus states that match the design guide.

**Page sections**

- **Header:** logo, navigation links, and contact information.
- **Hero:** main headline and call-to-action button.
- **Features:** a hidden title in the layout and a list of four feature items.
- **Team:** team member cards with photos, names, and roles.
- **Portfolio:** a separate section with the `portfolio` id and a grid of project cards.
- **Footer:** logo and short business description.

**Notes**

- The dominant font is `Roboto`, with `Raleway` used for the logo.
- Images in the portfolio and team sections include size attributes in the HTML.
- All content is static and intended for practice with semantic markup and CSS organization.
