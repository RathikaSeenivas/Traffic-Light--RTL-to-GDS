# Traffic-Light--RTL-to-GDS
`Full RTL-to-GDSII physical design of a Traffic Light Controller ASIC using Cadence Innovus — includes Verilog RTL, synthesis netlist, SDC constraints, place &amp; route, CTS, RC extraction, timing sign-off, and formal verification.`

What is this?
This project implements a Traffic Light Controller as a digital ASIC chip, going through the complete physical design flow — from writing RTL code all the way to a final GDS layout file ready for fabrication.

Tools Used
Cadence Genus — Logic Synthesis

Cadence Innovus — Place and Route

Cadence Conformal — Formal Verification

Verilog — RTL and Netlist

SDC — Timing Constraints

TCL — Flow Automation

Design Flow
Verilog RTL → Logic Synthesis → Floorplanning → Placement → Clock Tree Synthesis → Routing → Timing Sign-off → GDSII Layout

File Structure
traffic.v — RTL design

traffic_tb.v — Testbench

TrafficLight.v — Top-level module

trafficc_netlist_1.v — Gate-level netlist

constraints_trafficc.sdc — Timing constraints

run.tcl — Innovus run script

TrafficLight.gds — Final GDS layout

rc_model.bin — RC parasitics

timingReports/ — Setup and hold reports

fv/ — Formal verification workspace

Key Results
GDS layout generated successfully

Timing closure achieved

Formal verification passed between RTL and netlist

RC extraction completed

Author
VLSI Physical Design Project — Cadence Innovus Flow
