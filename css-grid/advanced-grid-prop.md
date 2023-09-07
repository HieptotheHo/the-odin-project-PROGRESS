## Advanced Grid Properties

- resize: both.
-> This is a property that allows the user to resize the container by clicking and dragging from the bottom right corner

- overflow: auto 
-> to enable scrolling if we resize the container to be smaller than our grid can accommodate.


- grid-template-rows: repeat(2, 150px); -> 2 rows, each 150px
- grid-template-columns: repeat(5, 150px); -> 5 cols, each 150px

- The most basic way to make our grid items dynamic is by using fractional units, also known as fr.

The fr unit is a way of distributing whatever remaining space is left in the grid. For example, if we have a four-column grid with a total width of 400px and four grid items each on a column track assigned 1fr as their size, all of the grid items should be given one fraction of that 400px of space, which is 100 pixels.


### minmax() 
- minmax() is a CSS function that is specifically used with Grid. It can only be used with the following CSS properties:
+ grid-template-columns
+ grid-template-rows
+ grid-auto-columns
+ grid-auto-rows


- With our grid-template-columns set with minmax() values, each grid item’s width will grow and shrink with the grid container as it resizes horizontally. However, as the grid shrinks, the column tracks will stop shrinking at 150px, and as the grid grows, they will stop growing at 200px. Talk about flexibility! Check it out for yourself below: