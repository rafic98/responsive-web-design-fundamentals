# CSS Flexbox

- CSS flexbox is used to layout, align and distribute space among HTML elements within a container, even when the size is unknown.

- it is used to lay out items in one dimension, either horizontally or vertically, at a time.

- it offers very powerfil allignment capabilities like:
  - Justify content
  - align items and more
- CSS flexbox is a whole module, not just a single property.

## flex-direction property

- it is used to specify the main axis within a flex container.
- it can be set to either row | or row-reverse | colomn | or column-reverse

## flex-wrap

- the default value is no-wrap but you can change it to wrap, or wrap-reverse to wrap the content on to the next line if there is not enough space in a line.

## flex-flow:<direction><flow>

- it is a shorthand css property to specify flex dirextion and flex wrap in a single line of code.

## Aligning items in flexbox

### Justify-content

- it is used to define how the items should be aligned along the main axis inside a flex container

- justify content values include:
  - flex-start
  - flex-end
  - center
  - space-evenly
  - space-around
  - space-between

### align-items

- it is used to define how the items should be aligned along the cross axis inside a flex container.

- align-items values include:
  - stretch
  - flex-start
  - flex-end
  - center
  - baseline

### align-content

- it is used to align lines of tems as a whole

-align-content values include:

- flex-start
- flex-end
- center
- stretch
- space-around
- space-between
