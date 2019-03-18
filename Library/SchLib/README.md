# SchLib  
- This folder contains all .SchLib files  
- SchLib files contain only the schematic symbol information. Graphics, pin numbers and names, default designators, etc. They do not contain any parametric data, instead, that is stored in a database.
- Each .SchLib should contain only one component. (or a family of components, e.g. resistor US vs EU)
- SchLib files should have the format <ComponentType>.SchLib if it is possible to use the same schematic symbol for more than one MPN (Manufacturer Part Number). (e.g. most jellybean parts).
- SchLib files should have the format <MPN>.SchLib if it is not possible to use the same schematic symbol for more than one MPN. (e.g. very special purpose ICs)
- The default designator should be set to follow [ANSI Y32.16](https://en.wikipedia.org/wiki/Reference_designator).
- Default Comment should be set to "=Value".
- Value should be set to TBD if a passive, or an MPN if not.
- Description should be set to a verbose version of the filename, or the MPN depending on which is appropriate.
- Type should be set to whatever is appropriate for the part, usually Standard.
- Symbol Reference gets entered as "Library Ref" in the database.
- All symbols stick with DXP defaults which is grid size 10 = 10 mil. No pins should fall outside the 10mil grid.
- All two pin parts should have 40 mil between, 3 pin parts like pots and transistors should also have 40 mil between pairs
- Pin number follows IPC-7351 standards (This means pin one on diodes is the cathode!) https://devras.com/vhs/2013-07-03_smt_class/IPC_7351BNamingConvention.pdf
- TODO insert image of Library Component Properties dialog.

