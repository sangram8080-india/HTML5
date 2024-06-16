# HTML Tags Overview

This repository provides a comprehensive guide to HTML5 and older version tags for beginners. Each section includes an explanation of the tags and examples to help you get started.

## Table of Contents

- [Introduction](#introduction)
- [HTML Basics](#html-basics)
  - [HTML Structure](#html-structure)
  - [Doctype Declaration](#doctype-declaration)
- [HTML Tags](#html-tags)
  - [Text Formatting Tags](#text-formatting-tags)
  - [Grouping Content Tags](#grouping-content-tags)
  - [Sectioning Tags](#sectioning-tags)
  - [Form Tags](#form-tags)
  - [Table Tags](#table-tags)
  - [Media Tags](#media-tags)
  - [Meta Information Tags](#meta-information-tags)
- [Deprecated Tags](#deprecated-tags)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Introduction

HTML (HyperText Markup Language) is the standard markup language used to create web pages. This guide covers HTML5 and older HTML tags to help beginners learn and understand the basic building blocks of web development.

## HTML Basics

### HTML Structure

An HTML document has a basic structure that includes a `<!DOCTYPE html>` declaration, `<html>` root element, `<head>` element, and `<body>` element.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Title</title>
</head>
<body>
    <h1>Hello, World!</h1>
    <p>This is a sample HTML document.</p>
</body>
</html>
```

### Doctype Declaration

The `<!DOCTYPE html>` declaration defines the document type and version of HTML. For HTML5, it is simply:

```html
<!DOCTYPE html>
```

Older versions of HTML have more complex doctype declarations:

- HTML 4.01 Strict:
  ```html
  <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
  ```

- HTML 4.01 Transitional:
  ```html
  <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
  ```

- XHTML 1.0 Strict:
  ```html
  <!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
  ```

## HTML Tags

### Text Formatting Tags

- `<h1> to <h6>`: Headings
  ```html
  <h1>This is a heading</h1>
  <h2>This is a smaller heading</h2>
  ```

- `<p>`: Paragraph
  ```html
  <p>This is a paragraph.</p>
  ```

- `<b>`: Bold text (use `<strong>` in HTML5)
  ```html
  <b>This text is bold.</b>
  ```

- `<i>`: Italic text (use `<em>` in HTML5)
  ```html
  <i>This text is italic.</i>
  ```

- `<u>`: Underlined text
  ```html
  <u>This text is underlined.</u>
  ```

- `<a>`: Anchor (link)
  ```html
  <a href="https://example.com">This is a link</a>
  ```

### Grouping Content Tags

- `<div>`: Division or section
  ```html
  <div>
      <p>This is inside a div element.</p>
  </div>
  ```

- `<span>`: Inline container
  ```html
  <p>This is a <span>span</span> inside a paragraph.</p>
  ```

### Sectioning Tags

- `<header>`: Header for a document or section
  ```html
  <header>
      <h1>Welcome to My Website</h1>
  </header>
  ```

- `<footer>`: Footer for a document or section
  ```html
  <footer>
      <p>&copy; 2024 My Website</p>
  </footer>
  ```

- `<nav>`: Navigation links
  ```html
  <nav>
      <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#contact">Contact</a></li>
      </ul>
  </nav>
  ```

- `<article>`: Self-contained content
  ```html
  <article>
      <h2>Article Title</h2>
      <p>This is an article.</p>
  </article>
  ```

- `<section>`: Section of a document
  ```html
  <section>
      <h2>Section Title</h2>
      <p>This is a section.</p>
  </section>
  ```

### Form Tags

- `<form>`: Form element
  ```html
  <form action="/submit-form" method="post">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name">
      <input type="submit" value="Submit">
  </form>
  ```

- `<input>`: Input field
  ```html
  <input type="text" id="name" name="name">
  ```

- `<textarea>`: Multiline text input
  ```html
  <textarea id="message" name="message"></textarea>
  ```

- `<button>`: Clickable button
  ```html
  <button type="button">Click Me!</button>
  ```

### Table Tags

- `<table>`: Table
  ```html
  <table>
      <tr>
          <th>Header 1</th>
          <th>Header 2</th>
      </tr>
      <tr>
          <td>Data 1</td>
          <td>Data 2</td>
      </tr>
  </table>
  ```

- `<tr>`: Table row
  ```html
  <tr>
      <td>Data 1</td>
      <td>Data 2</td>
  </tr>
  ```

- `<th>`: Table header
  ```html
  <th>Header</th>
  ```

- `<td>`: Table cell
  ```html
  <td>Data</td>
  ```

### Media Tags

- `<img>`: Image
  ```html
  <img src="image.jpg" alt="Description of image">
  ```

- `<audio>`: Audio content
  ```html
  <audio controls>
      <source src="audio.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
  </audio>
  ```

- `<video>`: Video content
  ```html
  <video controls>
      <source src="video.mp4" type="video/mp4">
      Your browser does not support the video element.
  </video>
  ```

### Meta Information Tags

- `<meta>`: Metadata
  ```html
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  ```

- `<title>`: Document title
  ```html
  <title>Page Title</title>
  ```

- `<link>`: Link to external resources
  ```html
  <link rel="stylesheet" href="styles.css">
  ```

## Deprecated Tags

These tags were used in older versions of HTML but are deprecated in HTML5:

- `<font>`: Defines font, font size, and color (use CSS instead)
  ```html
  <font color="red">This is red text.</font>
  ```

- `<center>`: Centers text (use CSS instead)
  ```html
  <center>This text is centered.</center>
  ```

- `<big>`: Makes text large (use CSS instead)
  ```html
  <big>This is big text.</big>
  ```

- `<basefont>`: Sets default font (use CSS instead)
  ```html
  <basefont size="4" color="red">
  ```

## Examples

### Basic HTML5 Page

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic HTML5 Page</title>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="home">
        <h2>Home</h2>
        <p>This is the home section.</p>
    </section
