# Bear X axis and Extruder

## Print Settings

### :warning: Warning

1. The parts have been designed and tested with the parameters bellow and it is important to follow them to avoid issues like part cracking, bad bridging, not enough stiffness or wrong tolerances.
1. Be sure to have a well calibrated machine and extruder. Check our guide here for [calibrating extrusion multiplier](https://guides.bear-lab.com/Guide/Extrusion+multiplier+and+filament+diameter/8?lang=en)


### Parameters

* Slicer: PrusaSlicer
* Infill type : Gyroid recommended
* Support : No
* Brim : No
* Detect thin walls : No

| Part | Quantity | Layer Height | Infill | Perimeters | Top/Bottom Layers | Filament type | Color |
|:----|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
| cable_guide_back_a     | 1 | 0.20mm | 20% | 4 | 5 | PETG | |
| cable_guide_back_b     | 1 | 0.20mm | 20% | 4 | 5 | PETG | |
| extruder_body          | 1 | 0.20mm | 20% | 4 | 5 | PETG | Black |
| extruder_cover         | 1 | 0.20mm | 20% | 4 | 5 | PETG | |
| extruder_idler         | 1 | 0.20mm | 20% | 4 | 5 | PETG | |
| filament_sensor_cover  | 1 | 0.20mm | 20% | 4 | 5 | PETG | Black |
| filament_sensor_lever  | 1 | 0.20mm | 20% | 4 | 5 | PETG | Black |
| hotend_collet_clip     | 1 | 0.20mm | 20% | 3 | 5 | PETG | |
| nozzle_fan_duct        | 1 | 0.20mm | 20% | 3 | 5 | Read note<sup>1</sup> bellow | |
| ptfe_cutter_50mm_60deg | 1 | 0.20mm | 20% | 3-4 | 5 | PETG | |
| x_carriage             | 1 | 0.20mm | 20% | 4 | 5 | PETG | |
| x_carriage_back        | 1 | 0.20mm | 20% | 3 | 5 | PETG | |
| x_end_idler            | 1 | 0.20mm | 20% | 4 | 5 | PETG | |
| x_end_idler_tensioner  | 1 | 0.20mm | 20% | 4 | 5 | PETG | |
| x_end_motor            | 1 | 0.20mm | 20% | 4 | 5 | PETG | |


> Note<sup>1</sup>: The nozzle_fan_duct needs to be printed with a heat resistant filament like ABS, Extrudr GreenTec Pro, annealed HTPLA, PC and probably much more. Don't forget to compensate for shrinkage accordingly to the filament type you are using.
