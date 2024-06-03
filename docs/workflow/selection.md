# Selecting Objects

When dealing with busy files, it can be a pain to even just pick the right objects to work with. A lot of files have many overlapping objects that get in the way.

## Selection methods

Lasso, Cpolygon, Spolygon, "fence"...

## Do you _need_ to select them?

This may sound like I'm stating the obvious, but a lot of operations in AutoCAD don't require you to select objects in a precise manner.

(this )


## Clean up your drawing

If you're having trouble with a lot of objects overlapping, 



Place hatches and their boundaries on separate layers, and freeze them.

Use "drafting" layers that you can get rid of.

Place blocks and XREFs on separate layers.

Name your XREFs so that you can control their layers in batch (e.g. `X2|*`).

Once you do the above, your drawing will breathe and you probably won't have to deal with too many overlapping objects anyway.

## Quick Select

`QSEL` command.

## Filter

`FILTER` command.

## Don't use "selection cycling"

`CTRL + W` toggles this option.