# CSS Introduction
**What is CSS ?**   
CSS is the language we use to style a Web page.
- CSS stands for Cascading Style Sheets
- CSS describes how HTML elements are to be displayed on screen, paper, or in other media
- CSS saves a lot of work. It can control the layout of multiple web pages all at once
- External stylesheets are stored in CSS files

**Why Use CSS ?**   
CSS is used to define styles for your web pages, including the design, layout and variations in display for different devices and screen sizes.

# CSS Selectors
CSS selectors are used to "find" (or select) the HTML elements you want to style.
- **Simple selectors** (select elements based on name, id, class)
- **Combinator selectors** (select elements based on a specific relationship between them)
- **Pseudo-class selectors** (select elements based on a certain state)
- **Pseudo-elements selectors** (select and style a part of an element)
- **Attribute selectors** (select elements based on an attribute or attribute value)

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `1_CSS_Selectors.html`

## How To Add CSS
When a browser reads a style sheet, it will format the HTML document according to the information in the style sheet.   
There are three ways of inserting a style sheet:    
1. External CSS - link to an external .css file
2. Internal CSS - use the `<style>` element in the head section
3. Inline CSS - use the style attribute on HTML elements

# CSS Comments
Comments are used to explain the CSS code, and may help when you edit the source code at a later date. 

Comments are also used to temporarily disable sections of CSS code within a stylesheet.     

Comments are ignored by browsers!  

A CSS comment is placed inside the HTML `<style>` element, and starts with `/*` and ends with `*/`

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `/* This is comment */`

# CSS Colors
In CSS, colors are specified by using a predefined color name, or with a RGB, HEX, HSL, RGBA, HSLA value.

**CSS Color Names**     
In CSS, a color can be specified by using a predefined color name:   

![colornames](/Assets/Color_Names.png)

**CSS Background Color**    
You can set the background color for HTML elements:

![background color](/Assets/text_and_background_color.png)

**CSS Text Color**      
You can set the color of text:

![text color](/Assets/text_and_background_color.png)

**CSS Border Color**    
You can set the color of borders:

![border color](/Assets/border_color.png)

**CSS Color Values**        
In CSS, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values:

Same as color name "DodgerBlue":

![color value](/Assets/Color_Values.png)

Same as color name "DodgerBlue", but 60% transparent:

![transperent](/Assets/Color_Values_But_Transparent_60_Percent.png)

### RGB Value    
An RGB color value represents RED, GREEN, and BLUE light sources.    
In CSS, a color can be specified as an RGB value, using this formula:   

**rgb(red, green, blue)**   

Each parameter (red, green, and blue) defines the intensity of the color between 0 and 255.     
For example, rgb(255, 0, 0) is displayed as red, because red is set to its highest value (255) and the others are set to 0.

### HEX Value       
A hexadecimal color is specified with: #RRGGBB.    
In CSS, a color can be specified using a hexadecimal value in the form:     

**#rrggbb**     

Where rr (red), gg (green) and bb (blue) are hexadecimal values between 00 and ff (same as decimal 0-255).      
For example, #ff0000 is displayed as red, because red is set to its highest value (ff) and the others are set to the lowest value (00).

### HSL Value
HSL stands for hue, saturation, and lightness.  
In CSS, a color can be specified using hue, saturation, and lightness (HSL) in the form: 

**hsl(hue, saturation, lightness)**     
Hue is a degree on the color wheel (from 0 to 360):

- 0 (or 360) is red
- 120 is green
- 240 is blue

**Saturation** is a percentage value: 0% means a shade of gray, and 100% is the full color.

**Lightness** is also a percentage; 0% is black, 50% is neither light or dark, 100% is white.

# CSS Backgrounds
The CSS background properties are used to add background effects for elements.  

In these chapters, you will learn about the following CSS background properties:

- background-color
- background-image
- background-repeat
- background-attachment
- background-position
- background (shorthand property)

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex- `4_CSS_Background.html `

# CSS Borders
The CSS border properties allow you to specify the style, width, and color of an element's border.

### CSS Border Style  
The border-style property specifies what kind of border to display.     

The following values are allowed:
- dotted - Defines a dotted border
- dashed - Defines a dashed border
- solid - Defines a solid border
- double - Defines a double border
- groove - Defines a 3D grooved border. The effect depends on the border-color value
- ridge - Defines a 3D ridged border. The effect depends on the border-color value
- inset - Defines a 3D inset border. The effect depends on the border-color value
- outset - Defines a 3D outset border. The effect depends on the border-color value
- none - Defines no border
- hidden - Defines a hidden border

### CSS Border Width
The border-width property specifies the width of the four borders.

The width can be set as a specific size (in px, pt, cm, em, etc) or by using one of the three pre-defined values: thin, medium, or thick:

### CSS Border Color
The border-color property is used to set the color of the four borders.     
The color can be set by:
- name - specify a color name, like "red"
- HEX - specify a HEX value, like "#ff0000"
 RGB - specify a RGB value, like "rgb(255,0,0)"
