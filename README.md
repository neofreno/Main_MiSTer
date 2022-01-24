
It forces twice the horizontal frequency to be able to view the Mister cores at native resolution on a CRT monitor > 100hz.

![Image text](https://user-images.githubusercontent.com/35410501/150386302-2a2bd068-da60-48a0-89a1-4b70b9a3d9cc.jpg)

Two options are added in the MiSTer.ini settings: 

<ul>
    <li>forced_dvrate_crt</li>
        <ol type="1">
            <li>only double v.rate</li>
            <li>set v.rate to 30khz if double v.rate < 29khz</li>
            <li><strong>double width to show menu if width < 282 and v.rate < 29khz</strong></li>
            <li>double width to show menu if width < 282 and v.rate < 28.5khz</li>
        </ol>
    <li>forced_dvrate_cfg</li>
        <ol type="1">
            <li><strong>set to 1 ro force settings (Aspect Ratio= full screen, scandoubler FX=None)</strong></li>
        </ol>
</ul>

For better compatibility use forced_dvrate_crt=3 and forced_dvrate_cfg=1.