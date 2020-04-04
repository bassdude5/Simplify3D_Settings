# Simplify3D_Settings
Settings for Simplify 3D for various printers

# Important g code commands

M851 Z0; // Set the Z offset to zero height
G28;     // Home Z in the middle of the bed
G1 Z0;   // This will move the head to zero height;

## Important for autoleveling. Make sure you dont go too far negative or you will damange your bed
M211 S0; // This will disable the end stops so that you 
         // will be able to proceed lower than Z=0
         
         
         
### See this article on stack overflow: https://3dprinting.stackexchange.com/questions/5857/z-offset-on-autoleveling-sensor-setup
