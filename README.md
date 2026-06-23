# CSS Introduction
**What is CSS ?**   
CSS is the language we use to style a Web page.
- CSS stands for Cascading Style Sheets
- CSS describes how HTML elements are to be displayed on screen, paper, or in other media
- CSS saves a lot of work. It can control the layout of multiple web pages all at once
- External stylesheets are stored in CSS files

**Why Use CSS ?**   
CSS is used to define styles for your web pages, including the design, layout and variations in display for different devices and screen sizes.

## CSS Selectors
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

## CSS Comments
Comments are used to explain the CSS code, and may help when you edit the source code at a later date. 

Comments are also used to temporarily disable sections of CSS code within a stylesheet.     

Comments are ignored by browsers!  

A CSS comment is placed inside the HTML `<style>` element, and starts with `/*` and ends with `*/`

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `/* This is comment */`

## CSS Colors
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

## RGB Value    
An RGB color value represents RED, GREEN, and BLUE light sources.    
In CSS, a color can be specified as an RGB value, using this formula:   

**rgb(red, green, blue)**   

Each parameter (red, green, and blue) defines the intensity of the color between 0 and 255.     
For example, rgb(255, 0, 0) is displayed as red, because red is set to its highest value (255) and the others are set to 0.

## HEX Value
A hexadecimal color is specified with: #RRGGBB.    
In CSS, a color can be specified using a hexadecimal value in the form:     

**#rrggbb**     

Where rr (red), gg (green) and bb (blue) are hexadecimal values between 00 and ff (same as decimal 0-255).      
For example, #ff0000 is displayed as red, because red is set to its highest value (ff) and the others are set to the lowest value (00).

## HSL Value
HSL stands for hue, saturation, and lightness.  
In CSS, a color can be specified using hue, saturation, and lightness (HSL) in the form: 

**hsl(hue, saturation, lightness)**     
Hue is a degree on the color wheel (from 0 to 360):

- 0 (or 360) is red
- 120 is green
- 240 is blue

**Saturation** is a percentage value: 0% means a shade of gray, and 100% is the full color.

**Lightness** is also a percentage; 0% is black, 50% is neither light or dark, 100% is white.

