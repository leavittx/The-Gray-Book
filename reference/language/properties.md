Properties are where datatype patches store data. A datatype patch can have any number of properties and you can see them listed in the PatchExplorer.

*Image:Properties listed in the PatchExplorer*

Properties can be added and removed via the explorer or simply by adding a Pad via the Nodebrowser. Pads are used in a patch to read from or write to a property. Properties and their pads are matched by name, so make sure to always be specific about naming, including casing. Rename a Pad by doubleclicking its label and pressing <span class="keyseq"><kbd>Enter</kbd></span> when finished.

Any number of different operations can write to the same pad but each operation can only write to a pad once. A little triangle above a pad is a hint that there is a pad with the same name in the patch that is also written to.

*Image:Different operations writing to the same pad*

You can use anonymous (unnamed) pads as a hub to join many links into one.

*Image:Anonymous pad use as a hub for multiple links*

In an operation you can assume that first always all pads are read from and only as the last step all pads are written to.

## The datatype of a property
By default a property does not have a datatype assigned and  therefore is generic. You see this because a pad at first is only an outlined circle. If the circle is filled, it means that the compiler has inferred a type for it which you can see in the tooltip by hovering it.

*Image:Generic pad vs. pad with a datatype inferred*

If you manually need to specify a type for a property you can annotate its pad by middleclicking and entering any type in the editor that pops up. As an alternative to the middleclick you can rightclick the pads label and choose -> Configure.

*Image:Annotating a pad*

You can recognize pads that are annotated manually as they have a black dot in their circle.

*Image:Annotated pad*
