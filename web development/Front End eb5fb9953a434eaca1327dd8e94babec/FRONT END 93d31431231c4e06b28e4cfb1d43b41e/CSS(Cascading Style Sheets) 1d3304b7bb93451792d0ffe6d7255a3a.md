# CSS(Cascading Style Sheets)

# Why is it used?

CSS is used instead of HTML because it allows for more control over the appearance of a web page. HTML defines the structure of a web page, but CSS defines how it looks. This allows for more flexibility and creativity in web page design.
For example, HTML defines a paragraph as a block of text. CSS can be used to change the font, size, color, and alignment of the text. HTML defines an image as a rectangular object. CSS can be used to change the size, shape, and position of the image.
CSS is also more efficient than HTML. HTML defines the structure of a web page, but CSS defines how it looks. This means that CSS can be used to change the appearance of a web page without having to change the HTML code. This can save time and effort when designing web pages.

### **Ways of implementing Using Css**

There are three ways of using CSS:

- Inline css
    
    To write inline CSS, you can use the style attribute. The style attribute is a shorthand for the style element. It allows you to specify CSS properties directly on an HTML element.
    To use the style attribute, you add the style attribute to the element you want to style. The value of the style attribute is a string of CSS properties and values. For example, to set the font size of an element to 12px, you would use the following code:
    
    `<p style="font-size: 12px;">This is a paragraph.</p>`
    You can also use the style attribute to set multiple CSS properties at once. For example, to set the font size, color, and background color of an element, you would use the following code:``
    
    `<p style="font-size: 12px; color: red; background-color: yellow;">This is a paragraph.</p>`
    The style attribute is a powerful tool that can be used to quickly and easily style HTML elements.``
    
    But this is only for a single element you want to use i.e it can be used in any tag like body,head etc.
    
- internal css
    
    To write internal CSS, you can use the style element. The style element is a container for CSS code. It can be placed inside the head element of an HTML document.
    To use the style element, you add the style element to the head element of your HTML document. The value of the style element is a string of CSS code. For example, to set the font size of all paragraphs to 12px, you would use the following code:
    
    `<head>`
      `<style>`
        `body {`
            `font-size: 12px;`
    
               `}`
      `</style>`
    `</head>`
    
    You can also use the style element to set multiple CSS properties at once. For example, to set the font size, color, and background color of all paragraphs, you would use the following code:
    
    `<head>`
      `<style>`
         `body {`
          `font-size: 12px;`
           `color: red;`
           `background-color: yellow;`
            `}`
      `</style>`
    `</head>`
    
    The style element is a powerful tool that can be used to quickly and easily style an entire HTML document.
    
    When you define style in the head tag, the style is applied to all elements in the document. When you define style in the body tag, the style is only applied to the elements within the body tag.
    
- external css
    
    Here is a basic program to show external CSS:
    
    `<!DOCTYPE html>`
    `<html>`
    `<head>`
     `<title>External CSS</title>`
      `<link rel="stylesheet" href="style.css">`
    `</head>`
    `<body>`
     `<p>This is a paragraph.</p>`
    `</body>`
    `</html>`
    
    The `link` element in the head tag tells the browser to load the CSS file `style.css`. The CSS file contains the style rules that are used to style the elements in the document.
    Here is an example of the contents of the `style.css` file:
    
    `body {`
     `font-size: 12px;`
     `color: red;`
     `background-color: yellow;`
    `}`
    
    This CSS file sets the font size of the body element to 12px, the color of the body element to red, and the background color of the body element to yellow.
    When the browser loads the HTML document, it will also load the CSS file and apply the style rules to the elements in the document.
    

CSS has four types of selectors:

- **Type selectors** select elements based on their type, such as `h1`, `p`, or `img`.
- **Class selectors** select elements based on the class attribute, such as `.my-class`.
- **Id selectors** select elements based on the id attribute, such as `#my-id`.
Type selectors are the most basic type of selector. They select all elements of a particular type, such as all `h1` elements or all `p` elements.
Class selectors are used to select elements that have a particular class attribute. For example, the selector `.my-class` would select all elements that have the `my-class` class attribute.
Id selectors are used to select elements that have a particular id attribute. For example, the selector `#my-id` would select the element that has the `my-id` id attribute.
CSS also has a number of other selectors, such as attribute selectors, pseudo-classes, and pseudo-elements. These selectors can be used to select elements based on their attributes, their position in the document, or their appearance
- The universal selector is a CSS selector that matches all elements. It is represented by the symbol `*`.
The universal selector can be used to apply a style to all elements in a document, or to select a specific element by its position in the document.
For example, the following CSS rule will set the font size of all elements to 12px:

      *{
       font-size: 12px;
         }

