# Code Refactoring

## Description:

Refactor HTML and CSS source code for Horisen. The goal is to improve accessibility and sustainability of the source codes, by apply semantic structure to them.
The website should also be optimized for search engines. After the refactor, all layouts and functionalities of the original website will remain the same.

## Issues in the original code:

 - The title of index.html is generic.
 - Not use semantic HTML elements. 
 - Incorrectly use of class attribute.
 -  Redundant CSS selectors and properties in CSS file.
 - CSS file structure isn't follow semantic structure.

## modifications

 - [x] Change title from "website" to "horiseon" for search engine optimization. 
 - [x] Use sematic elements such as `<header>`,`<footer>`,`<nav>  `etc. to replace most `<div>`elements.
 - [x] Change all unique class attributes to id attributes.
 - [x] Creat new class attributes in html.
 - [x] Add `alt` attributes in all `<img>` elements
 - [x] Consolidat and reorganize CSS selector and properties to follow semantic structure.
 
## Sample Codes

HTML code after refacyoring. 

![HTML Code after refactoring.](./assets/screenshot/html-after.png )

CSS code after refactoring.

![CSS code after refactoring.](./assets/screenshot/css-after.png)

## Links

[Horiseon website after code refactoring ](https://realzzkevin.github.io/Code-Refactor-ZZ/)

[Horiseon project Git Hub repository](https://github.com/realzzkevin/Code-Refactor-ZZ/settings)


![Horiseon page after refactoring](./assets/screenshot/Code-Refactor-ZZ.png)
