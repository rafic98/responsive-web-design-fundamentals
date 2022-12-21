# CSS Grid latout

- it is a two dimensional grid-based layout system in CSS

- Grid layout can be used to build complex layouts that are way too complicated for Flexbox to handle

- Divide a container into rows and columns and lays out within cells

- grid is layout in, we create layout the we place items into it

## Grid terminology

### Grid container

- The HTML element that is the parent for all the items in the grid. it is the element that has the display property defined on it and set equal to grid.

### Grid items

- The direct children of the grid container element.

### Grid lines

- The dividing lines that make up the structure of the grid (can be either vertical or horizontal)

- the grid lines are numbered, starting from 1 (they are used to define grid areas and cells)

### Grid cells

- A single unit of a grid is called a grid cell, it is formed by the space between two adjacent row and column grid lines.

### Grid tracks

- A Grid track is the space between 2 adjacent grid lines.

### Grid area

    - A grid area is composed of any number of grid cells

## grid-templte columns

- grid-template-coloumns: 100px 100px 100px;
  creates a grid each cell is 100px x 100px
- it can also be done using the repeat() fuction:
  - grid-template-columns: repeat(3,100px);
- values can be in absolute or relative values

  ### other units:

      - fr = fractions
      - auto -> takes remaining space

## min-content

- allows specifiying width for a column or height for a row and ensures that the cells take the minimum amount of space that the content needs.
- lowest possible width

## max-content

- Allows specifying dynamic width for a coloumn or height for a row and ensures that the vcells takes the maximum amount of space that the content needs.
- takes as much sapce as possible to fit the content

## minmax()

- this method is used to set a range of width for a column or a height for a row.
- the function accepts 2 parameters, which reperesnt the minimum and maximum values
- eg: grid-template-columns:2fr minmax(200px,2fr) 3dr;

## grid-gap

- allows you to specify the space between 2 adjacent rows and columns

- eg: grid-row-gap:10px; grid-column-gap:10px;

### shorthand for grid-gap

- grid-gap:<grid-row-gap><grid-column-gap>;
- eg: grid-gap: 10px 10px;

## Placing items

- A grid item by default takes up 1 cell in a grid.

- the item that is in the cell is placed in is chosen with the help of some rules and the order of the item in the list of items within the grid container.

- A grid item is placed in a grid by referring to specific grid lines.

- Start and end grid lines are specified for coumns and rows using CSS properties.

### Grid-column

- grid-column-start: USed on an item to speciy the start of grid line for the item.
- grid-column-end: Used to specify the end line for the item.

- eg: grid-column-start:2; grid-column-end:4;

- Shorthand: grid-column: 2/4;

- both properties ensure that the item takes all coloumns/rows between start and end gridlines specified
