#Libraries
A _library_ is made from one sample for a single target _platform_ and
has a specific _design_ associated with it that decides the _selection_
and _strategies_ used to make the library. A library may also have _tag
barcodes_ (primers) and QC information.

1. On the _List Samples_ page, enter your project name into the search box.
1. Check the gDNA samples to turn into libraries.
1. From the _Bulk actions_ drop down, select _Propagate (library) selected_.
1. A table will appear. Enter the library information from the table below.
1. Choose _Save_.

TODO library data tab

Note that for dual-index barcodes, only the first barcode needs to be
specified. The second is optional.

##Design
TODO wax poetic

##Quality control
There are three pieces of quality control information for a library in MISO:

1. The quantitative QC values (library QC)
1. The overall pre-sequencing quality control (QC passed)
1. The post-sequencing quality control (low quality library)

###Library QC
After measuring the insert size or concentration, this information can be
entered. There is no bulk entry for this information, it must be entered per
library at this time.

1. From the _List Libraries_ page, find the 0001 library using the search box and click the link.
1. Beside the _QCs_ heading, select _Options_ → _Add Library QC_.
1. Enter the insert size or concentration and the instrument used to perform the measurement.
1. Click _Add_.

###QC passed
The QC passed is a simple pass/fail for a library to decide if it is good
enough for sequencing.

1. From the _List Libraries_ page, find 0001 library and click the link.
1. Change _QC passed_ from _Unknown_ to _True_.
1. Click _Save_.

###Low Quality Library
Not every library realises its full potential. After sequencing, sometimes
problems are discovered in libraries that need to be sequenced again. The
“low-quality library” indicator causes any pool containing this library to be
flagged, in case it will be sequenced again.

1. From the _List Libraries_ page, find the 0004 library and click the link.
1. Check _Low quality library_.
1. Click _Save_.

In later exercises, this library will be marked as suspect.

## Boxes
Libraries can also be placed in boxes.

1. From the _List Boxes_ page, find the project-specific box created before.
1. Select an unused position and enter a matrix barcode from the table above.
1. Click _Lookup_ and then _Update position_.
1. Repeat for the remaining libraries.