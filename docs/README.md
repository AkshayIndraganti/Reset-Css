## Reset CSS

A CSS reset establishes a consistent foundation for styling web pages by neutralizing default browser styles. This ensures a uniform baseline, streamlines cross-browser compatibility, and mitigates inconsistencies among devices. By resetting margins, padding, borders, font sizes, and other attributes, developers can build upon a reliable starting point, creating cohesive and professional designs with ease.

```css
/* CSS Reset
 * Custom CSS Reset - Developed for optimal cross-browser consistency and minimal default styling 
*/


/* Define custom variables in :root for global access */
:root {
    /* Fonts */
    --font-family: -apple-system,
        BlinkMacSystemFont,
        "Segoe UI",
        Roboto,
        Oxygen-Sans,
        Ubuntu,
        Cantarell,
        "Helvetica Neue",
        sans-serif,
        "Noto Sans",
        Helvetica,
        Arial,
        "Apple Color Emoji",
        "Segoe UI Emoji";

    --font-size: 62.5%
}

/* Box sizing and inheritance */
html {
    font-size: var(--font-size);
    line-height: 1.5;
    scroll-behavior: smooth;
    box-sizing: border-box;
}

*,
*::before,
*::after {
    box-sizing: inherit;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    font: inherit;
    vertical-align: baseline;
}

/* Remove default list styles */
ul,
ol {
    list-style: none;
}

/* Remove default hyperlink styles */
a {
    text-decoration: none;
    color: inherit;
}

/* Remove default table border and spacing */
table {
    border-collapse: collapse;
    border-spacing: 0;
}

/* Remove default form field styles */
button,
input,
optgroup,
select,
textarea {
    margin: 0;
    padding: 0;
    border: 0;
    font: inherit;
    vertical-align: baseline;
}

/* Correct button and select style in Webkit */
button,
input {
    overflow: visible;
}

/* Remove inner padding and border in Firefox */
button::-moz-focus-inner,
input::-moz-focus-inner {
    border: 0;
    padding: 0;
}

/* Remove outline on focused elements */
button:focus,
input:focus,
textarea:focus {
    outline: 0;
}

/* Correct color inheritance */
svg:not(:root) {
    color: inherit;
}

/* Remove default styling for hr */
hr {
    box-sizing: content-box;
    height: 0;
    overflow: visible;
}

/* Reset font styles */
body {
    font-family: var(--font-family);
    font-size: 1.6rem;
    line-height: 1.5;
    font-weight: normal;
}

/* Reset form field appearance */
button,
input,
select,
textarea {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
}

/* Remove input placeholder color */
input::placeholder {
    color: inherit;
    opacity: 1;
}

/* Remove input type number arrow controls */
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
    -webkit-appearance: none;
    appearance: none;
    margin: 0;
}

/* Remove text selection color */
::-moz-selection {
    background-color: transparent;
    color: inherit;
}

::selection {
    background-color: transparent;
    color: inherit;
}

/* Remove default button border in IE */
button {
    border-style: none;
}

/* Remove default focus outline in IE */
a:focus {
    outline: none;
}

/* Remove default image border */
img {
    border-style: none;
}

/* Remove default vertical alignment on inline elements */
img,
span {
    vertical-align: baseline;
}
```
