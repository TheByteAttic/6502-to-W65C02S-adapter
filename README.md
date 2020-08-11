# 6502-to-W65C02S-adapter
A small daughterboard adapter that replaces a 6502 processor (used in vintage 8-bit computers such as the VIC-20, Apple II and BBC Micro) with a modern, currently manufactured CMOS equivalent. Two versions of the daughterboard are provided (long and short), which fit different motherboards. At the time of this upload, the adapter had been tested only in Commodore VIC-20 computers, in both versions of the VIC-20's motherboard. In both cases it worked flawlessly.
Here are the parts used to populate the daughterboard adapter:
-- 1x WDC W65C02S CPU, DIP 40-pin package;
-- 1x SN74HCT245N bus transceiver (oriented opposite to the CPU), DIP 20-pin package;
-- 1x 3K3 Ohm resistor;
-- 3x bypass capacitors of different values (non-critical). I suggest 1uF (electrolythic), 100nF (mini-electrolythic) and 10nF (tantalum or ceramic), but other values are possible and may work better depending on circumstances;
-- 2x 20-pin single-row precision pinheaders;
-- 1x 40-pin DIP precision IC socket (optional in the long version of the daughterboard, but required in the short version).
