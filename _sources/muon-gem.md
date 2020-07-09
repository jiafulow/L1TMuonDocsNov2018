# Gas Electron Multiplier

## Geometry

There are 3 GEM stations in the endcaps, namely GE1/1, GE2/1, and ME0. GE1/1 will be installed during LS2, while GE2/1 and ME0 will be installed during LS3. The GE1/1 chambers are 10° wide, while the GE2/1 and ME0 chambers are 20° wide. The following table shows the ϕ coverage for different chamber types. In total, there will be 144 GEM chambers (72 per endcap).

|Chamber type|Coverage|Num. of chambers|
|------------|--------|----------------|
|GE1/1       |10 deg  |72              |
|GE2/1       |20 deg  |36              |
|ME0         |20 deg  |36              |
|            |        |144 (total)     |

For L1 trigger, certain chambers are shared between two trigger sectors to ensure coverage at the sector boundaries. GE1/1 has 6 native chambers and 1 neighbor chamber, GE2/1 has 3 native chambers and 1 neighbor chamber, and ME0 has 3 native chambers and 1 neighbor chamber. Therefore, each trigger sector consists of 15 chambers (12 without neighbor sharing), as shown in the following table.

|Chamber type|Coverage|Num. of chambers<br/>(native only)|Num. of chambers<br/>(incl. neighbor)|
|------------|--------|----------------|----------------|
|GE1/1       |10 deg  |6               |7               |
|GE2/1       |20 deg  |3               |4               |
|ME0         |20 deg  |3               |4               |
|            |        |12 (total)      |15 (total)      |


## Chamber

For GE1/1, each chamber sends up to 8 GEM clusters per layer. 

## Data word

Each cluster is encoded into ?? bits.
