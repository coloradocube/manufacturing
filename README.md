# manufacturing
All things manufacturing (PCB, frame, mechanical systems, etc.). Split when appropriate.

## BOM

### Matching BOM column names

| JLC | KiCAD 6 | EPS | CDH | Bat pack | Sensors
| --- | --- | --- | --- | --- | --- 
| Comment | Designation | _Combination/selection/sum of_ Value, Cmp name, and Description
| Designator | Designator | Ref |
| Footprint | Package | Footprint | 
| JLCPCB Part No | Supplier and ref | 
| | Quantity | Qnty |

## TODO
1. JLCPCB [instructions](https://support.jlcpcb.com/article/84-how-to-generate-the-bom-and-centroid-file-from-kicad) for generating BOM and POS (aka CPL) are outdated for KiCAD 6.
2. Sample files for JCLPCB:
   1. [BOM](jlcpcb/Sample-BOM_JLCSMT.xlsx).
   2. [POS](jlcpcb/Sample-CPL_JLCSMT.xlsx).
