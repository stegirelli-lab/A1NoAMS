# A1NoAMS - Bambulab A1 (not MINI) manual change filament (no bubble)
This project is created to manually change colors on the Bambulab A1 without AMS. 
The code is based on the work of eukatree https://github.com/eukatree/Bambu_CustomGCode/ and Dennis-Q https://github.com/Dennis-Q/bambu. 
The code replaces (at your own risk) the G-code in the printer settings under "g-code filament change." Color changes can also occur within a layer. 

When the printer pauses, select the unload function from the screen. 
From the "Commands" menu, raise the nozzle temperature to the printing temperature, insert the filament. 
Press the down button once or twice until you feel the filament grab hold. 
Then continue printing.
The code purges the old color until the new color is added.
