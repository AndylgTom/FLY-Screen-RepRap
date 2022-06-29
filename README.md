Data 29.06.2022


**Fixes for 7 inch screen**

- Fixed interface in some places for alignment and other languages.
- Fix button to switch bad heat (did not react on pressing).
- Keyboard replaced by nicer one.
- Replaced some icons.
- Added some lines for English and Russian language.

![bandicam 2022-06-29 12-39-13-497](https://user-images.githubusercontent.com/20997012/176363023-1ffa3da0-2457-468e-9305-143e11cf0527.png)
![bandicam 2022-06-29 12-39-20-414](https://user-images.githubusercontent.com/20997012/176363025-16969db3-06a6-4bbc-b5d4-41ed6f3b05db.png)
![bandicam 2022-06-29 12-39-36-665](https://user-images.githubusercontent.com/20997012/176363027-40c632af-46c9-4751-b68d-00daa57a6acc.png)
![bandicam 2022-06-29 12-39-56-755](https://user-images.githubusercontent.com/20997012/176363028-3e8dc0ee-c0ab-4834-830c-ec7273d72878.png)
![bandicam 2022-06-29 12-40-01-718](https://user-images.githubusercontent.com/20997012/176363029-2d91061e-558a-4286-b5e6-d8e5a6bc5d16.png)
![bandicam 2022-06-29 12-40-03-759](https://user-images.githubusercontent.com/20997012/176363031-c9d61947-5d37-49df-be56-30bbf8bc7bd0.png)
![bandicam 2022-06-29 12-40-05-947](https://user-images.githubusercontent.com/20997012/176363032-d4ee7f35-f6da-4f32-9c15-cf22b1a57270.png)
![bandicam 2022-06-29 12-40-23-766](https://user-images.githubusercontent.com/20997012/176363033-64151d2d-2113-437c-ab39-7dbaebd3dc6b.png)
![bandicam 2022-06-29 12-40-44-398](https://user-images.githubusercontent.com/20997012/176363036-86474988-c868-44ed-a58e-b1728f5dd943.png)
![bandicam 2022-06-29 12-40-50-078](https://user-images.githubusercontent.com/20997012/176363037-02589337-eb30-4f8a-a400-aef499baa323.png)
#####
####
###

# FLY-Screen-RepRap
Firmware for the Fly Screens to be used with RepRapFirmware

## Config.g Setup

Edit the config file to include the following line
```
M575 P1 S0 B57600
```
## Upgrading the firmware

- Download the update
- Rename it to update.img
- Place the relevant update into the root of a FAT32 formatted SD card.
- Power on the screen.
- Apply the update.
- Once complete, power down the screen and remove the SD Card

## Adding a boot display

### 4.3" Screen
- Create a 480x232 resolution picture, the picture size should not exceed 128kb
- Rename the picture name to boot_logo.JPG, JPG is uppercase. 
- Put the picture into the root directory of the sd card.
- Plug it into the screen to upgrade.
### 7" Screen
- Create 800x480 resolution picture, the picture size should not exceed 128kb
- Rename the picture name to boot_logo.JPG, JPG is uppercase. 
- Put the picture into the root directory of the sd card.
- Plug it into the screen to upgrade.

## Future Features
- Support printing from the screen sd card and USB disk
- firmware settings are temporarily unavailable, and will be supported in the near future 
- Modify the config.g file on the screen. 
- Configure the machine firmware on the screen without opening the web page configuration

## Compiling/Editing instructions
Please see [here](https://teamgloomy.github.io/fly_firmware_compile.html) for more detailed information regarding compiling and editing the firmware now it is open source.

## Support
If you have any usage problems, please join https://discord.gg/hccjyvv Come to consult me
