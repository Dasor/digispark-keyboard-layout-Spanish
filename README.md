# Spanish keyboard layout for Digispark DigiKeyboard
Original files: https://github.com/digistump/DigistumpArduino/tree/master/digistump-avr/libraries/DigisparkKeyboard

# Installation
You just need to place the the header file `DigiKeyboard.h` into the **DigisparkKeyboard** library, inside your **Arduino15** folder.

### Windows (Arduino IDE 1.6.5 and previous):
```
c:\Users\(username)\AppData\Roaming\Arduino15\packages\digistump\hardware\avr\(version)\libraries\DigisparkKeyboard\
```
### Windows (Arduino IDE 1.6.6 and later):
```
c:\Users\(username)\AppData\Local\Arduino15\packages\digistump\hardware\avr\(version)\libraries\DigisparkKeyboard\
```
### Linux:
```
/home/(username)/.arduino15/packages/digistump/hardware/avr/(version)/libraries/DigisparkKeyboard/
```

# Info
For sending special characters, such as `\[]{}@#`, I modified the `DigiKeyboard.h` write function (line ~203), so to make it send the corresponding keystroke combination.

Remebember you don´t need to change the `scancode-ascii-table.h` just use the default one

#Resources

This is a fork from : - https://github.com/Maiux92/digispark-keyboard-layout-italian
