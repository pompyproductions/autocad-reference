# Blocks

(Difference between "Block definition" and "Block instance")

## Managing layers and style

### Layer "0"

First and foremost, a friendly reminder: _you should generally stay off the default layers created by AutoCAD._ (Rule of thumb to avoid unexpected behavior)

One such layer is the layer "0".

### BYLAYER and BYBLOCK

While "BYLAYER" is the way to go with your usual drawings, if you want the objects inside your block definition to match the style of your block instance

## Attributes

attdef, attsync


## Dynamic blocks



## Shortcomings

Blocks are great for a lot of things, but like everything else, they should be used in moderation.

### Nesting 

Try to avoid nesting too many blocks.

### Dynamic blocks & EDITREF

The EDITREF command does not work for dynamic blocks, so avoid using dynamic blocks when a normal block will suffice.