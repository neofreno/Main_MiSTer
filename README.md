
It forces twice the horizontal frequency to be able to view the Mister cores at native resolution on a CRT monitor > 100hz.

Two options are added in the MiSTer.ini settings: 

<ul>
    <li>forced_dvrate_crt=3</li>
        <ol>
            <li>only double v.rate</li>
            <li>set v.rate to 30khz if double v.rate < 29khz</li>
            <li>double width to show menu if width < 282 and v.rate < 29khz</li>
            <li>double width to show menu if width < 282 and v.rate < 28.5khz</li>
        </ol>
    <li>forced_dvrate_cfg=1</li>
        <ol>
            <li>set to 1 ro force settings (Aspect Ratio= full screen, scandoubler FX=None)</li>
        </ol>
</ul>

For better compatibility use forced_dvrate_crt=3 and forced_dvrate_cfg=1.