# RH-DEMO: CSS EXERCISE #3 / METHOD-3

### Project solution
CSS Grids can be utilized to organize containers within a parent div. The basic principles of CSS Grid is that there are columns and rows established with the parent div. Child divs, sections, asides, etc. can then be given a grid ID or class to later help designate it’s spot in the grid family. 

1. To start we must alter the HTML. First, consolidate all element of a page into a master container. In our example, we’ll go with `grid-container`.

2. Next, give your child containers grid item class or IDs. In this case, we'll go with class names of `grid-item-1` and `grid-item-2`.

3. Go into the style sheet and add the following property values for the selector `grid-container`.

```
display: grid; 
grid-template-columns: repeat(3, 1fr);
grid-gap: 0px;
grid-auto-rows: minmax(100px, auto);

``` 
Display is set to `grid`. Our `grid-template-columns` will be set to `3`. The `grid` gaps in between will be set to `0px` for now. The `grid-auto-rows` will be given a min and max value of `minmax(100px, auto)` 100px is the height and width is set to auto.

4. Next we'll give `grid-item-1` and `grid-item-2`property values:

```
section.grid-item-1 {
  grid-column: 1/ 3;
  grid-row: 1 / 4;
}

aside.grid-item-2 {
  grid-column: 3 / 4;
  grid-row: 1 / 3;
  background: pink;
}

```

The property value `grid-columns` is written in shorthand form. Left number represents the start of its position in the grid of columns (in our 3 columns) and the right number represents the end position.

The property value `grid-row` can be written in shorthand form as well, but since we are dealing with only one row, we will just list both with a valule of `1`.

5. Add back the the green border on `grid-item-1` with a property value of `border: 15px solid lightgreen;`.

6. Remove margins from `article` element.

7. Remove `article` and `section` from the last selector list. This will prevent any awkward spacing between the grids. If you need to set specific spacings, target the individual elements or play with the CSS Grid `grid-gap` settings.


