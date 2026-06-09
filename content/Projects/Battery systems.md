In [this video](https://www.youtube.com/watch?v=UUr-CJudg38), we showcased a high-density battery management system (BMS) in a 40x40mm form factor for a 3-cell [tabless 18650](https://www.youtube.com/watch?v=yfsgWKdlQEo) Li-ion battery pack using a [BQ77915](https://www.ti.com/lit/ds/symlink/bq77915.pdf?ts=1772557832985) and a pair of [highly efficient MOSFETs from Infineon](https://www.infineon.com/assets/row/public/documents/24/49/infineon-iqdh35n03lm5-datasheet-en.pdf?fileId=8ac78c8c8a44f57b018a456befa5020f), pictured below. It was able to maintain within safe temperatures during a ~50A discharge for more than 60 seconds. In [a following video](https://www.youtube.com/watch?v=pDYJ8d-5PCU), a '[360Wh/kg semi-solid state](https://www.alibaba.com/product-detail/Factory-Price-Solid-State-HvLi-Battery_1601390711844.html)' battery pack was tested and evaluated against its datasheet ratings, and we provided some commentary on the progress of solid-state battery technology.

![[bmsx.webp|345]]
*Example design: Battery protection system section of BMS X based on [BQ77915EVM-014](https://www.ti.com/tool/BQ77915EVM-014) reference design*

A large portion of our battery knowledge is from [Battery Mooch](https://www.patreon.com/c/batterymooch/posts) and [Pajda](https://www.patreon.com/c/Pajda704/posts) on Patreon who we could highly recommend for anyone wanting to know the latest news on practical battery tech.

***

#### To do
- create a versatile, robust, and modular active balancing circuit
- make an easy to use cylindrical battery recycling system which helps solve the issue of leftover nickel / copper chunks while keeping the steel plating intact / restoring it 
- implement fuel gauges and programmable battery monitors with the newest battery cells using high nickel cathodes, silicon-composite anodes and/or modified voltage ranges
- create an 'active' battery cycle life tester that efficiently converts power instead of wasting it
- look into using GaN FETs as power switches for their increased power density and [surge robustness](https://www.ti.com/lit/ta/sszt507/sszt507.pdf?ts=1772636379538) 