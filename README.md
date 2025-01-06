# Click The Haze
Deadlock main menu "minigame"

## Changing the image

Can be done by editing the url in line 2 of styles/hazeclicker.css

## Building

### Requirements

Source 2 Viewer nightly build
Deadlock
Deadlock community sdk

### Steps

Decompile and export "panorama/layout/dashboard.vxml_c"
Place the decompiled file in the repo to mirror the game's path
Add xml code to the file as detailed in panorama/layout/patch
Use community sdk to compile hazegame.js, hazeclicker.css and the newly made dashboard.xml
place them where the originals are in the repo
Use source2viewer to pack the repo into a vpk, named pakXX_dir.vpk where X is a digit (es pak75_dir)