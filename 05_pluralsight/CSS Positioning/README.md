### Pluralsight course   
https://app.pluralsight.com/library/courses/css-positioning-1834/table-of-contents

Position attribute allows to move an element in the document. (respective to document or parent)      
It's important to understand how and element and it's surrounding elements behaves when changing it's position attribute.   
 - Static - default positioning in document
 - Fixed - fixed position respect Browser window
 - Absolute - fixed position respective to docuemnt or fixed position respective to closest parent with position attribute set
 - Relative - sets the position of an element relative to its original position.
 - Inherit - inherit positioning from parent
 - Sticky - doesn't support most browsers, not much used
## Static positioning
 - Default positioning for elements. (How it would be in DOM by default)
 - Doesn't respect position values (top, bottom, left, right)
## Fixed positioning
 - ***Fixed positioning*** ’fixes‘ the position of an element **relative to the browser window.**   
 - The element always stays fixed in place, even when scrolling.   
 - **Surrounding elements** ignores fixed position elements.   
 - Can apply ***top***, ***bottom***, ***left***, ***right*** properties. (with repect to browser window)   

## Absolute positioning
 - ***Absolute positioning*** takes an element out of document flow, meaning the browser acts as if the element has no width and height, and the    
 **Surrounding elements** on the page move up as if it was never there.    
 - The position of the element is then fixed with respect to the ***top level container***, or the ***closest parent with a set positioning***.
 - If parent doesn't have a position attribute, absolute will behave similar to **fixed**, but the difference is element will move along with the page when scrolling.   
  

## Relative positioning
 - ***Relative positioning*** sets the position of an element *relative to its original position*.   
 - The element's original width and height is retained in document flow and *other elements behave as if it was in its original position*.
 - Position changes to container (parent) element doesn't effect on relative positioned elements

## Inherit positioning
 - Inherit position from parent element.
 - Initially looks like no changes, but the thing is we can apply left,right,bottom,top positioning values after adding inherit position. (otherwise default is *static* and won't respond to lrbt properties)


## z-index property
 - control the stacking of the elements.

## float property
 - Removes the element from document flow, but other elements respect the width and height of the floating element. (unlike position attributes)
 - Easier to position elements on left, right rather than using padding, margin.
## clear property
- avoid floating elements, and start from new line.

## couple of methods to center an element
