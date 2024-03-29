# Class 5 Reading Notes - *Design web pages with CSS*

## What is CSS?

**CSS (Cascading Style Sheets)** is a programming language that allows you to design a website. CSS allows us to control, with extreme precision, how HTML elements appear on a webpage.

A document or text file is structured using a markup language such as [HTML](class4.md). Text files are then presented (usually in a visual format) by using internet browsers which can display information on a screen, project something, or print it out.

> Note: Internet browsers (Google Chrome, Microsoft Edge, Mozilla Firefox, etc.) are also known as **user agents**.

When we see how basic HTML is read in a web browser we can notice that the text does have design elements applied such as headings being larger and links being blue/underlined. This is because our internet browsers have very basic CSS styles built into them that apply what is written in HTML.

### CSS Syntax

CSS is defined by rules which specify what styles should be applied to an element or groups of elements written by your markup language.

> HTML is the markup language that most people are familiar with, however, there are others such as SVG or XML which can be styled by CSS.

Let's look at an example of CSS being used to style the heading on a page to be displayed as large blue text.

`h1 {color: red;
    font-size: 5em;}`

- The above CSS rule opens with a **selector** `<h1>` which selects the HTML element which is being styled.
- Then a set of curly brackets `{}` is used to contain the styling code.
- Inside the brackets are the **declarations** which can be split into a **property** and **value** pair. The declaration begins with the property `color` then a colon `:` to separate the value `red` followed by a semicolon `;` to end the declaration.
- this example includes 2 declarations, one for `color` and one for `font-size`.

### CSS Specifications

Web standard technologies such as HTML, CSS, or JavaScript are defined by large reference documents aka *specifications* (or "specs"). These specs are kept up to date and published by organizations such as W3C, WHATWG, ECMA, or Khronos.

CSS is developed by a group within the W3C known as the CSS Working Group. This group consists of internet browser vendors and companies who have an interest in maintaining CSS. New features for CSS are created as need or demand by the community requires. However, the CSS Working Group remains vigilant to NOT change any CSS data that would "break old websites."

### Browser Support Information

> NOTE: CSS features can only be utilized in making a web page if browsers have implemented the feature.

Code must be written to understand the instructions in our CSS files and output design onto a monitor/screen. Browsers implement features at different times, so there can be gaps where CSS will fully implement on one browser but NOT another.

## How to Add CSS

### Three Ways to Insert CSS

There are three (3) ways of inserting a CSS style sheet into an HTML document:

1. **External CSS**
2. **Internal CSS**
3. **Inline CSS**

### External CSS

An *external style sheet* is a separate file which can be used to add CSS style instructions for an entire website. Each HTML page must include a reference to the external style sheet inside the `<link>` elements inside the `<head>` section. An external style sheet can be written in any text editor and must be saved with an `.css` extension. The industry best practice is to title this file `style.css`

- How to Link to a Style Sheet within your HTML file: `<link rel=“stylesheet” href=“style.css”>`

> **Note:** Do NOT add spaces between property values and the units.

- Incorrect (space added): `margin-left: 20 px;`
- Correct (no space): `margin-left: 20px;`

### Internal CSS

An *internal style sheet* can be used if a single HTML page has a unique style. The internal style is defined using a `<style>` element inside the `<head>` section. 

### Inline CSS

*Inline* CSS styling is used for adding unique design to a single element. In this method, the style attribute is added directly to the element as shown below. 

`<h1> style="color:blue;text-align:center;"This is a heading</h1>`

#### Cascading Order

If more than one CSS style is used for a specific HTML element then the styles will *"cascade"* based on the following order of priority.

1. Inline style (inside an HTML element) = Highest priority
2. External & Internal style sheets (in the `<head>` section)
3. Browser defaults = Lowest priority

## [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
