# Layers

Every object in AutoCAD sits in a layer, in one way or another. How you organize and use these layers have, arguably, the biggest impact on your work.



## Make it concise and extensible

## Thematic vs. Graphic layers

## Non-printing layers

(Construction lines, viewports, hatch boundaries)

## Freezing vs. Turning off a layer

## Special layers

There are two specific layers in AutoCAD that behave differently than others, and that you should pay attention to: **Defpoints** and **0.**

Long story short, avoid drawing on the layer 0 unless you're inside a block, and don't _ever_ draw on Defpoints. More about these two layers below.


### The layer "0"

Without exception, every AutoCAD file has a layer named "0". For the uninitiated, this might seem like an invitation to go ahead and draw on it.

However, before you understand what it does, don't do it. Even if it's just temporary. Create your own layer instead.

The most important thing to know about 0 is that it's very commonly used inside block definitions. If, inside a block, there's an object on the layer "0", that object will appear **on the same layer as whatever layer you put the block on.**

_(If that last sentence confused you, you should go check out [the article about blocks.](blocks.md))_  
_(Fun fact: the layer 0 works with [xrefs](xrefs.md) too.)_

Because it's such a special layer, doing things like freezing or hiding it may affect unrelated things. It is a real pain when you try to freeze layers to make sense of a drawing, only to find out that there are random things disappearing from the screen.


### Defpoints

Defpoints is a layer that pops up when you create dimension lines. Like the layer 0, it is a "system layer" that behaves differently than others. There are a lot of tutorials out there that teach either of these two "hacks":

- "If you want to draw non-printing objects, draw on Defpoints, it is a special layer that doesn't print."  
- "Freezing the layer 0 will make the objects on Defpoints unselectable."

**Don't heed such advice.** You can make non-printing layers with a single click, and categorize them so that you have control over them. And you don't need a functionality that forces you to freeze such an important layer.

### Special characters

Don't even try to use special characters in layer names; AutoCAD will normally stop you from doing so, but it can still behave in unexpected ways and you can end up with nasty bugs. Some of these special characters are called "wildcards", and behave in different ways.

_(For programmers: some are used as RegEx patterns, and "." stands for "current path".)_