# WhiteFox Configuration
This is my configuration for Input Club/Matt3o's [WhiteFox Keyboard](https://input.club/whitefox) with the TrueFox Layout. 
Feel free to [open an issue](https://github.com/calvinc97/whitefox-config/issues/new) for any possible improvement suggestions!

![WhiteFox (TrueFox) Config](https://raw.githubusercontent.com/calvinc97/whitefox-config/master/assets/layout.png)


## Usage
Make sure your keyboard is in Flash Mode (Orange LED will turn on)
1. Clone the repository `git clone https://github.com/clhcalvin/whitefox-config.git`
2.  Install drivers/dfu-util
    * Windows: Unplug your keyboard and use the [Windows Driver Installer](https://github.com/kiibohd/kiidrv/releases/download/v1.5.3-kiidrv/KiibohdDrivers.msi)
    * Ubuntu: `sudo apt-get install dfu-util`
3. [Download the Configurator](https://github.com/kiibohd/configurator/releases)
4. On the top right of the configurator home screen, click on the Quick Flash button
5. Flash the keyboard with `kiibohd.dfu.bin`
6. Orange LED will turn off, and your keyboard is ready to go!
