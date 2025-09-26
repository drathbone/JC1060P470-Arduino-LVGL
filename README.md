# JC1060P470-Arduino-LVGL
Template Arduino sketch for the JC1060P470 ESP32-P4. Drivers for touchscreen and display are enabled for LVGL.

Modified version of the example files to remove all of the LVGL demos, leaving this ready to start adding your code.
You will need to move the lv_conf.h (included in the lvgl directory) into your Arduino libraries directory.

Nothing is being output to the screen on this sketch, although LVGL is fully enabled uing 8.3.
If you use the touchscreen then the co-ordinates are printed to the serial output (for testing).

I've used this as a template to then add UI code with things like EEZ Studio, and so far things are working great.

Hope someone finds this useful :)
