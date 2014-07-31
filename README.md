EEPROM2
=======

Extended Arduino EEPROM library with array functions

This library is fully compatible with the standard EEPROM library delivered with Arduino. Just replace #include &lt;EEPROM.h&gt; with #include &lt;EEPROM2.h&gt;

Following functions are added:

void EEPROM.read(address, array *, count);<br>void EEPROM.write(address, array *, count);

New functions read and write a block of EEPROM data starting on given address.

Please note that no address or pointer check is performed!
