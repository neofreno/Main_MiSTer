
It forces twice the horizontal frequency to be able to view the Mister cores at native resolution on a CRT monitor > 100hz.

Two options are added in the MiSTer.ini settings: 

forced_dvrate_crt=3  
 ; 1 - only double v.rate
 ; 2 - set v.rate to 30khz if double v.rate < 29khz
 ; 3 - double width to show menu if width < 282 and v.rate < 29khz
 ; 4 - double width to show menu if width < 282 and v.rate < 28.5khz

forced_dvrate_cfg=1   
 ; set to 1 ro force settings (Aspect Ratio= full screen, scandoubler FX=None)

For better compatibility use forced_dvrate_crt=3 and forced_dvrate_cfg=1.