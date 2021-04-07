# MG-EV-OBD-PID
PID file for MG EV suitable for use with Torque Pro
These are being tested with an Australian 2021 model MG ZS EV.

## How to use:
These codes are primarily for use with Torque Pro which runs on Android phones and tablets.

Download https://github.com/peternixon/MG-EV-OBD-PID/archive/refs/heads/main.zip and extract the "extendedpids\MG ZS EV.csv" file into the ".torque\extendedpids\" directory on your phone then import it from the "Settings \ Manage extra PIDs/Sensors \ Add predefined set \ MG ZS EV" Menu in the Torque Pro app.

The Torque wiki has more details at https://torquebhp.fandom.com/wiki/How_to_add_extended_PIDs

If you wish, you can also use my sample dashboards by extracting the files from the "dashboards" directory into the ".torque\dashboards\" directory on your phone then inside the Torque app, go to realtime data and select the gear icon, then select "Layout Settings", then select "Import" and select "MG ZS EV - 1.dash" and repeat for "MG ZS EV - 2.dash".

## What hardware do I need?
Any Bluetooth Diagnostic Scanner supported by Torque Pro connected to an android phone or tablet should be fine however testing is being done with an NX101 Pro with PIC18F25K80 Chip

## Required Software:
[Torque Pro](https://play.google.com/store/apps/details?id=org.prowl.torque)

## What is OBD? What is PID?
OBD is On-Board_Diagnostics. By connecting directly to the car we have access to the status of various vehicle subsystems.
PIDs are the Parameter IDs; these are the codes used to request data from a vehicle
Refer to [Wikipedia ](https://en.wikipedia.org/wiki/On-board_diagnostics)


## Informal warning

Before you download and use this software consider the following: you are interfering with your car and doing that with hardware and software beyond your control (and frankly, for a large part beyond ours), created by a loose team of interested amateurs in this field. Any car is a possibly lethal piece of machinery and you might hurt or kill yourself or others using it, or even paying attention to the displays instead of watching the road. Be extremely prudent!

By even downloading this software, or the source code provided on GitHub, you agree to have completely understood this.
