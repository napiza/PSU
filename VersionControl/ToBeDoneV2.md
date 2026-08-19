* Stack up
* Packaging bigger
* Think on material of manufacturing
* Connectors standard
* Think on measurement sent to PSU-Monitoring
* Current of LDO calculate
* Re-do layout
* Add schematic+layout rules depending on JLCPCB capabilities. 
* Was IMPOSIBLE to solder the control part= This I need to improve
* Start with cleaning schematics+Rules+ Component selection--> After layout 
* Everything in miles 
* Diseñar las dos PCB (por lo menos esquematico tambien de monitoring), para pensar y diseñar pensando en el otro 
* Clean library= Can I create in Git a Kicad library? To clean it. 
* High voltage clearance and creapage!!! Gnd clearance also consider 
* Run your schematic’s ERC 
* IMPORTANT TO BE CHECKED : Primary of the transformer in my first version of the PCB, did I manually needed to solder both primaries? 
* Tengo que intentar usar los mismos componentes para no volver a comprar lo que ya tengo: Sobre todo lo caro: Trafos... 





DONE
* Library loaded in C:\Users\napinill\cernbox\WINDOWS\Desktop\PCB_DESIGN\KicadLib   
    * With CernLib I have the Schematic library (.kicad_sym), and the footprints for the pcb (kicad_mod /.pretty). CERN does not provide 3D models. 
    * (This is computer specific, need to do it in my personal computer) still 
    * I could also do this with Kicad databases. But for now I did just copy paste. (I think they are not meant for that -In the CERN repo it says like that)
        * Now I have set it up setting up dbl library, following:  https://engineering-software.docs.cern.ch/eda/sw/kicad/
        * I can also extract datasheet and 3D models from Altium- To be checked (For now not because I depend on Cernbox? And I want to be independant. I can add them myself for the moment )
* Rules: https://jlcpcb.com/blog/pcb-design-rules-best-practices
* For connectors IEC, I need to look at:  https://www.ni.com/en/shop/isolation-and-safety-standards-for-electronic-instruments.html
    * IEC 60664-1 is an international standard for insulation coordination in low-voltage electrical systems (up to 1,000 V AC or 1,500 V DC): https://electricaltrader.com/blogs/news/iec-60664-1-explained-insulation-standards?srsltid=AfmBOopFXsIEfxyb8wJP597Rjpa-bIKdlHjMa1NXTL3iGU3a2NP2kdQ_