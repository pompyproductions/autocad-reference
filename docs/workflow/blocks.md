# Blocks

(Difference between "Block definition" and "Block instance")

Before we dive into specifics of how to use blocks effectively, we need to make a clear distinction between a **block definition** and a **block instance**. 
In simple terms, a **block definition** is like a blueprint, and **block instances** are the individual copies that you insert to your drawing.

Why is this important? Once we start looking into specifics (such as the `BYBLOCK` style), we need to be able to distinguish the contents of the block _definition_ and the resulting block _instance_. 

For example, if you draw a line inside your block _definition_ with the color set to `BYBLOCK`, and insert a block _instance_ whose color is `BLUE`, the line that you drew will be displayed `BLUE`.

## Managing layers and style

### Layer "0"

First and foremost, a friendly reminder: _you should generally stay off the default layers created by AutoCAD._ (Rule of thumb to avoid unexpected behavior)

One such layer is the layer "0".

<figure markdown="span">
  ![Defining a block](../img/BLOCK-01.gif)
  <figcaption>Defining a block.</figcaption>
</figure>

<figure markdown="span">
  ![Layer 0](../img/BLOCK-02.gif)
  <figcaption>Using the layer 0.</figcaption>
</figure>



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