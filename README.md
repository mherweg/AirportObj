# AirportObj

* updated airport layouts for Flightgear. 
* file format: .btg.gz 
* with correct elevations

The layouts were pulled from http://gateway.x-plane.com/ and converted to btg.gz with genapts850 version 2.1.0.

Source for the elevation data is http://viewfinderpanoramas.org/

Check out the AirportObj.txt file or browse the folder structure here to see if "your" airport is included. 

I will try to include all airports that are marked as "3D" on the gateway (and also included in Project3000)

Depending on the "airport hole" in Scenery 2.0 the new airport layout will fit or not fit into your terrain. You have to try that yourself.

I suggest you make a backup of your old btg.gz file.

## Example:

    cd .fgfs/TerraSync/Terrain/w070n10/w067n10/SVMI.btg.gz
    mv SVMI.btg.gz SVMI.btg.gz.bak
    cp AirportObj/w070n10/w067n10/SVMI.btg.gz .
    
    
If you find a layout with an extremly wrong elevation (usually at sea level) please report to Flightgear forum user "pommesschranke" or create an issue here on github:
 https://github.com/mherweg/AirportObj/issues
 
  
