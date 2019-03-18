Altium does not define any meaning to mechanical layers. Circuit Studio does define some layer meanings by default which are included below. "Used By" is either Footprint, PCB, or both indicating at which stage the layer is used. Layers with Top and Bot in their names need to be set up as layer pairs. The skeleton PcbDoc and PcbLib TODO will include these layer names and pairings by default.

| Mechanical Layer | Name                | Usage                                                 | Used By         | Notes               |
| ---------------- | ------------------- | ----------------------------------------------------- | --------------- | ------------------- |
| 1                | Outline             | Defines Board Outline                                 | PCB             |                     |
| 2                | Fab Notes           | Dimensions, Notes, Etc. for Fab (included in gerbers) | PCB             |                     |
| 3                | Internal Notes      | Notes for internal use                                | PCB / Footprint |                     |
| 4                | Undefined           |                                                       |                 |                     |
| 5                | Undefined           |                                                       |                 |                     |
| 6                | Assy Text Top       | REFDES strings                                        | Footprint       | For Assy Dwg Output |
| 7                | Assy Text Bot       | REFDES strings                                        | Footprint       | For Assy Dwg Output |
| 8                | Assy Top            | Comp Outline and Pin 1 Des                            | Footprint       | For Assy Dwg Output |
| 9                | Assy Bot            | Comp Outline and Pin 1 Des                            | Footprint       | For Assy Dwg Output |
| 10               | Undefined           |                                                       |                 |                     |
| 11               | Comp Dimensions Top | Component Dimensions                                  | Footprint       |                     |
| 12               | Comp Dimensions Bot | Component Dimensions                                  | Footprint       |                     |
| 13               | Comp Body Top       | 3D model and mech outlines of components              | Footprint       |                     |
| 14               | Comp Body Bot       | 3D model and mech outlines of components              | Footprint       |                     |
| 15               | Courtyard Top       | Courtyard visual indicator and origin crosshair       | Footprint       |                     |
| 16               | Courtyard Bot       | Courtyard visual indicator and origin crosshair       | Footprint       |                     |
| 17               | Undefined           |                                                       |                 |                     |
| 18               | Undefined           |                                                       |                 |                     |
| 19               | Undefined           |                                                       |                 |                     |
| 20               | Undefined           |                                                       |                 |                     |
| 21               | Undefined           |                                                       |                 |                     |
| 22               | Undefined           |                                                       |                 |                     |
| 23               | Undefined           |                                                       |                 |                     |
| 24               | Undefined           |                                                       |                 |                     |
| 25               | Undefined           |                                                       |                 |                     |
| 26               | Undefined           |                                                       |                 |                     |
| 27               | Undefined           |                                                       |                 |                     |
| 28               | Undefined           |                                                       |                 |                     |
| 29               | Undefined           |                                                       |                 |                     |
| 30               | Undefined           |                                                       |                 |                     |
| 31               | Undefined           |                                                       |                 |                     |
| 32               | Undefined           |                                                       |                 |                     |
