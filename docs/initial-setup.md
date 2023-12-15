# Initial Setup

After setting up the device (firmware, SD card, WLAN) the device will connect to the wifi access point and start in an initial setup configuration:

![](img/setup_initial_welcome.png){: style="width:500px"}

With the buttons on the top you can navigate through 5 steps which guide you through the necessary setup:

1. Create the [Reference Image](Reference-Image.md). It is the base for the position referencing and the identification of the digits and counters.
1. Define two unique [Reference Marks](Alignment.md). They is used to align the individual camera images and identify the absolute positions.
1. Define [ROIs](ROI-Configuration.md) for the Digits. They will be used to digitize the digit part of your meter. If your meter has no digits, this step can be skipped.
1. Define [ROIs](ROI-Configuration.md) for the Analog Counters. (Only required in case your meter has analog counters)</li>
1. [General Settings](Configuration.md). Further configuration of your device.

All settings can be accessed later in the normal operation mode.

!!! Note
    Don't forget to save each step with "Save", and do not reboot at this stage.

## Finish the Setup and change to the Normal Operation mode
With the last step `(1)` you leave the **Setup Mode** and reboot to the **Normal Operation mode**.

![](img/initial_setup_6_finish_reboot.jpg){: style="width:500px"}


## Access to the Setup Pages in the Normal Operation mode
You always can access all the settings during the normal operation mode via the `Settings` menu:

![](img/initial_setup_7_access_normal_mode.jpg){: style="width:500px"}

- `(1)` Access to the [General Settings](Configuration.md).
- `(2)` Update of the [Reference Image](Reference-Image.md).
- `(3)` Update of the [Alignment Marks](Alignment.md).
- `(4)/(5)` Update of the [ROIs](ROI-Configuration.md).
