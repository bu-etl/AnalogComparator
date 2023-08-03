# AnalogComparator
<p align="center">
  <img src="https://github.com/bu-etl/AnalogComparator/blob/main/Docs4README/image.png" />
</p>

## Description
* Signal Path:
SMA connentor accepts an input signal &rarr; Goes through an analog comparator with a 0.25V threshold &rarr; Goes through a level shifter to convert it to 1V8 CMOS &rarr; singal output through SMA
* Power Path:
Accepts 4V-10V through power barrel input &rarr; 3.3V LDO voltage regulator &rarr; Powers comparator and LED &rarr; 3.3V gooes into 1.8V LDO voltage regulator &rarr; Powers level shifter

## File Paths
* Altium Project files: AnalogComparator 
* Circuit Schematic PDF: AnalogComparator &rarr; Project Outputs for AnalogComparator &rarr; Schematic Print 
* BOM: AnalogComparator &rarr; Project Outputs for AnalogComparator &rarr; BOM
