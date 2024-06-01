# CTB (Color-dependent Plot Style Table)

I don't know how they went from _"Color-dependent Plot Style Table"_ into _"CTB",_ but that's what it stands for. CTB's are called CTB's because the file format is `.ctb`. But what are they?

As the name suggests, a CTB will take a colorful drawing and "translate" it into different colors, line thicknesses, and so on. In other words, it affects **plot styles** depending on the object's color.

<figure markdown="span">
  ![CTB File](../img/CTB-01.jpg)
  <figcaption>Example: a plot style replacing the color "1" (red).</figcaption>
</figure>

## Important things to consider

**A CTB file can only affect index colors** (1–255).  
Any object that use a true color will be completely ignored by your CTB. If line thicknesses are of any importance _—they almost always are—_ 

**CTBs and Layers go hand in hand.**  
In other words, your layer structure should reflect the CTB you're working with, so that 

**Keep the end result simple.**  
Don't go overboard with tons of different linewidths and shades of gray, two or three of each are generally more than enough (most go with 1 black and 1 gray).

**Have few styles, but many colors printing them.**
The colors of your layers are not only for your CTB, but also for you to be able to distinguish between certain parts of your drawing. It is very reasonable to have 3-4 different colors that print the same, but "stand for" different things, especially when dealing with different linetypes.

**Consider reserving the colors 1–10 for black lines.**  
The colors 1-10 are "primary" colors that are the most commonly used. While different conventions do exist, these are usually the go-to colors, and they often represent 90% of your drawings.

**Use the colors 250 to 255 for grayscale, in reverse order.**

**The brighter the color, the thicker the line it should produce.**

**Don't go near the color 5.**






(avoid using pure blue for layers)

(pure and bright colors are thicker by nature)

(rely less on colors and more on lineweights)

(use specific color layers for simple colored drawings)