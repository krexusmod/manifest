<p align="center">
  <img src="https://raw.github.com/krexus/manifest/mm/krexus-logo.png" width="600">
</p>


*Stock nexus, as it should be*
------------------------------

Manifest
========

**Android 6.0.x** (latest is 6.0.1_r62)

1. Initialize the marshmallow repo's **OMS branch**			
`repo init -u https://github.com/krexusmod/manifest.git -b dr1.6-oms`

2. Sync		
`repo sync`

3. Load the environment		
`ln -s vendor/krexus/utils/krebuild.sh krebuild.sh`		
`. krebuild.sh`

4. lunch and build!		
`lunch ****** && mka otapackage`

Credits
------------
Huge thanks to:  
[George G.](https://github.com/KreAch3R)		
[Ezio Lacandia Bijelkic](https://github.com/ezio84)		
[Dario Ferretti](https://github.com/AndroidRul3z)		
[CallMeAldy](https://github.com/CallMeAldy)		
[Sykopompos](https://github.com/Sykopompos)		
[rascarlo](https://plus.google.com/+CarloDiNuccio/)		
[BeansTown106](https://github.com/BeansTown106)		
[SlimRoms](https://github.com/SlimRoms)		
[Cyanogenmod](https://github.com/CyanogenMod)  
Google	
AOSP
