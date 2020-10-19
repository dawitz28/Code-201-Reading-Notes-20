
**IMAGES**
- <img>
- To add an image into the page you need to use an <img> element. This is an empty element (which means there is no closing tag). It must carry the following two attributes:
- src - This tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your own site. (Here you can see that the images are in a child folder called images — relative URLs
- alt - This provides a text description of the image which describes the image if you cannot see it.
- title - You can also use the title attribute with the <img> element to provide additional information about the image. Most browsers will display the content of this attribute  when the user hovers over the image.
##Height & width of the images## 
- You will also often see an <img> element use two other attributes that specify its size:
- height - This specifies the height of the image in pixels.
- width - This specifies the width of the image in pixels.
##Aligning images horizontally##
- Align - The align attribute was commonly used to indicate how the other parts of a page should flow around an image. It has been removed from  HTML5 and new websites should use CSS to control the alignment of images.
- The align attribute can take these horizontal values:
- Left - This aligns the image to the left (allowing text to flow around its right-hand side). 
- Right - This aligns the image to the right (allowing text to flow around its left-hand side).
- Aligning images vertically
- There are three values that the align attribute can take that control how the image should align vertically with the text that surrounds it:
- Top - This aligns the first line of the surrounding text with the top of the image.
- Middle - This aligns the first line of the surrounding text with the middle of the image.
- Bottom - This aligns the first line of the surrounding text with the bottom of the image.tom
##COLOR## 
- FORGROUND COLOR (color)
- The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:
- rgb values
- These express colors in terms of how much red, green and blue are used to make it up. For example: rgb (100,100,90)
- hex Codes
- These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. 
- Color names
- There are 147 predefined color names that are recognized by browsers. For example: DarkCyan
Above each CSS rule in this example you can see how CSS allows you to add comments to your CSS files. Anything between the /* symbols and the */ symbols will not be interpreted by the browser. They are shown in grey above.
- FORGROUND COLOR (backgound-color)
- CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box.
- OPACITY - CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).
- HSL & HSLA (hsl, hsla) - The hsl color property has been introduced in CSS3 as an alternative way to specify colors. The value of the property starts with the letters hsl, followed by individual values inside parentheses for:
- HUE - This is expressed as an angle (between 0 and 360 degrees).
- SATURATION - This is expressed as a percentage.
- LIGHTNESS - This is expressed as a percentage with 0% being white, 50% being normal, and 100% being black.
- The hsla color property allows you to specify color properties using hue, saturation, and lightness as above, and adds a fourth value which represents transparency (just like the rgba property). The a stands for:
- ALPHA - This is expressed as a number between 0 and 1.0. For example, 0.5 represents 50% transparency, and 0.75 represents 75% transparency.
**TEXT** 
- font-family - The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies. The value of this property is the name of the typeface you want to use.
- The properties that are used to control fonts can be broken into two groups.
- Those that directly affect the fonts appearance are bold italic.
- Those that have the same effect regardless of the font type. color, spacing and kerning are examples.



