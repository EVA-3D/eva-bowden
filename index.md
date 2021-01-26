---
badges:
    - Official
---
# Bowden

![preview](assets/Bowden.__ALL__.png)

As I don't expect this one to be used much on CoreXY machines it will come handy for some V-casts or cantilever printers. EVA 2 / Bowden is built with the base parts of EVA that are later on "remixed" to achieve different drive types.

??? info "PC4-M6"

    Mosquito, Dragon and V6 (clones) that do not have the PTFE grabbing collar do need a PC4-M6 "pneumatic fitting" on the hot end side to grab the bowden tube. The parts do not have threads but the hole size allows for self-tapping.

    ![](assets/PC4-M6.png)

    Make sure to get the connector that allows the bowden to go through it:

    ![](assets/PC4-M6_through.png)

??? notice "MGN15"

    To mount EVA / Bowden on a MGN15C carriage you will need a few different than the default parts and a few longer screws. The BOM replaces **only a few parts and screws** from the default BOM - for MGN15C you need to look at both - **what follows is not the full MGN15C BOM**.

{{ bom("drives/bowden/bom/BOM_Bowden.MGN15.csv", 4) }}


### Links

{{ eva_download_button("bowden") }}

{{ eva_link("bowden") }}

{{ onshape_link("bowden") }}

### BOM

=== "E3D V6"

{{ bom("drives/bowden/bom/BOM_[Assembly]_V6.csv", 4) }}

=== "Mosquito"

{{ bom("drives/bowden/bom/BOM_[Assembly]_mosquito.csv", 4) }}

=== "Dragon"

{{ bom("drives/bowden/bom/BOM_[Assembly]_dragon.csv", 4) }}
