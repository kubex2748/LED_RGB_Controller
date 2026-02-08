This project is a PC application for controlling an RGB LED strip via a microcontroller such as an ESP32 or Arduino over a USB connection. 
The user first selects the USB port to which the controller is connected. Using the Select Color button, RGB values can be chosen to change the LED strip color. 
The LIGHT button turns on white light (255, 255, 255), while Turn Off switches the LEDs off (0, 0, 0).
The Submit button confirms the selection and sends the data to the controller. 
Users can also manually enter RGB values in the input fields below the Turn Off button. A brightness slider below the Submit button allows adjustment of the selected color’s intensity. 
The currently selected color is displayed in a preview square at the top, with its RGB values shown below.

On the controller side, it is enough to upload the provided script to the microcontroller, select the appropriate pins, connect a simple MOSFET-based driver, and attach the LED strip.
