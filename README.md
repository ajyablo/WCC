# WCC <br>
<b>Workstation Control Centre</b><br>
<i>All of my projects and hardware are named after Futurama Characters.<br>
My Home Server has been named "Welshi" after the replacement for Scotty in Star Trek in "Where No Fan Has Gone Before".<br>
This project uses "Welshi" in place of "Workstation" quite often.</i>
<p>
DIY "Pi-KVM" to allow remote control of a PC.
<p>
Bill of Materials.<br>
Raspberry Pi 4<br>
5V Relay (2 ch)<br>
HDMI to USB Encoder<br>
<p>
General notes:<br>
Tkinter GUI<br> 
Relays trigger to turn PC on or off via joining the motherboard contacts while still retaining the case button controls.<br>
Power and Hardware Reset buttons check if System is ON or OFF with the Power LED+ off the motherboard.<br>
-If ON, program holds power longer for OFF command.<br>
-If OFF, program only presses power for a couple of seconds to trigger ON command.<br>
Ping service to check system status.<br>
-IP is settable by GUI.<br>
<p>
Future:<br>
Add video overlay (via cv2?) to see the server's HDMI output.<br>
Add GUI feedback for relay status.<br>
Add GUI feedback for System state.
