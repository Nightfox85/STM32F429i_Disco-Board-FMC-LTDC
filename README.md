I made a STM Cube IDE Project with a Setup that uses the external SDRAM via FMC for the Framebuffer and the LCD initialization via SPI5 for the RGB Interface of the builtin ILI9341 Dispalycontroller. The Display is controlled with the LTDC.
I used max. Clockspeed 180Mhz and make the whole Project Quick and Dirty. There are many Codeartefacts that can be removed.

Setup:
-SDRAM via FMC for Framebuffer on startadress 0xd0000000
-Ili9341 Initialisation via SPI5 for the RGB Interface
-LTDC Controlling the Display

The uploaded Project is an Archive File (.zip) directly exportet from CUBE IDE. You can import it without any changes in the STM Cude IDE (used Cube IDE Rev. 1.18.1)

