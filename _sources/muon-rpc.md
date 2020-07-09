# Resistive Plate Chamber

## Geometry

There are 4 RPC stations in the endcaps, namely RE1, RE2, RE3, and RE4. In Phase 0 and Phase 1, there are 2 rings in each station. In Phase 2, iRPC (*improved* RPC) will be installed in stations 3 & 4, and they are labeled as RE3/1 & RE4/1. The traditional RPC chambers are 10° wide, while the iRPC chambers are 20° wide. The following table shows the ϕ coverage for different chamber types. In total, there will be 648 RPC chambers in the endcaps (324 per endcap).

|Chamber type|Coverage|Num. of chambers|
|------------|--------|----------------|
|RE1/2       |10 deg  |72              |
|RE1/3       |10 deg  |72              |
|RE2/2       |10 deg  |72              |
|RE2/3       |10 deg  |72              |
|RE3/1       |20 deg  |36              |
|RE3/2       |10 deg  |72              |
|RE3/3       |10 deg  |72              |
|RE4/1       |20 deg  |36              |
|RE4/2       |10 deg  |72              |
|RE4/3       |10 deg  |72              |
|            |        |648 (total)     |

In addition, there are 4 RPC stations in the barrel, namely RB1, RB2, RB3, and RB4. RB1 & RB2 have two layers, while RB3 & RB4 have only one layer. The chambers in RB3 & RB4 are divided into two along ϕ. All the chambers are divided into 5 wheels along the z-axis. The following table shows the ϕ coverage for the barrel RPC chamber types. In total, there are 480 RPC chambers in the barrel.

|Chamber type|Coverage|Num. of chambers|
|------------|--------|----------------|
|RB1in       |30 deg  |60              |
|RB1out      |30 deg  |60              |
|RB2in       |30 deg  |60              |
|RB2out      |30 deg  |60              |
|RB3         |15 deg  |120             |
|RB4         |15 deg  |120             |
|            |        |480 (total)     |

For L1 trigger, certain chambers are shared between two trigger sectors to ensure coverage at the sector boundaries. In stations 1 & 2, there are 12 native chambers and 2 neighbor chambers in each station. In stations 3 & 4, there are 15 native chambers and 3 neighbor chambers. Therefore, each trigger sector consists of 64 chambers (54 without neighbor sharing), as shown in the following table.

Note that in Phase 1, EMTF receives the RPC input via CPPF. RE1/3 and RE2/3 are not included. Therefore, each trigger sector consists of 42 chambers (36 without neighbor sharing) in Phase 1.

<!--What to do with barrel RPC?-->

|Chamber type|Coverage|Num. of chambers<br/>(native only)|Num. of chambers<br/>(incl. neighbor)|
|------------|--------|----------------|----------------|
|RE1/2       |10 deg  |6               |7               |
|RE1/3       |10 deg  |6               |7               |
|RE2/2       |10 deg  |6               |7               |
|RE2/3       |10 deg  |6               |7               |
|RE3/1       |20 deg  |3               |4               |
|RE3/2       |10 deg  |6               |7               |
|RE3/3       |10 deg  |6               |7               |
|RE4/1       |20 deg  |3               |4               |
|RE4/2       |10 deg  |6               |7               |
|RE4/3       |10 deg  |6               |7               |
|            |        |54 (total)      |64 (total)      |


## Chamber

Each chamber sends up to 2 RPC clusters.


## Data word

Each cluster is encoded into ?? bits.

