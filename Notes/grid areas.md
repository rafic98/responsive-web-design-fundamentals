# Grid Areas

- A grid template area is an area that spans, one or multiple cells. it is defined using grid-template-areas CSS property.

- using names for an area in a grid is much more convinient and intuitive.

## Grid areas to place items

## grid areas properties

### grid-template-areas

- grid-template-areas:
  "R1C1 R1C2 R1C3"
  "R2C1 R2C2 R2C3"
  "R3C1 R3C2 R3C3";
  - Creates a 3x3 grid.
  - you can name them however you want,
  - if you repeate the name of grid areas will cause the content to span across those cells.
  - a period(.) segnifies an empty cell. (you cannot allocate this cell to an item to a grid)
- grid-area:R1; if we place this css property inside a certain class, the element with this class will occupy the area specified.
