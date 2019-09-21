
## A MaterialBuilder Script for Redshift in SideFx Houdini

### Features

- Provides a Materialbuilder for PrincipledShader based on a Texture-Selection by the user
- creates a tree based on Filnames and works best with strings provided by Substance
  - base_color or basecolor
  - roughness
  - normal
  - metallic
  - reflect
  - height
  - displace
  - bump
  - ao or ambient_occlusion
- The strings to look for can easily be changed at the bottom of the script
- A shelf is provided in the toolbar folder (put it to $HOUDINI_USER_PREF_DIR/toolbar)


###  Example Node tree for MaterialBuilder

![alt text](https://raw.githubusercontent.com/eglaubauf/materialBuildRedshift/master/images/Tree.png "The Tree created by the Script")

### Installation:

Append egLib to Houdini Python path or add to 123.py or 456.py

```
import sys
sys.path.append("<PathToLib>\scripts")
```

### Notes:

All of the scripts are free of charge for free use, commercial or non commercial whatsoever.  But this script may break your workflow. 

### Contact/Issues/Features/Questions

Please check out my other Repos as well, they might be handy to you. For any questions and/or improvement suggestions just contact me via twitter or mail.<br>
Twitter: @eglaubauf <br>
Web: www.elmar-glaubauf.at
