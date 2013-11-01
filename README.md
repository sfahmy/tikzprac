# TikZ/PGFPlots Practical CE7451

## TikZ
For this exercise, we will try to recreate the figure in `simplearch_ref.pdf`:

1. Clone the repository
2. Compile the `simplearch.tex` file to see what you have so far
3. Change the *documentclass* to `standalone` and recompile
4. Add a block for the memory with a narrower defined width, placing it beside the Accelerator block using relative positioning
5. Draw a thick line for the bus (use the `line width` parameter), from below the bottom left corner of accelerator to the bottom right corner of memory
6. Draw the arrows between the top blocks and the bus
7. Place two small blocks, using the style below the bus, using the 0.25 and 0.75 positions
8. Connect up the final blocks to complete the diagram (You can specify a point that is the intersection of two lines from two points using `(a |- b)` as the coordinate)

##PGFPlots
For this exercise, we will take a basic plot, add more data points and add a pre-determined function line:
1. Compile `simpleplot.tex`, and change to the standalone class
2. Modify the plot so that only the marks are shown
3. Add the second data series from the file `plot2.data`
4. Modify the colours so the two plots are distinct
5. Now add a third mathematical plot: `\addplot {expression}` where the expression is for 3x^2-2x+4
6. Add `domain=0:20` do get the line to draw for the required range
6. Modify the style so the expression plot stands out from the others
7. Label the axes *x* and *y*