The following CSS rule will set the font size of the first element in the document to 12px:

*:first-child {
font-size: 12px;
}

The universal selector can be used in conjunction with other selectors to create more specific rules. 

# **CSS PROPERTIES**

CSS properties are the characteristics of an HTML element that can be manipulated using CSS. They are used to change the appearance of an element, such as its color, size, or position. CSS properties are defined using a property name and a value, separated by a colon

### colour

The color property is a CSS property that sets the color of an element. It can be used to set the color of the element's text, background, or border. The color property takes a color value, which can be either a color name, a hexadecimal color code, or a RGB color value. For example, the following CSS code sets the color of an element to red:

`color: red;`

color: #RRGGBB;

color: #FF0000;

color: rgba(RR, GG, BB, AA);

color: rgba(255, 0, 0, 0.5);
There are many different color names that can be used with the color property. For a complete list of color names, see the CSS color names reference.

use colorhunt or any other websites for colours 

### Font size

 

The font-size property in CSS is used to set the size of the text in an element. It can be set using a variety of different units, including pixels, ems, and rems.
To set the font size of an element using pixels, you can use the following syntax:

`font-size: 16px;`

This would set the font size of the element to 16 pixels.
To set the font size of an element using ems,    1 pixel = 1/96 inch.  you can use the following syntax:

`font-size: 1.2em;`

This would set the font size of the element to 1.2 times the size of the parent element.
To set the font size of an element using rems, you can use the following syntax:

`font-size: 1rem;`

This would set the font size of the element to 1 times the size of the root element

`width: 100pt;`

The point is a unit of measurement that is used to specify the size of an element in CSS. It is represented by the letter `pt`. The code would set the width of an element to 100 points. 1 point = 1/72 inch.

``

### Font weight

The font weight property in CSS is used to set the thickness of a font. It can be set to one of the following values:
* normal
* bold
* bolder
* lighter
* 100
* 200
* 300
* 400
* 500
* 600
* 700
* 800
* 900
To set the font weight, use the following syntax:

`font-weight: <value>;`

For example, to set the font weight to bold, you would use the following code:

`font-weight: bold;`
lighter and bolder are relative and increases or decreases by 100

### Font family

The font-family property in CSS is used to set the font family for an element. It can be set to a single font family name, or a list of font family names separated by commas.
To set the font family, use the following syntax:

`font-family: <font-family-name>;`

For example, to set the font family to "Helvetica", you would use the following code:

`font-family: Helvetica;`

You can also set the font family to a list of font family names, in order of preference. For example, to set the font family to "Helvetica", "Arial", and "Times New Roman", you would use the following code:

`font-family: Helvetica, Arial, Times New Roman;`

If the browser does not have any of the fonts in the list, it will use the closest matching font that it does have.

quotes are necessary when using a font name in CSS. This is because font names can contain spaces, and spaces are not allowed in CSS property values. For example, if you want to use the font name "Times New Roman", you would need to use the following code:

`font-family: "Times New Roman";`

Without the quotes, the browser would not know that you are referring to the font name "Times New Roman" and would instead try to use the variable "Times New Roman"

### Text align

The text-align property in CSS controls the horizontal alignment of text within an element. It can be set to one of the following values:
* left: Aligns the text to the left side of the element.
* right: Aligns the text to the right side of the element.
* center: Centers the text within the element.
* justify: Justifies the text so that it fills the entire width of the element.
To set the text-align property, use the following syntax:

`text-align: value;`
where `value` is one of the values listed above.``

# Padding border and Margin

so padding is the gap between the invisible box and the contents inside the box

Border is the border of the box

Margin is the border to other elements

## combining css selectors

 selector, selector {

Colour: blue violet

}

We apply this so that we can apply to multiple elements at once

selector > selector {

Colour: firebrick;

}

Use this to put it for child of a selector not descendant

selector selector {

Colour: blue;

}

We uses to apply to the descendant

selectorselector {

Colour: sea green;

}

We use this for combining selectors are apply. Where all selectors are true.

selector selectorselector {

 font – size: 2rem;

}

This is used for combining combiners

## CSS positioning

We have four positions: 

- Static positioning
- Relative positioning
- Absolute positioning
- Fixed positioning

 static positioning: just a position, it's supposed to be in and is relative to the web browser

Relative position: it is relative to the position It is supposed to be in.

Absolutely positioning: position related to the nearest position ancestor or top left corner of webpage

 fixed positioning: it is relative to the screen, not the browser so how much ever you scroll it's fixed there 

Z-index:It is so that you can change the value of like the Z axis if you put it -1 by default, everything is zero, so the minus one goes to behind every element

 how do you create a circle: we use the property called as border-radius which we can use percentage or pixel value