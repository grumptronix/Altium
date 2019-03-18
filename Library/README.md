# Overview

This repo is my attempt to stop reinventing the wheel when it comes to libraries in Altium. There are other similar efforts (notably Celestial Library by @issus) but this way I get to control things the way I like. Eventually if others like my preferences maybe it will be more than a one man operation. As a rule, I am going to try to enter entire series instead of one off parts. Not sure how best to do this yet, but better to add all values so you don't have to keep adding rows in a database later on. For MPNs I will stick to vendor series I'm used to at first e.g. Murata GRM for generic ceramic caps. Yageo RC for generic resistors.

# Layer Assignments

Altium has layers reserved for some information (for example, silkscreen and soldermask) but generic "mechanical" layers for others. It is up to the end user to define what meaning the layers convey. This library will be maintained such that it uses the layer definitions described in [mech_layers.md](./mech_layers.md)

TODO: Eventually I will also setup a skeleton project with these layers already prenamed.

# SchLib  
- This folder contains all .SchLib files  
- See its README for more info

# PcbLib
- This folder contains all .PcbLib files
- See its README for more info

# Database Properties

All components are guaranteed to have the following properties set and match the formatting used in Digikey:
-IPN (Internal Part Number, for now just something generic like CAP-00001), this is the key for the table
-Description
-Manufactuer
-Manufacturer Part Number
-Library Ref (the name in the corresponding SchLib file)
-Library Path (relative path to the SchLib file)
-Footprint Ref (name of the nominal footprint)
-Footprint Path (relative path to the PcbLib file)
-Value (either a real value or the most descriptive string, possibly also the MPN)

Note: additional footprints can be used ("most" and "least" as described in the IPC docs. these are additional columns with suffixes of 2, 3, etc.)
Additional work will go into adding supplier information and how to choose packaging (cut tape, reel, etc.) later on. For now it's assumed you'll spit out a BOM and import to your favorite distributors tool.





