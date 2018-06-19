## CSS

### Objectives
* Understand the anatomy of a declaration block
* Learn how to test CSS with Chrome Dev Tools
* Create custom layouts using Semantic UI and Grid
* Go over custom CSS and flex box

### Why CSS is important
* ```<a href="http://www.csszengarden.com/" >Zen Garden</a>```

### Key Principles of CSS
* Creating a declaration block:
```css
p {
  font-weight: bolder;
}```
  * p: selector (selectors are used to select the HTML elements that you want to style);
  * font-weight: attribute or property name;
  * bolder: value
* The Box Model
  * Padding: distance from the inside of the `div` to the border
  * Border: border around `div`
  * Margin: distance from exterior content to the `div`
* Cascading Stylesheet
  * Three ways to write css in relation to an HTML document:
    * In-line styling: ```<p style="color: red">in line!</p>```
    * Internal stylesheet: ```<head> <style> p {color: red;}</style> </head>```
    * External stylesheet: ```<link rel="stylesheet" type="text/css" href="./style.css"/>```
  * Style is inherited if not explicitly defined
  * Will always look to nearest definition, if style is declared multiple times.

### Best Practices
* Use `class` over `id` when adding selectors to HTML tags

### Chrome Dev Tools
* Can test/edit CSS in real time in the Chrome browser
* Pseudo-classes: used to define special states of an element, where applicable
  * `a:hover` (targets a link when hovered over)
  * `a:active` (targets a link when active, used in nav bars )
  * `div:first-child` (targets the first nested child inside of a `div` )
  * `input:optional` (makes an `input` within a `form` optional)
  * `p::after` (inserts content after every `p` tag)

### Bringing in external resources
* Semantic UI, Material UI, Bootstrap
* Grid
* Google Fonts

### Flexbox and writing custom CSS
* Flexbox: direction agnostic layout that helps to organize `divs` on a page.
* ```div {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}```
