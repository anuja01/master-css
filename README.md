# master-css
Useful concepts in CSS   

### 01 - `display` property  
https://www.youtube.com/watch?v=Qf-wVa9y9V4 

- `display: block`   
  - Element will take up the entire width.
  - Adds new line above and below to element. So no side by side elements.
  - Can set width, height to the element.
  - `div` is by default display `block`.

- `display: inline`
    - Element take the minimum amount of width (space) as possible to fit the content inside.
    - Elements fit together side by side.
    - Can't set width, height to the element.
    - `span` is by default display `inline`.

- `display: inline-block`
  - Same behaviours as `inline`
  - But can set width, height to the element.

- `display: none`
  - Acts as if element is completely deleted from the HTML.
  - No space is taken.


### 03 - `flexbox` layout model
https://www.youtube.com/watch?v=fYq5PXgSsbE
- Set `css` property `display: flex` for the wrapper to create a flexbox container.
- Allows you to style flexibility and sizing of elements inside the flexbox container from the actual container selector, rather than styling individual element.
- Items inside a flex container will shrink to fit the browser widow by default
- By default flexbox container laid out in a row (Horizontal). (`flex-direction: row`)
- Can change layout to vertical by setting `flex-direction: column`, then main axis will be vertical and property behaviour will change according to main axis.

### 04 - `CSS Grid` layout model
https://www.youtube.com/watch?v=9zBsdzdE4sM
