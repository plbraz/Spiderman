# Spider-Man | Multiversos Web Page Documentation

## Overview

This HTML document represents a simple webpage with a navigation menu styled with CSS. The page is themed around Spider-Man and uses Google Fonts and custom stylesheets.

## HTML Structure

### Document Type and Metadata
- **`<!DOCTYPE html>`**: Specifies the document type and version of HTML.
- **`<html lang="pt-BR">`**: Defines the language of the document as Brazilian Portuguese.
- **`<head>`**: Contains metadata and links to external resources.
  - **`<meta charset="UTF-8">`**: Sets the character encoding to UTF-8.
  - **`<meta http-equiv="X-UA-Compatible" content="IE=edge">`**: Ensures compatibility with Internet Explorer.
  - **`<meta name="viewport" content="width=device-width, initial-scale=1.0">`**: Sets the viewport to match the device width for responsive design.
  - **`<link rel="stylesheet" href="assets/css/home-page-styles.css">`**: Links to an external CSS stylesheet.
  - **`<title>Spider-Man | Multiversos</title>`**: Sets the title of the webpage.

### Content
- **`<body>`**: Contains the visible content of the page.
  - **`<nav class="s-menu">`**: Defines a navigation menu.
    - **`<ul>`**: Unordered list containing menu items.
      - **`<li class="s-menu__item">`**: List item with a navigation link.
      - **`<li class="menu__icon">`**: List item containing an icon image.
  - **`<div class="s-container">`**: A container div for additional content (currently empty).

## CSS Styles

### Imports
- Imports the Poppins font from Google Fonts.
- Imports a CSS reset stylesheet.
- Imports a global stylesheet.

### Variables
- Defines a CSS custom property for the primary color.

### Body Styles
- Sets the font family to Poppins and the background color to the primary color.

### Navigation Menu Styles
- Styles the navigation menu with padding, full width, and centered text.
- Styles each menu item to display inline with uppercase text and margin.

### Global Styles
- Resets global styles for all elements, setting padding, margin, list styles, and text properties.

## Notes
- Ensure that the external stylesheets and images are correctly linked and available in the specified paths.
- Customize the `s-container` div as needed for additional content.
