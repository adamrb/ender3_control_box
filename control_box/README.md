# Ender 3 Control Box

This is a 3D printable control box to replace the mainboard enclosure. This enclosure contains:

- A [Raspberry Pi 3B](https://www.raspberrypi.org/products/raspberry-pi-3-model-b/) for running OctoPrint,
- A [BigTreeTech SKR 1.3 main board](https://github.com/bigtreetech/BIGTREETECH-SKR-V1.3),
- (optional) [A Google AIY Audio Hat](https://aiyprojects.withgoogle.com/voice-v1/) with Speaker and microphone,
- 2 LM2596 Step down converter for providing 12V for the lights and 5V for the raspberry Pi,
- 2 or 3 5V relay switch modules controlling the printer, the lights and a fan for the raspberry Pi.
- Instead of one the relay switch, there is the option to put a [24V UPS Mini from BTT](https://github.com/bigtreetech/BIGTREETECH-MINI-UPS-V2.0/tree/master/BTT%20UPS%2024V%20V1.0).

This installation is controlled using an OctoPrint plugin available at
[damienmg/OctoPrint-ControlBox](https://github.com/damienmg/OctoPrint-ControlBox).

The main entry point is  [constrol_box.scad](control_box.scad). All parameters for this box can be changed in [params.scad](params.scad).

The top of the box has 2 STLs that can be combined following
[this tutorial](https://medium.com/@damien.martin.guillerez/multi-filament-print-with-a-single-extruder-using-prusaslicer-2e0746348cdd?source=friends_link&sk=541dcda7cd469b502874ed76e266267e).

This object can also be found on [Thingiverse](https://www.thingiverse.com/thing:3839977).
