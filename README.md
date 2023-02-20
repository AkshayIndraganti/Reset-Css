## Reset CSS

A CSS reset is a set of styles that are applied to all elements on a web page in order to provide a consistent baseline for styles across different browsers. The purpose of a reset is to "reset" or "normalize" the default styles that browsers apply to HTML elements, which can vary between browsers and may not provide a consistent starting point for building a website.

A CSS reset typically includes a set of rules that remove or reset all the default styles applied to HTML elements by the browser. This includes removing margins, padding, and borders from elements, setting the font size and line height to a consistent value, and setting the background and text colors to transparent. The reset may also include setting a default font family and font size for the entire page.

```css
/* Box sizing border-box for all elements */
*,
*::before,
*::after {
  box-sizing: border-box;
}

/* Remove default margin and padding on all elements */
html,
body,
div,
span,
h1,
h2,
h3,
h4,
h5,
h6,
p,
a,
img,
ul,
ol,
li,
table,
thead,
tbody,
tr,
th,
td,
form,
input,
textarea,
button {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
}

/* This will set 1rem to be equal to 10px */
html {
  font-size: 62.5%;
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
  font-family: sans-serif;
  font-size: 16px;
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
