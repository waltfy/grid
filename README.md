grid
====

A simple grid for LESS.

# Usage
====

Grid will look for 3 variables:
* `GRID_columns`: the number of columns of your grid.
* `GRID_margin`: the size of the margin (%).
* `GRID_bp`: the break-point in which the width should become 100% and margins to be removed.

Follow the example below:
```less
@import 'GRID';
@GRID_columns: 6;
@GRID_margin: 2.4;
@GRID_bp: 31.25em;

// define your components span
.a {
  background: red;
  .grid(2);
}

.b {
  background: blue;
  .grid(2)
}

.c {
  background: green;
  .grid(2)
}
```
