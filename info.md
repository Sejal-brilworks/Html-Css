# HTML    
         hyperText - using hyperlink to move to the next page 
         Markup Language - it use tages to define elenmnts 

# HTML Docs

<!doctype html> //show that this code have version html5 
<html lang="en-US"> //show languages 
  <head>
    <meta charset="utf-8" /> // data about data means meta data charset means encoding for webpage and here utf 8 means converts into machine code by 8 bit 
    <meta name="viewport" content="width=device-width" /> contents are fit within screeen  so we can see laoptop , pohone , tab
    <title>My test page</title> show on title bar 
  </head> 
  <body>// body of the code
    <img src="images/firefox-icon.png" alt="My test image" />
  </body>
</html>


#  HTML tags commonly 

1. **Document Structure**
   - `<!DOCTYPE html>`: Defines the document to be HTML5.
   - `<html>`: The root element of an HTML document.
   - `<head>`: Contains meta-information about the document.
   - `<body>`: Contains the visible content of the HTML document.

2. **Head Elements**
   - `<meta>`: Provides metadata about the document, like character set or viewport settings.
   - `<title>`: Specifies a title for the document.
   - `<link>`: Defines relationships between the document and external resources (like stylesheets).
   - `<style>`: Contains style information for the document.
   - `<script>`: Contains scripts or points to external scripts.

3. **Text Formatting**
   - `<h1>`, `<h2>`, ... `<h6>`: Headings, from largest and most important to smallest.
   - `<p>`: Paragraph.
   - `<br>`: Line break.
   - `<strong>`: Bold text.
   - `<em>`: Italic text.
   - `<abbr>`: Abbreviation or acronym.
   - `<blockquote>`: A section quoted from another source.

4. **Links and Media**
   - `<a>`: Anchor (for creating hyperlinks).
   - `<img>`: Image.
   - `<audio>`: Audio content.
   - `<video>`: Video content.

5. **Lists**
   - `<ul>`: Unordered list.
   - `<ol>`: Ordered list.
   - `<li>`: List item (used within `<ul>` or `<ol>`).

6. **Containers**
   - `<div>`: A block-level container.
   - `<span>`: An inline container.

7. **Form Elements**
   - `<form>`: Defines a form.
   - `<input>`: Input fields (can be text, checkbox, radio, etc.).
   - `<label>`: Label for an `<input>` element.
   - `<textarea>`: Multi-line text input.
   - `<select>`: Dropdown list.
   - `<option>`: Option inside a `<select>` list.
   - `<button>`: Clickable button.

8. **Table Elements**
   - `<table>`: Table.
   - `<tr>`: Table row.
   - `<td>`: Table data (cell).
   - `<th>`: Table header.
   - `<tbody>`: Table body group.


9. **<header>**
    Represents a container for introductory content or navigation.
    ```html
    <header>
      <h1>Site Title</h1>
      <nav>
        <a href="#">Home</a> | <a href="#">About</a> | <a href="#">Contact</a>
      </nav>
    </header>
    ```

10. **<nav>**
    Represents a section with navigation links.
    ```html
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Products</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
    ```

11. **<article>**
    Represents a self-contained composition in a document, such as a blog post or a news story.
    ```html
    <article>
      <h2>Blog Post Title</h2>
      <p>Blog post content...</p>
    </article>
    ```

12. **<section>**
    Represents a standalone section of a document, such as tabs, tabbed content, or any content that stands alone.
    ```html
    <section>
      <h2>Section Title</h2>
      <p>Section content...</p>
    </section>
    ```

13. **<aside>**
    Represents content that is related to the main content but can stand alone, such as a sidebar or advertisement.
    ```html
    <aside>
      <h3>Sidebar Title</h3>
      <p>Sidebar content...</p>
    </aside>
    ```

14. **<footer>**
    Represents a container for the footer of a document or section.
    ```html
    <footer>
      <p>Copyright 2023. All rights reserved.</p>
    </footer>
    ```


