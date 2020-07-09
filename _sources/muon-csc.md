# Cathode Strip Chamber

## Geometry

There are 4 CSC stations in the endcaps, labeled as ME1, ME2, ME3, and ME4. In station 1, there are 3 rings: ME1/1, ME1/2, and ME1/3, while there are only 2 rings in the other stations. In station 1, the CSC chambers are 10° wide, while in the other stations, the chambers are 20° wide in ring 1, and 10° wide in ring 2. The following table shows the ϕ coverage for different chamber types.
In total, there are 540 CSC chambers (270 per endcap).

|Chamber type|Coverage|Num. of chambers|
|------------|--------|----------------|
|ME1/1       |10 deg  |72              |
|ME1/2       |10 deg  |72              |
|ME1/3       |10 deg  |72              |
|ME2/1       |20 deg  |36              |
|ME2/2       |10 deg  |72              |
|ME3/1       |20 deg  |36              |
|ME3/2       |10 deg  |72              |
|ME4/1       |20 deg  |36              |
|ME4/2       |10 deg  |72              |
|            |        |540 (total)     |

For L1 trigger, certain chambers are shared between two trigger sectors to ensure coverage at the sector boundaries. In station 1, there are 18 native chambers and 3 neighbor chambers. In the other stations, there are 9 native chambers and 2 neighbor chambers in each station. Therefore, each trigger sector consists of 54 chambers (45 without neighbor sharing), as shown in the following table.

Note that each ME1/1 chamber is split into ME1/1a and ME1/1b at η ~ 2.05, and ME1/1a is sometimes referred to as ring 4. But for L1 trigger, we still consider it as a single chamber. Also note that, to compensate for the drift of the electrons in the strong magnetic field, the ME1/1 wires are tilted by 29°.

|Chamber type|Coverage|Num. of chambers<br/>(native only)|Num. of chambers<br/>(incl. neighbor)|
|------------|--------|----------------|----------------|
|ME1/1       |10 deg  |6               |7               |
|ME1/2       |10 deg  |6               |7               |
|ME1/3       |10 deg  |6               |7               |
|ME2/1       |20 deg  |3               |4               |
|ME2/2       |10 deg  |6               |7               |
|ME3/1       |20 deg  |3               |4               |
|ME3/2       |10 deg  |6               |7               |
|ME4/1       |20 deg  |3               |4               |
|ME4/2       |10 deg  |6               |7               |
|            |        |45 (total)      |54 (total)      |


## Chamber

Each chamber sends up to 2 LCTs (or segments). The local coordinates are in unit of halfstrip for ϕ, and in unit of wiregroup for θ. Different chambers have different numbers of strips and wires. The following table lists the numbers of strips (and halfstrips) and numbers of wiregroups.

Using ME2 as reference, the ϕ resolution is 0.0625° (1.1 mrad) for 10° chamber, and 0.1250° (2.2 mrad) for 20° chamber.

|Chamber type|Num. of strips|Num. of halfstrips|Num of wiregroups|
|------------|--------------|------------------|-----------------|
|ME1/1a      |48            |96                |48               |
|ME1/1b      |64            |128               |48               |
|ME1/2       |80            |160               |64               |
|ME1/3       |64            |128               |32               |
|ME2/1       |80            |160               |112              |
|ME2/2       |80            |160               |64               |
|ME3/1       |80            |160               |96               |
|ME3/2       |80            |160               |64               |
|ME4/1       |80            |160               |96               |
|ME4/2       |80            |160               |64               |


## Data word

Each LCT is encoded into a 32-bit word.


