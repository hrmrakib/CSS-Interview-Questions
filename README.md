## CSS Interview Question for Fresher 

A brief description of what this project does and who it's for

### 1. What is CSS?

CSS (Cascading Style Sheets) is a language used to style the presentation of web pages written in HTML and XHTML. It controls how HTML elements are displayed on screen, in print, or in other media. CSS allows developers to define colors, fonts, layouts, and other visual aspects, ensuring consistent and attractive design across different devices and screen sizes.

### 2. What do you understand by the universal sector?
A universal selector is a selector that matches any element type's name instead of selecting elements of a particular type.

```css

* {
  property: value;
}

```

### 3. What are the elements of the CSS Box Model? 

➡️ The CSS box model defines the layout and design of CSS elements. The elements are content (like text and images, padding (the area around content), border (the area around padding), and margin (the area around the border).

` → Content, Padding, Border, Margin `

### 4. What is the difference between a class and an ID?

Class is a way of using HTML elements for styling. They are not unique and have multiple elements. Whereas ID is unique and it can be assigned to a single element. 


### 5. Define z-index.
This is one of the most frequently asked CSS interview questions. Z-index is used to specify the stack order of elements that overlap each other. Its default value is zero and can take both negative and positive values. A higher z-index value is stacked above the lower index element. It takes the following values- auto, number, initial, and inherit. 


### 6. What is the difference between inline, inline-block, and block?
1. Block Elements are `<div> and <p>`. They usually start on a new line and can take space for an entire row or width.
2. Inline elements are `<a>, <span>, <strong>, and <img>` tags. They don't start on a new line. However, they appear on the same line as the content and tags beside them.
3. Inline block elements have padding and margins and set height and width values. Though, they are similar to inline elements.


### 7. What is CSS Box Model and what are its elements?

➡️ This box defines design and layout of elements of CSS. The elements are:

**Margin**: the top most layer, the overall structure is shown

**Border**: the padding and content option with a border around it is shown.  Background color affects the border.

**Padding**: Space is shown. Background colour affects the border.

**Content**: Actual content is shown.

### 8. What is the grid system?
The CSS grid system is a type of powerful layout of 2 dimensional systems with respect to columns and rows.

### 9. What is the difference between flex and grid?

The flex system is 1 dimensional and grid system is 2 dimensional layout.

### 10. What does !important mean in CSS?
The style “!important” in the CSS has the highest precedence. Also, the cascaded property will be overridden with it.

### 11. Does this property work overflow: hidden?
Overflow: the hidden property is used to specify the content’s clipping. We need to add scrollbars to the content area at the time of specified container size exceeding the content limit where the content gets enclosed. This makes the content invisible via clipping; also the overflow value will be hidden.

### 12. Tell us about CSS float property.
The float property of CSS positions an image to the right or left as needed, including text wrapping around it. All properties of elements used before it remain unchanged.

### 13. What are the CSS frameworks?

➡️ CSS frameworks are the preplanned libraries that make easy and more standard-compliant web page styling. The frequently used CSS frameworks are: -
```
- Bootstrap
- Foundation
- Semantic UI
- Gumby
- Ulkit
```

### 14. What is the difference between background and background-color?
background property is a shorthand of the following property:

```css
➡️ background:

 `background-color`
 `background-image`
 `background-repeat`
 `background-attachment`
 `background-position`
 `background` (shorthand property)
```

### 15. What is the use of CSS Opacity?
The CSS opacity property is used to specify the transparency of an element. In simple word, you can say that it specifies the clarity of the image. In technical terms, Opacity is defined as the degree to which light is allowed to travel through an object.

### 16. Explain CSS box-sizing: border-box
`box-sizing: border-box;` adjusts the box model so that an element's padding and border are included in its specified width and height, simplifying layout management and ensuring predictable element dimensions.

### 17. How can CSS be integrated into an HTML page?

➡️ There are three ways of integrating CSS into HTML:

1. Using style tags in the head section
2. Using inline styling
3. Writing CSS in a separate file, and linking to the HTML page by the link tag.

### 18. Explain a few advantages of CSS. 
With CSS, different documents can be controlled using a single site, styles can be grouped in complex situations using selectors and grouping methods, and multiple HTML elements can have classes.

### 19. What is meant by RGB stream?
RGB represents colors in CSS. The three streams are namely Red, Green, and Blue. The intensity of colors is represented using numbers 0 to 255. This allows CSS to have a spectrum of visible colors. 

### 20. How can you target h3 and h2 with the same styling?

➡️ Multiple elements can be targeted by separating with a comma:

h2, h3 {color: red;}

### 21. Name media types allowed by CSS.

➡️ The different media types allowed by CSS are:
```
- speech
- audio
- visual
- tactile media
- continuous or paged media
- grip media or bitmap
- interactive media
```

### 22. How can you use CSS to control image repetition?
➡️ The background-repeat property is used to control the image. Example:

h3 {

background-repeat: none;

}

###


###


###


###


###
































