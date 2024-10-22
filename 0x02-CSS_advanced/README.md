#0x02-CSS_advanced

---

**Requirements:**

- You can use any of the following editors: vi, vim, emacs, VSCode, or Atom.
- The files will be tested using Chrome (version 78.x).
- Ensure that all files end with a newline.
- Each file must begin with a comment explaining the task.
- A `README.md` file is required in the root directory of the project.
- Your code must comply with W3C standards and pass validation through the W3C-Validator.

Here’s a rewritten version of the text with a different structure:

---

### Tasks Overview

#### 0. Get the Images!
**File: images**  
The project description gives an idea of the final look, but we'll need to download images. Visit Unsplash and download 10 high-resolution images that closely match the project’s vision. These images will also be used in a future Responsive Design project. Don’t forget to include the 3 linked images from the project description (2 logos and the favicon). Make sure the images accurately represent their categories; for example, work-related images should reflect work-related themes.

#### 1. Smooth Scroll Transitions
**File: 1-style.css**  
Ensure fluid scrolling behavior on the HTML element itself when triggered.

#### 2. Define Color Values
**File: 2-style.css**  
Following the styles in 1-style.css, add the following:
- Set the body and anchor elements’ color to `#161616`.
- Hide elements with the `.visually-hidden` class.
- Set the color of `.card-category` and `.section-tagline` to `#D73953`.

#### 3. Simplify with Variables
**File: 3-style.css**  
In the root element, define custom properties:
- `color-primary: #D73953`
- `color-black: #090909`
- `color-white: #ffffff`
- `color-light-grey: #f3f3f3`
- `color-dark-grey: #353535`
- `text-color: color-black`
  
Update the colors for `.section-tagline` and `.card-category` using `color-primary`, and the body and anchor colors using `text-color`. No W3C validation needed.

#### 4. Font-Family Variables
**File: 4-style.css**  
In the root element, define custom properties for fonts:
- `font-family-base: 'Helvetica Neue', Helvetica, Arial, sans-serif`
- `font-family-title: 'Helvetica Neue', Helvetica, Arial, sans-serif`

Set the body font to `font-family-base`, and the section headings’ font to `font-family-title` before the links declaration. No need for W3C validation.

#### 5. Font Size Variables
**File: 5-style.css**  
Create custom properties in the root selector for font sizes:
- `font-size-small: 1.2rem`
- `font-size-medium: 1.6rem`
- `font-size-large: 1.8rem`
- `font-size-x-large: 2.3rem`
- `font-size-xx-large: 4.8rem`

Set HTML font sizes to 62.5%, and body fonts to `font-size-medium`. No W3C validation needed.

#### 6. Font-Weight Variables
**File: 6-style.css**  
Create custom properties in the root element:
- `font-weight-regular: 400`
- `font-weight-bold: 700`

Apply `font-weight-regular` for body text and `font-weight-bold` for headings. No W3C validation needed.

#### 7. Adding Google Fonts
**File: 7-style.css**  
Add the following fonts to the custom properties:
- `font-family-base: 'Open Sans', Helvetica, Arial, sans-serif`
- `font-family-title: 'Raleway', Helvetica, Arial, sans-serif`

No W3C validation needed.

#### 8. Line Height Variables
**File: 8-style.css**  
Create custom properties for line heights:
- `line-height-small: 1.2`
- `line-height-base: 1.5`
- `line-height-big: 1.8`

Set the minimum line height for the body to `line-height-base`. No W3C validation needed.

#### 9. Remove Link Decoration
**File: 9-style.css**  
Remove all text decorations from anchor elements. No W3C validation needed.

#### 10. Center Section Titles
**File: 10-style.css**  
Create a custom property `section-header-align` and set it to `center`. Use this to horizontally align the `.section-header` class. No W3C validation needed.

#### 11. Add Styles to Section Taglines
**File: 11-style.css**  
Create the property `section-tagline-transform` with a value of `uppercase`. Style the `.section-tagline` with this transformation, `font-family-title`, and `font-weight-bold`. No W3C validation needed.

#### 12. Style the Section Titles
**File: 12-style.css**  
Define custom properties for `.section-title`:
- `section-title-margin: 0`
- `section-title-color: color-black`

Use these for setting margins, color, font size, and weight. No W3C validation needed.

#### 13. Styling Pseudo Classes
**File: 13-style.css**  
Ensure anchor elements target only hyperlinks. Add styles for visited, hover, and active states. No W3C validation needed.

#### 14. Normalize the Stylesheet
**File: 14-style.css**  
Use Necolas’ normalize.css to reset the stylesheet for cross-browser consistency. No W3C validation needed.

#### 15. Add Universal Box Sizing
**File: 15-style.css**  
Before styling the HTML, add a universal box-sizing rule. No W3C validation needed.

#### 16. Style the Container
**File: 16-style.css**  
Set the container width to 960px with evenly distributed margins. No W3C validation needed.

#### 17. Add Section Padding
**File: 17-style.css**  
Create custom padding properties for sections and apply them across various classes (header, body, footer). No W3C validation needed.

#### 18. Customize Navbar
**File: 18-style.css**  
Style the `.navbar-menu` to float right, and apply margin, padding, and text alignment to other elements within the `nav` class. No W3C validation needed.

#### 19. Grid Layout and Custom Properties
**File: 19-style.css**  
Create a custom property for `section-tagline-margin`, and apply grid layout styles to `.row` and `.col-*` classes. No W3C validation needed.

#### 20. Clear Grid Context
**File: 20-style.css**  
After each `.row`, create a new row with no content and no floating elements. No W3C validation needed.

#### 21. Simplify Column Selector
**File: 21-style.css**  
Select all `col-*` classes, float them left, and set padding. Remove redundant references from individual `col-1-3` and `col-1-2` classes. No W3C validation needed.

#### 22. Add Dark Theme
**File: 22-style.css**  
For elements with `data-section-theme="dark"`, set text color to `color-white`, background to `color-black`, and section title color to `color-white`. No W3C validation needed.

#### 23. Fix Dark Theme Issues
**File: 23-style.css**  
Style `.footer-address` and `.social-link` for better visibility in dark mode. No W3C validation needed.
