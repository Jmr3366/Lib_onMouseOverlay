# Lib_onMouseOverlay
![alt text](https://github.com/Jmr3366/Lib_onMouseOverlay/blob/main/LibonMouseOverlay.webp?raw=true)

Library token for the Maptool VTT application.

This library token uses functionality that aligns an overlay with a token.
While functional, Maptool does not directly support this.

To get real value from this library token, there is an expectation that you know how to edit macros  
and can navigate the Maptool Wiki.  This skillset can allow you to integrate this into your ways of working  
or framework that you are using.

An overlay is created as you mouse over tokens.  
The overlay provides up to 9 tiles that you can click on that run macros.  
Up to 6 overlays can be configured:
- **Self, PC, Friend, NPC, Foe, Other**
  - Each overlay can contain up to 9 different macros
  - Each macro recieves the Selected Token ID and the Mouse Over ID
    - JSON array sent to macros: `["selected token id","mouse over id"]`
    - The values will be empty if not detected


On the library token, you will find these Macro Groups: **Self, PC, Friend, NPC, Foe, Other**.  
Each group will contain 9 macros that align with each tile location on the overlay.  

These are 9 overlays that I've included as default options.  
![alt text](https://github.com/Jmr3366/Lib_onMouseOverlay/blob/main/onMouseOverlay-incOverlays.jpg?raw=true)
