Project: MiniTemperature Monitor
Design Software:KiCad
Microcontrolled selected: ATtiny412

1. Project Overview
I am designing a compact, standalone digital temperature monitor using an 8-pin microcontroller and a custom-designed printed circuit board (PCB).
The device will measure the surrounding temperature and display the current reading alongside the minimum and maximum temperatures recorded since the last reset.
The goal is to design and manufacture a functional two-layer PCB, program the microcontroller, and create a custom enclosure using 3D printing.
This project will be an opportunity to learn electronics, embedded programming, PCB design, and mechanical product design from the ground up.

2. Project Goals
The primary goals are:
Design an original PCB using KiCad.
Use an 8-pin microcontroller as the main processor.
Measure ambient temperature using a digital temperature sensor.
Display temperature readings on a small Epaper screen.
Track minimum and maximum recorded temperatures.
Include a physical button to reset the recorded minimum and maximum.
Write firmware to control the device.
Manufacture and assemble the PCB.
Design and 3D print a custom enclosure.

3. Planned Features
Temperature Monitoring using a sensor to pull current tempeature data and store high and low temperature data
Oled Display to display the current temp and high and low since last reset
Physical Push button for user to press to reset the high and low
Potential battery power option for travel use
Compact enclosure
Push button to wake screen to save battery usage 

5. Planned Hardware
The following components are being considered. Final selections will depend on electrical compatibility, availability, physical dimensions, and the project budget.
Microcontroller: ATtiny412
OLED Screen: 	Pervasive Displays E2206KS0E1, 2.06"
Digital Temp Sensor: TMP102
Push Button: In progress
Battery holder: In progress

6. Roadmap
Phase 1 — Research and Planning
Phase 2 — Schematic Design
Phase 3 — PCB Design
Phase 4 — Firmware Development
Phase 5 — Manufacturing and Assembly
Phase 6 — Enclosure and Final Testing 

7. Testing Plan
The completed device will be evaluated using the following tests:
Verify that the device powers on reliably.
Verify that the OLED displays readable temperature values.
Compare temperature readings against a separate thermometer.
Verify that minimum and maximum values update correctly.
Verify that the reset button clears the recorded range.
Verify that readings continue updating over an extended period.
Check that the enclosure fits and protects the assembled PCB.

8. The completed project will consist of:
An original two-layer PCB.
A programmed 8-pin microcontroller.
A functioning temperature sensor.
An OLED display showing current, minimum, and maximum temperatures.
A functional reset button.
A custom 3D-printed enclosure.
Complete KiCad design files.
A bill of materials.
Firmware source code.
An engineering development journal.
A video demonstration of the completed device.
