# Lab 4B - Web Development

## Overview
This project demonstrates the use of jQuery for DOM manipulation in a web development context. It involves working with basic HTML elements and replacing plain JavaScript DOM operations with their jQuery equivalents.

## Project Details

### Requirements
The objective is to rewrite a web page's JavaScript DOM manipulation statements using jQuery.

### Features Implemented
1. **Modify the text content of an element**: Using jQuery to change the content of an element with the `id="myElement"`.
2. **Add a CSS class to an element**: Using jQuery to add a CSS class to the `div` element with the `id="myDIV"`.
3. **Attach a click event handler to a button**: Using jQuery to display an alert when a button is clicked.

### HTML Structure
- **`#myElement`**: A `div` element that originally contains the text "Original Text" and gets updated with "Modified Text".
- **`#myDIV`**: A `div` element that gets a new background color by adding the `myStyle` class.
- **`#myButton`**: A button that triggers an alert on click.

## Steps to Run

1. Download or clone this repository.
2. Open the `index.html` file in your preferred web browser.
3. Open the browser's Developer Tools (Press `F12` or `Ctrl+Shift+I`).
4. Go to the **Console** tab to see the changes made by jQuery operations.

## Code Snippets

### jQuery Equivalent for the JavaScript DOM Operations

- **a** - Modify text content of `#myElement`:
  ```javascript
  $("#myElement").text("Modified Text");
