# CSS Tutorial

## What is CSS?

CSS (Cascading Style Sheets) is a language used for describing the presentation of a document written in HTML or XML (including XML dialects such as SVG, MathML, etc.). It controls how HTML elements are displayed on a webpage.

## Getting Started

To apply CSS to an HTML document, you have three main options:

1. **Inline CSS**: Apply styles directly to HTML elements using the `style` attribute.

   ```html
   <p style="color: red; font-size: 16px;">Hello, CSS!</p>

```
html <!DOCTYPE html>
<html>
<head>
    <style>
        p {
            color: red;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <p>Hello, CSS!</p>
</body>
</html>

##Internal CSS: Define styles within a <style> tag in the <head> section of your HTML document.

```
html <!DOCTYPE html>
<html>
<head>
    <style>
        p {
            color: red;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <p>Hello, CSS!</p>
</body>
</html>
    ### External CSS: Create a separate CSS file and link it to your HTML document using the <link> tag.

```html
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <p>Hello, CSS!</p>
</body>
</html>

       ##In `styles.css`:
```css
p {
    color: red;
    font-size: 16px;
}
p {
    color: blue;
}
###CSS Selectors
##CSS selectors are used to target HTML elements for styling. Here are a few commonly used selectors:
```css
p {
    color: blue;
}

     ##Class Selector: Targets elements with a specific class attribute.
```html
   <p class="intro">This is a paragraph.</p>

```css
.intro {
    font-size: 18px;
}
## ID Selector: Targets an element with a specific ID attribute.
```html <p id="main-paragraph">This is the main paragraph.</p>
 ```css #main-paragraph {
    font-weight: bold;
}

#CSS Properties

##CSS properties define how HTML elements are displayed. Here are a few common properties:

color: Sets the text color.
font-size: Sets the size of the font.
font-family: Specifies the font family.
background-color: Sets the background color.
margin, padding: Controls the spacing around an element.
border: Sets the border properties.
width, height: Defines the dimensions of an element.
#Example
##3Let's combine what we've learned into a simple example:


```html <!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <h1 class="heading">Welcome to CSS Tutorial</h1>
    <p class="intro">This tutorial will teach you the basics of CSS.</p>
</body>
</html>

```css .heading {
    color: #333;
    font-size: 24px;
    font-family: Arial, sans-serif;
    text-align: center;
}

.intro {
    color: #666;
    font-size: 16px;
    line-height: 1.5;
}
