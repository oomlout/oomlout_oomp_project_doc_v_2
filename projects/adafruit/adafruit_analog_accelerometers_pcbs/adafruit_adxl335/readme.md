# adafruit_analog_accelerometers_pcbs
 
## summary 
* id: adafruit_adafruit_analog_accelerometers_pcbs_adafruit_adxl335
* user: adafruit
* name: adafruit_analog_accelerometers_pcbs
* board: adafruit_adxl335
* repo: https://github.com/adafruit/Adafruit-Analog-Accelerometers-PCBs



* src_file_repo_sch: 
*
 src_file_repo_sch_link: https://github.com/adafruit/Adafruit-Analog-Accelerometers-PCBs/tree/master/
* full details link: https://github.com/oomlout/oomlout_oomp_project_bot_v_2/tree/main/projects/adafruit_adafruit_analog_accelerometers_pcbs_adafruit_adxl335/current_version/working  

## schematic  
![](working_schematic_600.png)  
[schematic (pdf)](working_schematic.pdf)  

## pcb  
![](working_3d_600.png) 
![](working_3d_front_600.png)  
![](working_3d_back_600.png)  
![](working_600.png)  
[board (pdf)](working.pdf)  

## working_bom
| Id | Designator | Footprint | Quantity | Designation | Supplier and ref |  | None | 
| --- | --- | --- | --- | --- | --- | --- | --- | 
| 1 | IC2 | SOT23-5L | 1 | LP298XS |  |  | [''] | 
| 2 | C1,C5 | C0805K | 2 | 10uF |  |  | [''] | 
| 3 | C2,C4,C3 | C0805K | 3 | 0.1uF |  |  | [''] | 
| 4 | U$8,U$5 | MOUNTINGHOLE_2.0_PLATED | 2 | MOUNTINGHOLE2.0 |  |  | [''] | 
| 5 | U$2,U$1 | FIDUCIAL_1MM | 2 | FIDUCIAL |  |  | [''] | 
| 6 | JP2 | 1X07_ROUND_76 | 1 |  |  |  | [''] | 
| 7 | IC1 | 16LCSP | 1 | ADXL33X |  |  | [''] | 
| 8 | U$4 | ADAFRUIT_2.5MM | 1 |  |  |  | [''] | 


## bom_schematic
| Ref | Qnty | Value | Cmp name | Footprint | Description | Vendor | DNP | 
| --- | --- | --- | --- | --- | --- | --- | --- | 
| C1, C5 | 2 | 10uF | C-USC0805K | working:C0805K |  |  |  | 
| C2, C3, C4 | 3 | 0.1uF | C-USC0805K | working:C0805K |  |  |  | 
| IC1 | 1 | ADXL33X | ADXL33X | working:16LCSP |  |  |  | 
| IC2 | 1 | LP298XS | LP298XS | working:SOT23-5L |  |  |  | 
| JP2 | 1 | HEADER-1X7THICKER | HEADER-1X7THICKER | working:1X07_ROUND_76 |  |  |  | 
| U$1, U$2 | 2 | FIDUCIAL | FIDUCIAL | working:FIDUCIAL_1MM |  |  |  | 
| U$5, U$8 | 2 | MOUNTINGHOLE2.0 | MOUNTINGHOLE2.0 | working:MOUNTINGHOLE_2.0_PLATED |  |  |  | 


## mounting_holes
| x | y | package | value | ref | size | 
| --- | --- | --- | --- | --- | --- | 
| 13.969999999999999 | 0.0 | MOUNTINGHOLE_2.0_PLATED | MOUNTINGHOLE2.0 | U$5 | m3 | 
| 0.0 | 0.0 | MOUNTINGHOLE_2.0_PLATED | MOUNTINGHOLE2.0 | U$8 | m3 | 


