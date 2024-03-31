# Useful LISPs (custom commands)

LISPs are, in short, custom-made commands that can extend the functionality of AutoCAD.

They are often created by other AutoCAD users, using a programming language called AutoLISP (itself based on the LISP language), and can be found all over the internet. While generally safe, they are pieces of third-party code, so err on the side of caution if you find them on questionable websites...

## PLDiet

This is one of my go-to routines. As the name suggests, it is a much needed program to put polylines on a "diet", reducing their vertices.

Very useful when you have splines in your drawing that you'd rather turn into polylines:  
1. Convert to polyline with `PEDIT`  
2. Use `PLD` (PLDiet) to reduce its vertices

## Flatten

This one is for the LT users who, for the longest time, were deprived of the powerful `FLATTEN` command that comes with regular AutoCAD.

I'm grateful that AutoCAD finally decided to make LISPs available in AutoCAD LT, thereby making use of `FLATTEN` in form of a LISP possible. But I'm still quite upset that LT was designed in such a way that it'd be utterly powerless when it comes to the Z axis. They could have included `FLATTEN` in the first place, projected all new objects to `Z=0`, calculated projected intersections between objects with different altitudes, allowed switching to side views for a 2.5D experience, and so on.

_(Side note: it is still possible to switch to side views with some black magic, but that's outside the scope of this guide...)_

It doesn't seem to play well with certain types of objects (rays, construction lines, blocks...), so I tend to use it in a "localized" approach, where I select a smaller set of shapes that do not seem to intersect correctly.


## Other LISPs I'll be testing

`https://www.lee-mac.com/3pointrectangle.html`  
`https://www.lee-mac.com/polylineprograms.html`