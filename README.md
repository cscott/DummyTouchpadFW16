# Dummy Touchpad Input Module
![image](DummyTouchpad.jpg)

This is a dummy touchpad.  All it does is contain the resistors and pads to
tell the FW16 that there is a touchpad installed (though there is not).
It also brings the signal lines out to a 2.54mm SMT header, but that's
mostly for debugging/development, not for any real use.

If you are using this in conjunction with a
[full width touchpad spacer](https://github.com/cscott/TouchpadSpacerFW16)
don't populate the header.

Here's the [schematic](./MinimalSmallInputModule.pdf).

## License
Input Modules © 2023 by Framework Computer Inc is licensed under CC BY 4.0. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/

## Fabrication and Assembly
Use a 0.8mm PCB for Input Modules.

As with the Framework [example](https://github.com/FrameworkComputer/InputModules/tree/main/Electrical/MicrocontrollerInputModule) use Keystone 24929
"zero height threaded inserts" ([available from Digikey](https://www.digikey.com/en/products/detail/keystone-electronics/24929/16343672))
where indicated, with the "big" side down.  These are soldered in place
and provide enough steel to engage properly with the magnets on the
FW16 midplate to hold the PCB in place.

![image](./images/assembled.jpg)
