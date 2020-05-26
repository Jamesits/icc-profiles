# ICC Profiles

A collection of ICC profiles for screens that I have access to. Since OpenSUSE ICC Taxi service is down, I do not have other methods to share ICC profiles publicly so they are now placed here. 

## Usage

Go to the latest measurement result directory of your device model, download the `.icm` file and apply on your device. 

## Accuracy

I cannot guarantee any level of accuracy on the data provided. The main reasons are:

* Every display panel differs slightly
* The same panel's color performance would drift as time goes by
* I can't afford something that can calibrate my colorimeter

## Test Environments

Device: X-Rite i1 Display Pro (uncalibrated)

Software: DisplayCAL (under macOS if it is an Apple device; under Windows for everything else)

Screen (unless otherwise stated):

* Brightness: max
* HDR: off
* Connection: internal > DisplayPort > HDMI, whatever available first
* Other settings: factory settings

## License

`.ccmx` files are from [DisplayCAL Colorimeter Corrections Database](https://colorimetercorrections.displaycal.net). These files are under their own license. 

All other files, unless otherwise stated, is licensed under CC BY 4.0 International license.
