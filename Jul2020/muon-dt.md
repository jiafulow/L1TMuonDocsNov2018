# Drift Tube

## Geometry

There are 4 DT stations in the barrel, namely MB1, MB2, MB3, and MB4. The DT system is divided into 5 wheels along the z-axis. Each wheel is divided into 12 sectors that are approximately 30° wide. There is one chamber per sector, except in the MB4 uppermost & lowermost sectors (sectors 4 & 10), where there are 2 chambers. The following table shows the ϕ coverage for the DT chamber types. In total, there are 250 DT chambers in the barrel.

|Chamber type|Coverage|Num. of chambers|
|------------|--------|----------------|
|MB1         |30 deg  |60              |
|MB2         |30 deg  |60              |
|MB3         |30 deg  |60              |
|MB4         |30 deg  |70              |
|            |        |250 (total)     |

For L1 trigger, certain chambers are shared between two trigger sectors to ensure coverage at the sector boundaries. In all the stations, there are 2 native chambers and 1 neighbor chamber per wheel. Therefore, each trigger sector consists of 12 chambers (8 without neighbor sharing) per wheel, as shown in the following table.

|Chamber type|Coverage|Num. of chambers<br/>(native only)|Num. of chambers<br/>(incl. neighbor)|
|------------|--------|----------------|----------------|
|MB1         |30 deg  |2               |3               |
|MB2         |30 deg  |2               |3               |
|MB3         |30 deg  |2               |3               |
|MB4         |30 deg  |2               |3               |
|            |        |8 (total)       |12 (total)      |


## Chamber

Each chamber sends up to 2 DT segments.

## Data word

Each segment is encoded into ?? bits.
