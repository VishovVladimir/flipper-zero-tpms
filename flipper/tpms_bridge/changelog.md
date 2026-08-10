v1.1:
Clearer key hints on the list screen. The R:wake and L:auto hints now sit
on the side of the key they name, and periodic waking is shown in the
header as "wake" instead of a bare "W".

v1.0:
First release.

Receives Renault TPMS sensors on 433.92 MHz and shows them on the Flipper
screen: sensor list with signal level bars, and a detail screen with
pressure in bar, PSI and kPa, temperature, current and peak signal level,
frame counter and protocol flags.

Wakes a sensor at rest with a 125 kHz field: a single pulse on the Right
key, or a repeating pulse every 5 seconds on the Left key.

Streams decoded frames as line-delimited JSON over the USB CLI through the
tpms_rx command, for logging and charting on a computer.
