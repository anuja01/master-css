### Pluralsight course   
https://app.pluralsight.com/library/courses/css-positioning-1834/table-of-contents

Position attribute allows to move an element in the document. (respective to document or parent)      
It's important to understand how and element and it's surrounding elements behaves when changing it's position attribute.   
 - Fixed - fixed position respect to document
 - Absolute - fixed position respective to docuemnt or fixed position respective to closest parent with position attribute set
 - Relative - 

## Fixed positioning
 - ***Fixed positioning*** ’fixes‘ the position of an element **relative to the browser window.**   
 - The element always stays fixed in place, even when scrolling.   
 - **Surrounding elements** ignores fixed position elements.   
 - Can apply ***top***, ***bottom***, ***left***, ***right*** properties. (with repect to browser window)   

## Absolute positioning
 - ***Absolute positioning*** takes an element out of document flow, meaning the browser acts as if the element has no width and height, and the other elements on the page move up as if it was never there.    
 - The position of the element is then fixed with respect to the ***top level container***, or the ***closest parent with a set positioning***.
 - If parent doesn't have a position attribute, absolute will behave similar to **fixed**, but the difference is element will move along with the page when scrolling.   
  

## Absolute positioning
 - ***Relative positioning*** sets the position of an element *relative to its original position*.   
 - The element's original width and height is retained in document flow and *other elements behave as if it was in its original position*.