CSS : Cascading style sheet it provides styling to content 

1. **Selectors & Properties**
   - **Selector:** Specifies which elements in the HTML document are styled. Examples include element names (e.g., `h1`, `p`), classes (e.g., `.myClass`), IDs (e.g., `#myID`), and more.
   - **Property:** The aspect you want to change (e.g., color, font-size).
   - **Value:** The value you set the property to.

   ```css
   selector {
     property: value;
   }
   ```

   For example:

   ```css
   h1 {
     color: red;
   }
   ```

2. **Incorporating CSS**:
   - **Inline:** Apply styles directly on individual HTML elements using the `style` attribute.
     ```html
     <p style="color: blue;">This is a blue text.</p>
     ```
   - **Internal (or Embedded):** Include styles within the `<head>` of the HTML document using the `<style>` tag.
     ```html
     <style>
       p {
         color: green;
       }
     </style>
     ```
   - **External:** Link to an external `.css` file. This method is the most common for larger websites as it ensures consistency and separates content from design.
     ```html
     <link rel="stylesheet" href="styles.css">
     ```

3. **Classes & IDs**:
   - **Class:** Used for styling multiple elements. Denoted by a `.` before its name in CSS.
     ```css
     .highlight {
       background-color: yellow;
     }
     ```
   - **ID:** Used for styling a single, unique element. Denoted by a `#` before its name in CSS.
     ```css
     #header {
       background-color: black;
     }
     ```

4. **Box Model**: Every HTML element is considered a box, and can be described by properties like:
   - **Content:** The actual content of the box, where text and images appear.
   - **Padding:** Space around the content inside the border.
   - **Border:** The border surrounding the padding (if any) and content.
   - **Margin:** Space around the outside of the border.




