<h1>CNC Plotter Machine Simulation Using Proteus</h1><hr>

A 3-Axis CNC Plotter Machine simulated in Proteus using Arduino Uno, ULN2003 stepper motor drivers, and 28BYJ-48 stepper motors. The project demonstrates CNC motion control by operating X, Y, and Z axes and plotting a heart-shaped pattern through predefined coordinates. The simulation provides real-time feedback using the Proteus Virtual Terminal.
<hr>
<h2>Features</h2>

* 3-Axis CNC Motion Control (X, Y, Z)
* Arduino Uno Based Controller
* ULN2003 Driver Interfacing
* 28BYJ-48 Stepper Motor Control
* Heart Shape Plotting Algorithm
* Virtual Terminal Monitoring
* Automatic Restart Countdown (5 to 1)
* Fully Simulated in Proteus
<hr>
<h2>Components Used</h2>

* Arduino Uno
* 3 × 28BYJ-48 Stepper Motors
* 3 × ULN2003 Driver Modules
* Virtual Terminal
* 5V Power Supply
* Proteus Design Suite
* Arduino IDE

Circuit Diagram

<img width="100%" alt="Proteus Simulation" src="images/proteus_circuit.png">
<hr>
<h2>Pin Configuration</h2>

<table>
  <tr>
    <th>Axis</th>
    <th>Arduino Pins</th>
  </tr>
  <tr>
    <td>X-Axis</td>
    <td>D2, D3, D4, D5</td>
  </tr>
  <tr>
    <td>Y-Axis</td>
    <td>D6, D7, D8, D9</td>
  </tr>
  <tr>
    <td>Z-Axis</td>
    <td>D10, D11, D12, D13</td>
  </tr>
  <tr>
    <td>Virtual Terminal</td>
    <td>TX (D1)</td>
  </tr>
</table>


<hr>
<h2>Working Principle</h2>

1. Arduino initializes X, Y, and Z axes.
2. Z-axis performs Pen Down operation.
3. X and Y axes follow predefined coordinates.
4. A heart-shaped pattern is generated.
5. Z-axis performs Pen Up operation.
6. System displays completion status.
7. Countdown from 5 to 1 starts.
8. Drawing process automatically repeats.
<hr>
<h2>Virtual Terminal Output</h2>


<pre>
=================================
     CNC PLOTTER MACHINE
=================================

Initializing X Axis...
Initializing Y Axis...
Initializing Z Axis...
Ready

Drawing Heart Shape...

Pen Down

Move X: 50  Y: 50
Move X: 30  Y: 40
Move X: 20  Y: 30
...
Heart Shape Completed

Restarting in...
5...
4...
3...
2...
1...

Starting New Heart Drawing...
</pre>

<hr>
<h2>Applications</h2>

* CNC Machine Learning
* Motion Control Systems
* Embedded Systems Projects
* Automation Demonstrations
* Educational Simulations

<hr>
<h2>Software Used</h2>

* Proteus 8 Professional
* Arduino IDE
<hr>
Developed By
<div align="center">
<h1 style="color:#0A66C2;">Pritam Kumar Gupta</h1>  
</div>
