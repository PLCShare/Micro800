This folder contains documentation for the Micro870 PLC trainer featuring:

    * Micro870 24QBB PLC with IF4, OW4I, and serialisol plug in modules
    * Master Control Relay (Siemens 3TK2823-1C830) with two emergency stop pushbuttons
    * two three-phase WEG reversing motor starters
    * DC motor to show operation of Motor Starter #2 
    * interposing relays
    * lighted pushbutton
    * two green panel lamps
    * on-off-on selector switch
    * on-off-on momentary switch
    * Red, Yellow Green light tower with alarm
    * 24 VDC to 10 VDC power supply
    * three 10-turn potentiometers
    * RS-422 to USB converter

This folder contains a Connected Components Workbench template where the I/O are mapped to global memory locations via three programs including:

    * prgInMap (ladder)
    * prgOutMap (ladder)
    * prgInMapAnalog (function block)

Code developed with Connected COmponents Workbench version 20.01.00 (standard edition)

Notes:

    * The power for the motor starters is derived from the Master Control relay (MCR). Note that the corresponding interposing relay will activate but the motor starter coils will not activate without MCR activation. Recommend the red tower lamp be programmed to activate if the MCR is not activated.


TODO:

    * Schematic