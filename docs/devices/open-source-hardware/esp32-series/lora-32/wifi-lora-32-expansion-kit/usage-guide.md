---
sidebar_position: 1
title: Usage Guide
---

# WiFi LoRa 32 Expansion Kit Touchscreen Operation Guide

The following sections will guide you step-by-step through the touchscreen button functions, interface navigation, notification sound settings, and how to switch to the new MUI interface. Each step can be accompanied by corresponding photos to provide a more intuitive understanding of the operation process.

##  Startup Mode
Press and hold the `PWR` button for approximately 3 seconds to power on the device and enter the Classic UI.


## Button Instructions
- USER Button: Next/Forward
- GPO35 Button: Previous/Return
- PWR Button: Power switch
- RST Button: Reset
- Touch Screen Operation
  - Click on the screen: Go to the next page (equivalent to the USER key)
  - Long press the screen: Confirm and enter the interface

## Prompt sound setting 

When the system is turned on for the first time, prompt sounds will be played when pressing keys or touching. If you need to turn off or adjust the prompt sound, please follow the steps below:

From the main interface, navigate to `System`, press and hold to enter the system settings, then select `Notifications` followed by `Buzzer Mode` to configure the notification sound as needed.

| Mode          | Click Sound | Message Notification Sound |
|---------------|-------------|-----------------------------|
| ALL Enable    | Yes         | Yes                         |
| Disable       | No          | No                          |
| DMS Only      | No          | No                          |
| Notifications | No          | Yes                         |
| System Only   | Yes         | No                          |

## Switch to MUI

The MUI interface supports advanced features such as full-screen touch control and an on-screen keyboard.

Switching steps:
Enter the `System` menu, press and hold to access the system settings, select `Reboot/Shutdown`, tap `Switch to MUI`, and confirm with `Yes`; the device will then reboot into the new MUI touchscreen interface.

- When the screen is off, press the USER button once to wake the display.
- The new interface supports full touchscreen operation.
- A virtual keyboard will appear when sending messages in a channel.
- This interface enables complete text input and browsing without relying on the mobile app.

## Return from MUI to Classic UI

In the MUI interface, tap the `settings` icon and open the `Reboot/Shutdown` menu. Then, press and hold the `Bluetooth icon` in the center and select `OK`; the device will restart and switch back to the Classic UI.


:::tip
For more detailed instructions on Meshtastic operation, please refer to the [official documentation](https://meshtastic.org/docs/configuration/radio/).
:::