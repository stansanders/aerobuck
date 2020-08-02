# aerobuck

a free/libre open source aeroponic plant propagation tool designed to utilize a standard 5-gallon bucket to realize an aeroponic cloner which functions well and requires minimal cost or effort.  

## Overview

The aim of this design is to improve on existing plant cloner designs in the following areas:   
 
* Cost: Require a minimal bill of materials  
* Leaks: prevent liquid escape completely, without complicated sealing efforts seen in many bin-based designs.  
* Simplicity: use no tools other than a printer and human hands  

This repository will provide the design files in STEP form to allow the design to be modified to suit the user, as well as STL files to provide a simple route for users to print the design as-is with no need to utilize a computer beyond providing the file to their printer.

## Bill of Materials  

* printed manifold  
* printed lid
* 360 degree 10-32 / M5-0.8 sprayer nozzles (botanicare micro sprayer, xGarden mister, etc) 
* 5 gallon bucket  
* 48mm neoprene cloner collars (commercially available or self made)
* submersible pump with 1/2" female threaded  upwards-facing outlet (ecoplus 396 has been tested, others may work as well)

## Printing recommendations

The manifold and lid designs have been tested using a modified version of the Voron v1.5 coreXY printer design, using Inland brand PLA+.  Most printers should be capable of printing the design adequately so long as their work envelope permits.  Slicer settings are left as an exercise to the user due to the wide variations in printer needs and plastic types.  A high number of perimeter shells, high infill percentage, and high number of top and bottom solid layers are a good idea due to the pressures and liquids involved.  Low quality prints may function for some time but should be observed for leaks in the manifold due to delamination and undesired liquid intrusion into the interior of the printed lid.  The test unit has a layer height of 0.2mm, 4 perimeter shells, 3 bottom solid layers, and 6 top solid layers.    

## Assembly
The manifold is designed as a single part which should thread into the submersible pump's outlet and form a good seal.  The holes in the upper surface of the manifold ring are sized to allow the sprayer nozzles to self-tap slightly.  A firm grip should be all that is needed, however allowing the plastic to warm either by sunlight or source of warm air (e.g. blow dryer) may ease the process.

With the nozzles fitted assembly is completed by threading the manifold into the pump, placing the pump and manifold assembly in the bucket such that the manifold ring is roughly centered, and setting the lid into the bucket with the neoprene collars fitted.

## Use
Cuttings should be of good health and cut with sharp tools shortly before insertion into the system.  The pump should run at all times and the reservoir should be kept full enough to cover the pump inlet with clean water.  A fungal control formula is outlined below and recommended to avoid cutting loss due to rot.  The system may be run indoors or outdoors so long as temperatures remain moderate and sunlight exposure is not excessive - system has been tested outdoors successfully in an area that receives approximately 2 hours of full direct sun and 10 hours of open shade.  Cuttings should require no further care until their root systems are sufficient to transplant to their final growing media.

This system has been tested and successful with cuttings of papayas (*Carica papaya*),  figs (*Ficus carica*), and tomatoes (*Solanum lycopersicum*).  Rooting has happened much more quickly and with less damage than other methods.  Many other species should also work well.

## Fungal Control

While not a part of the hardware design, fungal destruction of plant stems in this type of system is a primary cause of cutting loss so it is important to discuss ways to mitigate that issue.  Commercial solutions exist to address the problems one is likely to encounter however their cost is high compared to the formula below.

*Please exercise the appropriate precautions when handling potentially harmful materials.  Use appropriate safety equipment, follow appropriate safety procedures, observe all precautions specified by the relevant materials safety and data sheets.* 

Calcium hypochlorite is marketed for use in swimming pools and can be purchased cheaply.  "HTH 52023 Super Shock Treatment Swimming Pool Chlorine Cleaner" has been tested to work well and is readily available.  Other options should work well so long as they are of comparable composition.

Using calcium hypochlorite 56.44% in granular form, a stock solution is made by adding 0.26 grams of granules to 1 liter of plain water.  This stock solution is added to the cloner at a rate of 1.5 milliliters stock solution per liter of plain water.  For this design, 15 milliters of calcium hypochlorite stock solution and 10 liters of plain tap water should result in the water level being just below the sprayers.