- HSL - specify a HSL value, like "hsl(0, 100%, 50%)"
- transparent

### CSS Border - Individual Sides
From the examples on the previous pages, you have seen that it is possible to specify a different border for each side.  

In CSS, there are also properties for specifying each of the borders (top, right, bottom, and left):
- border-top-style
- border-right-style
- border-bottom-style
- border-left-style

### CSS Border - Shorthand Property
Like you saw in the previous page, there are many properties to consider when dealing with borders.

To shorten the code, it is also possible to specify all the individual border properties in one property.

The border property is a shorthand property for the following individual border properties:
- border-width
- border-style (required)
- border-color

### CSS Rounded Borders
The border-radius property is used to add rounded borders to an element:

![border radius](/Assets/border_radius.png)

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex- `5_CSS_Border.html`

# CSS Margins And Padding
### CSS Margins
The CSS margin properties are used to create space around elements, outside of any defined borders.

Margins define the distance between an element's border and the surrounding elements.

With CSS, you have full control over the margins. CSS has properties for setting the margin for each individual side of an element (top, right, bottom, and left), and a shorthand property for setting all the margin properties in one declaration.

### Margin - Individual Sides
CSS has properties for specifying the margin for each side of an element:

- **margin-top** - sets the top margin of an element
- **margin-right** - sets the right margin of an element
- **margin-bottom** - sets the bottom margin of an element
- **margin-left** - sets the left margin of an element

**All the margin properties can have the following values:**

- **auto** - the browser calculates the margin
- **length** - specifies a margin in px, pt, cm, etc.
- **%** - specifies a margin in % of the width of the containing element
- **inherit** - specifies that the margin should be inherited from the parent element

### Margin - Shorthand Property
To shorten the code, it is possible to specify all the margin properties in one declaration.    

The margin property is a shorthand property for the following individual margin properties:

If the margin property has four values:
- margin: 25px 50px 75px 100px;
    - top margin is 25px
    - right margin is 50px
    - bottom margin is 75px
    - left margin is 100px

### CSS Padding
The CSS padding properties are used to generate space around an element's content, inside of any defined borders. 

With CSS, you have full control over the padding. There are properties for setting the padding for each side of an element (top, right, bottom, and left), and a shorthand property for setting all the padding properties in one declaration.

### Padding - Individual Sides
CSS has properties for specifying the padding for each side of an element:

- **padding-top** - sets the top padding of an element
- **padding-right** - sets the right padding of an element
- **padding-bottom** - sets the bottom padding of an element
- **padding-left** - sets the left padding of an element

**All the padding properties can have the following values:**

- **length** - specifies a padding in px, pt, cm, etc.
- **%** - specifies a padding in % of the width of the containing element
- **inherit** - specifies that the padding should be inherited from the parent element 

**Note**: Negative values are not allowed.

### Padding - Shorthand Property
To shorten the code, it is possible to specify all the padding properties in one declaration.

The **padding** property is a shorthand property for the following individual padding properties:

- padding-top
- padding-right
- padding-bottom
- padding-left

Here is how it works:

If the padding property has four values:

- **padding: 25px 50px 75px 100px;**
- top padding is 25px
- right padding is 50px
- bottom padding is 75px
- left padding is 100px

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `6_CSS_Margin_And_Padding.html`

# CSS Height and Width      
The CSS height and width properties are used to set the height and width of an element.

### CSS Set height and width  
The height and width properties are used to set the height and width of an element.

The height and width do not include padding, borders, or margins. It sets the height and width of the area inside the padding, border, and margin of the element.

### CSS height and width Values
The height and width properties can have the following values:

- **auto** - This is default. The browser calculates the height and width
- **length** - Defines the height or width in px, cm, em, etc.
- **%** - Defines the height or width in percent of the containing block
- **initial** - Sets the height or width to its default value
- **inherit** - The height or width will be inherited from its parent value

### CSS Min/Max Height and Width
The `min-width` and `max-width` properties are used to set the minimum and maximum width of an element.

The `min-height` and `max-height` properties are used to set the minimum and maximum height of an element.

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `7_height_And_Width.html`

# CSS Box Model
**The CSS Box Model**   

In CSS, the term "box model" is used when talking about web design and layout.

The CSS box model is essentially a box that wraps around every HTML element.

Every box consists of four parts: content, padding, borders and margins.

The image below illustrates the CSS box model:

![box model](/Assets/box_model.png)

Explanation of the different parts (from innermost part to outermost part):

- **Content** - The content of the box, where text and images appear
- **Padding** - Clears an area around the content. The padding is transparent
- **Border** - A border that goes around the padding and content
- **Margin** - Clears an area outside the border. The margin is transparent

The box model allows us to add a border around elements, and to define space between elements.

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `8_Box_Model.html`

