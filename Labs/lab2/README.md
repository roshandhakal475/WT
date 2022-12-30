In CSS, the flow layout is the default layout for elements in a document. This allows elements to be placed one after the other in the order they appear in the HTML. The position of each element is determined by the position of the elements before it and the available space in the parent element.

The positioned layout, on the other hand, allows you to specify the exact position of an element within its parent element or the document itself using the position, top, right, bottom, and left properties. There are four possible values for the position property:

# static: This is the default value and elements will be positioned according to the normal flow of the document.

# relative: The element is positioned relative to its normal position in the flow of the document. You can use the top, right, bottom, and left properties to specify how the element should be moved from its normal position.

# absolute: The element is positioned relative to its nearest positioned ancestor (if any) or the initial containing block (if there is no positioned ancestor). You can use the top, right, bottom, and left properties to specify how the element should be positioned within its containing block.

# fixed: The element is positioned relative to the initial containing block, which is the viewport for most devices. The element will remain in the same position regardless of scrolling. You can use the top, right, bottom, and left properties to specify how the element should be positioned within the viewport.
 
 Here's an example of using the positioned layout to position an element with a position of absolute 50 pixels from the top and left of its parent element:


.element {
  position: absolute;
  top: 50px;
  left: 50px;
}