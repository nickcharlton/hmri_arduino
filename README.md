# HRMI Arduino Sketch

This is an updated Arduino Sketch for [Dan Julio][]'s Polar Heart Rate Monintor
Interface (HMRI). You can [buy them from Sparkfun][product].

Whilst the original sketch mostly works, it requires a bit of modification to work
with newer Arduino boards as some of the methods have changed. That's all this does.

This happened because of the work on iDAT's [Bio-OS project][bioos] I did.

## Pin Out

Based on an Uno:

Arduino Pin | HMRI Board
----------- | ------------
5v          | 5v
GND         | GND
Analog In 5 | TX/SCL
Analog In 4 | RX/SDA

It's recommended that you use a 4.7 kOhm pullup, but I found it worked fine without.

## Credits

The original software is Copyright danjuliodesigns, LLC 2010.

I guess that means this should be licensed in the same way.

[Dan Julio]: http://danjuliodesigns.com/
[product]: https://www.sparkfun.com/products/8661
[bioos]: https://github.com/i-DAT/Bio-OS-Android
