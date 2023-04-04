
# A Material Design 3 inspired theme for GarlicOS on the Anbernic RG35XX

## Instructions

1. Clone the repo
2. Open the folder of the specific theme variant
3. Take the boot_image.bmp out of the folder
4. Open up the boot_logo.bmp.gz from the MISC partition in 7-zip
5. Place the modified boot_image.bmp into it and replace the original one
6. Copy the rest from the theme's folder into the CFW/skins folder in your OS/"ROMS" partition
7. Boot into GarlicOS


## Make your own color scheme

I've added .psd files (open them up in Adobe Photoshop ~2022) so anyone can make modifications to the icons/boot logo

## GBA overlays

If you want to have GBA overlays (be it with or without the screen filters), just take the files from "GBA_overlays" and put them into 
```I:\CFW\retroarch\.retroarch\overlay```

After that:
1. Enable the original GBA scaling by enabling 
```Settings > Video > Scaling > Keep Aspect Ratio ```
2. Go to 
```Settings > On-Screen Display > On-Screen Overlay > Overlay Preset```
 and choose the overlay you want