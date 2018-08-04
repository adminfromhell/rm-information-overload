# Information Overload
This is a theme that is almost 100% powered by HWiNFO checks.

## Installing this Suite
Go to releases and download the release that you want, the latest release is prefrerred.

Install [HWiNFO](https://www.hwinfo.com/download.php)

## Configuring the Skins
If a skin does not show any data it is most likley that your sensor ID and/or instance is diffrent from what is in the the sensor files.

You will need to launch the HWiNFO Shared Memory Viewer. This is located in the `[Theme Directory]@Resources\Tools Directory`. Then compare and update any ID's or instances that are diffrent in the corrosponding `[Theme Directory]@Resources\Sensors\*.inc` files.

## Updating Theme Colors
If you want diffrent colors than the preset you can edit the `[Theme Directory]@Resources\Themes\amd.inc` file.

## Common Issues
### Disks not showing up correctly
If this is happening you will want to check and make sure that the correct Disk Letter is assigned to that disk in the  `[Theme Directory]@Resources\config.inc` file.
### Network bars are too small or too big
This is because the `MaxUpload` and `MaxDownload` sizes are incorrect for you ISP speeds. Run a speed test and find out what your max upload and download speeds are. If the speed test returns your speed in Megabytes you will need to convert them to bits.  
You can use this [conversion tool](https://www.gbmb.org/mb-to-bits) to get the correct numbers to replace the values in `[Theme Directory]@Resources\config.inc`
