# Positioning
This exercise is a basic introduction to layouts using CSS positioning. Although layout methods can be used in combination—this exercise focuses solely on practicing skills related to positioning.

In this exercise you will:
- Practice using 3 different types of positioning: fixed, absolute and relative. You will also use companion properties like top, bottom, left, and right.
- Code based on a provided high-fidelity prototype
- Code in a modular fashion by focusing on the design of a product module (similar to a list item in an Article List)

## Tasks
- **Preview**: Make sure you know what your goals are! The prototypes you will need to follow are provided in the screenshots folder. 
	- For this exercise you will focus on developing a mobile design that is fluid but will not worry about layouts for larger screens. 
	- Most of the page layout has been coded for you, your focus will be the layout of the product modules.
- **Code the Product Module**: This will require you to do three things:
	- Constrain the image to the module and make the images the full width of the module.
	- Place the tea category in the top left of the module; on top of the image.
		- _Hint: for positioning to work, make sure the parent element of the modules or a further descendant explicitly has `position: relative;` set on it._
	- Place the button in the bottom right of the module; below all of the content. Note that this layout could be accomplished with floats but you need to implement with positioning and make sure the button does not overlap any text (even when the screen is zoomed in 200%).
	- - _Hint: To accomplish this you need to add space to the bottom of the product module._
- **Code the Page Header**: Although it may not be clear in the prototypes, the designer would like the site identifier (Teatastic) visible at all times at that top of the page even when the page is scrolled. This means that the products and other content would scroll behind the header at the top of the page.
	- The header should span the full width of the viewport (Browser window).
	- When at the very top of the page you should be able to see all content. 
		- _Hint: You will need to add some space above main for that to happen._
- **Make it live**: Publish your finished product (just make sure you have valid and accessible code first).

## Verify the code meets standards
- CSS Validation
- HTML Validation
- Accessibility checker (WAVE or AXE)

## Resources
- [MDN CSS:Position](https://developer.mozilla.org/en-US/docs/Web/CSS/position)
- [CSS-Tricks Position](https://css-tricks.com/almanac/properties/p/position/)
- [MDN CSS: Box Model](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)
