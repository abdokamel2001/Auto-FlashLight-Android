# Flashlight Control Android

This app uses the sensors on your Android device to control the flashlight in various ways.

# Features

- `Shake to Toggle` : Shake your phone to turn the flashlight on and off with a delay of 1 second to prevent sudden blinking.
- `Activate on Low Light` : Uses the light sensor to turn the flash on when the surrounding gets dark (simulating a sudden power outage) but also uses the proximity sensor so it doesn't turn on when your hand is on the sensor or when the phone is in your pocket.
- `Activate When Picked` : Uses the gravity sensor to turn the flash off when placed face down on a flat surface, otherwise it will keep the flash on.
- `Disable Auto Switching` : Allows you to control the flashlight with the switch only and disables the auto control of the flashlight , you can also control the flashlight with the switch in the auto modes but the sensors will return the flash to its expected state immediately, except in the `Shake to Toggle` mode.
- There is a checkbox that allows the app to run in the background , but when the app is removed from recent apps it won't work.

# Screenshot
<img src="https://i.imgur.com/AezIZF0.png" height="500">
