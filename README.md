# Flexbox and Responsive Design Practice

## Overview
This project demonstrates the use of **HTML and CSS** to practice various Flexbox properties and responsive design techniques. The primary focus is on understanding how Flexbox properties influence layout and alignment, ensuring a flexible and adaptive design.

### Alignment & Flex Sizing
- **align-content**: Controls the alignment of flex lines when there is extra space in the cross axis.
- **align-self**: Allows individual flex items to override the align-items property.
- **align-items**: Defines how flex items are aligned along the cross axis.
- **flex-basis**: Specifies the initial size of a flex item before it grows or shrinks.
- **flex-grow**: Determines how much a flex item will grow relative to others.
- **flex-shrink**: Controls how flex items shrink if necessary.
- **flex shorthand**: A shorthand property that combines `flex-grow`, `flex-shrink`, and `flex-basis`.

### Flexbox Layout & Wrapping
- **flex-wrap**: Specifies whether flex items should wrap onto multiple lines.
- **justify-content**: Defines alignment along the main axis.
- **flex-direction**: Determines the direction of the flex container (row, column, etc.).

## Responsive Design with Media Queries
In addition to practicing Flexbox, this project incorporates **media queries** to ensure a responsive layout across different screen sizes. Media queries are used to:
- Adjust the flex properties on screen width.
- Change layout structures for better readability on smaller devices.
- Modify font sizes, spacing, and other CSS properties for an optimized user experience.
### Example Media Query
```css
media (max-width: 768px) {
    .container {
        flex-direction: column;
        align-items: center;
    }
    .item {
        flex-basis: 100%;
    }
}
```
## How to Use
1. Clone or download the repository.
2. Open the `index.html` file in a web browser. 
3. Experiment with different screen sizes to see Flexbox and media queries in action.
4. Modify the CSS file to practice and enhance your understanding of Flexbox.

## Technologies Used
- **HTML5** for structuring the layout.
- **CSS3** for styling and implementing Flexbox properties.
- **Media Queries** for creating a responsive design.

