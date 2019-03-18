# PcbLib
- This folder contains all .PcbLib files
- PcbLib files are organized by category
- PcbLib files contain footprint information, which should conform to the layer assignments in [mech_layers.md]( ../mech_layers.md).
- Solder mask expansion is set to zero in all parts. Fab notes should allow fab house to expand as necessary, or this should be handled through rules 
- All footprints should adhere to the IPC-7351 zero orienttion standard https://devras.com/vhs/2013-07-03_smt_class/IPC_7351BNamingConvention.pdf
- Where possible, use the Altium IPC Compliant Footprint Wizard to generate footprints and 3d models, stick with the defaults
- Prefix IPC names with common names, e.g. 0805_CAPC2012X13N, accept the default description
- Change soldermask expansion to zero
- Add overlay to match courtyard, 0.127mm minimum, default to 0.2mm
- If high density footprint, omit the silkscreen outline entirely
- Leave altium generated step files as embedded
- More TBD

#Capacitors

- 0805 cap footprints created from these dimensions https://search.murata.co.jp/Ceramy/image/img/A01X/G101/ENG/GRM21BR72A103KA01-01.pdf
