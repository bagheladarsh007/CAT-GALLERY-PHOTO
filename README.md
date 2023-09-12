# CAT-GALLERY-PHOTO
This is a simple photo gallery web page created using HTML and CSS. <br>
In this README, we'll go over the HTML code provided and explain the various tags used.<br>
We'll also discuss the CSS properties used for styling

## HTML Tags Used
This HTML document utilizes the following HTML tags:

`<html>`
The root element of the HTML document, encompassing all other elements.

`<head>`
Contains meta-information about the document, such as character encoding, viewport settings, and the document title.

`<meta>`
Provides metadata about the HTML document, like the character encoding and viewport settings for responsive design.

`<title>`
Sets the title of the HTML document, which appears in the browser's title bar or tab.

`<link>`
Links an external stylesheet (styles.css in this case) to style the HTML content.

`<body>`
Encloses the visible content of the HTML document, including headings, paragraphs, and div containers.

`<h1>`
A heading element with the text "css flexbox photo gallery," which serves as the main title.

`<div>`
A container element used for grouping and styling other HTML elements. In this case, `<div class="gallery">` A container div for the photo gallery.

CSS Styling
The CSS code provided in style.css is responsible for styling the photo gallery. Here are the CSS properties used in the stylesheet:


## Screenshort of Webpage
### Header Section
<img width="956" alt="cath" src="https://github.com/bagheladarsh007/CAT-GALLERY-PHOTO/assets/142333682/822f3eb7-5aff-4cd2-9a97-a742d15ab174">

### `<div class="gallery">` section

<img width="577" alt="cat img" src="https://github.com/bagheladarsh007/CAT-GALLERY-PHOTO/assets/142333682/54b2be90-92f1-423e-a5dd-e920f1b2cee9">

## CSS Styling

The CSS code provided in style.css is responsible for styling the photo gallery. Here are the CSS properties used in the stylesheet:

### Explanation of CSS Properties
`* { box-sizing: border-box; }:` Applies the box-sizing property to all elements, ensuring that padding and borders are included in the element's total width and height.

`body: `Styles the entire page body, setting margin, font family, and background color.

`.header: `Styles the header section with text alignment, text transformation, padding, background color, color, and a border at the bottom.

`.gallery:` Styles the photo gallery container as a flexbox. It sets the flex direction to row, allows wrapping of items, justifies content to the center, aligns items to the center, defines a gap between items, sets a maximum width, and provides margin and padding for spacing.

`.gallery img:` Styles the gallery images, ensuring they take up the full width, have a maximum width of 350px, a fixed height of 300px, and use object-fit to cover the entire image area. It also rounds the corners with a border radius.

`.gallery::after:` Pseudo-element used to create an empty space after the last row of images in the gallery.

## hosted link

You can access the live preview of the webpage [here] https://bagheladarsh007.github.io/CAT-GALLERY-PHOTO/
