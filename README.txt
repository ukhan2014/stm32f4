Readme:

Date: Oct 11, 2015
------------------
This is my stm32f4 projects readme. I am using the stm32f4 discovery board. MCU is stm32f407vgt.

Projects are developed and debugged on Eclipse Mars running on Late 2013 Macbook Pro 13" Yosemite. To set up the projects in this git repository we have to follow two documents that I originally found on the Internet:
1. http://grafixmafia.net/updated-using-the-stm32f4-discovery-board-with-mac-osx-10-9-mavericks/   <-- Thx to Markus Müller from Oldenburg
2. http://eraycanli.com/2015/08/19/using-standard-peripheral-library-instead-of-hal-with-stm32f4/  <-- Thx to Eray CANLI from Ankara

Since these links may change, I will extract the info and set it up in a PDF file titled Environment_Setup.pdf. Link 1 is about setting up the compilers and linkers with eclipse under Mac. Since by default the environment will be set up to use the STM_HAL drivers from ST (which I found very difficult to use), Link 2 will help us convert the environment from using STM_HAL drivers to the STM32 Standard Peripheral Library, which makes much more sense at the time of this writing. Both links will be contained in the Environment_Setup.pdf file.

After the environment has been setup, the individual projects can be cloned, built, loaded and debugged on the device.  


