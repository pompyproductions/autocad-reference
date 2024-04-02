# Commands

## ADDSELECTED

(my favorite command)  
(making the same type of object with the same properties: linetype scale, color, layer...)  
(very powerful when making hatches)  
(unfortunately the commands don't work the same, e.g. window selection in hatches)

![Add selected](../img/ADDSELECTED-01.gif)

## WBLOCK

(save blocks to disk: good for models you can reuse in the future)  
(powerful synergy with ddinsert for overwriting blocks)

## DDINSERT

(useful for overwriting blocks: just copying does not redefine the block)

## FIELD

(associate areas)

## UCS

(hit twice to go to world)  
(ucs > p to go to previous ucs)  
(ucs > save shortcut and similar stuff)  

## XATTACH

## PURGE

(-purge > r > > n)

## LAYER

(what you really want is the -layer variant)
(`*` for ALL layers)  
(``)  
(``)  
(`*|*` for ALL xref layers)  
(`*|*<name>*` all xref layers with `<name>` in it)  
(`*|*<name>` all xref layers that end with `<name>`)  
(`~*|*` for ALL non-xref layers)  
(EXAMPLE: `X@#*`, XP0, XP1, XCL, XCT)  

## LTSCALE

## CELTSCALE

## BEDIT

## REFEDIT

(quickly add objects to an existing block)  
(don't use them on dynamic blocks)  

## PUBLISH

## QSELECT

(select objects in given type, useful when cleaning for exports)

## FILTER

(save and load filters, useful for draw order and selecting hatch/polylines)

## VIEWPORTS

(in model space, work with different viewports)  
(one interesting method is to keep one very thin window to the side with the chartre des calques/blocks/annotations for addselected/copy/layer commands)

## PEDIT

(make arrows!)  
(close polylines)  
(convert splines into polylines)  
(straighten polylines without breaking hatch association)  
(linetype generation)

## STRETCH

(use in combination with )

## COPY

(array copy: prefer it over actual array)

## ARRAY

(avoid as much as possible)

## LINE

## PLINE

(make arrows)

## MIRROR

## OFFSET

(multiple offset!)  
("par")

## JOIN

(will break if lines aren't perfect)  
(joining many lines at once isn't the same with joining segments to polylines)

## FILLET

(useful for joining lines when the join command breaks)

## LAYMCH

(hit enter twice quickly to bring to current layer)

## (copy to layer)

(useful and overlooked command)  
(little gimmick: asks displacement at the end, just hit enter twice)

## (isolate layer)

(option to fade or to hide entirely)

## (set current layer)

## (matchprop)

## GROUP

(change pickstyle to temporarily modify groups)

## DIST

(prefer this over cotes)

## TEXT

## MTEXT

(can be exploded to make simple texts)

## RECTANGLE

(use tab)

## PASTEORIG

(often used in combination with world ucs to transfer objects between files)

## COPYBASE

(useful for copying things between drawings/layouts with a common point of reference. Especially when the 0 point doesn't match between files)

## ATTSYNC

(sigh... just autocad things)

## EXTEND

(try the different methods: fence, polygons)  
(hit enter twice to pick all objects, but don't do this with heavy drawings)

## TRIM

(try the different methods: fence, polygons)  
(hit enter twice to pick all objects, but don't do this with heavy drawings)

## EXPLODE

(use on text)

## XLINE

(avoid on non-flat drawings, can't be flattened and mess up the whole thing)

## DRAWORDER

(right click usually does the trick, but could be faster to use this command if you reach for it often)