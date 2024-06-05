# VESTA 363

**BUS Isolated Range Extender (ISL-1-BUS)**

**Introduction**

The ISL-1-BUS is an isolated range extender. It can extend the communication range and amplify the signal of wired security system over long distances, while protecting the connected devices against short circuit downstream. The isolator has galvanically separated the input and output terminals. In case when there is a short circuit at the output, all the devices connected to the input of ISL-1-BUS will continue to operate without interruption. The ISL-1-BUS can also boost the voltage up to 13.5V for BUS devices connected to output.

**Identifying the Parts**

![](<.gitbook/assets/0 (10).png>)

1. **BUS Wiring Outlet for Input Lines**
2. **Pluggable BUS Terminal for Input**
3. **LED for BUS Terminal (Input)**

The LED lights up when the BUS output terminal A is powered.

1. **Terminal Resistor Jumper for Terminal Input**

![](<.gitbook/assets/1 (6).jpeg>)

Turn the jumper to OFF by removing or “parking” the jumper link.

![](<.gitbook/assets/2 (5).jpeg>)

Turn the jumper to ON by resting the jumper link on both pins.

1. **LED for BUS Terminal (Output A)**

The LED lights up when the BUS output terminal A is powered.

1. **Terminal Resistor Jumper for BUS Terminal (Output A)**

![](<.gitbook/assets/3 (5).jpeg>) Turn the jumper to OFF by removing or “parking” the jumper link.

![](<.gitbook/assets/4 (5).jpeg>)

Turn the jumper to ON by resting the jumper link on both pins.

1. **Pluggable BUS Terminal for Output A**

The LED lights up when the BUS output terminal A is powered.

1. **BUS Wiring Outlet for Output Lines**
2. **Pluggable BUS Terminal Output B**
3. **LED for BUS Terminal (Output B)**

The LED lights up when the BUS output terminal B is powered.

1

1. **Terminal Resistor Jumper for BUS Terminal (Output B)**

The same function as Terminal Resistor Jumper for Terminal Output A.

_**Please note:**_

* _**After unplugging the terminal(s), when re-installing the terminal(s) back to the board, make sure to install the terminal(s) in the same orientation to avoid potential hazards.**_

**Power Supply**

The ISL-1-BUS is powered by the Hybrid Panel BUS. As a booster, the ISL-1-BUS can provide 13.5V, 0.5A power on each of its output terminal A and B.

**Wiring Connection**

Adding the ISL-1-BUS to the existing BUS system will extend the BUS range and boost the power up to 13.5V, 0.5A for each of its output terminal A and B.

As the input terminal and two independent output terminals are galvanically separated, the ISL-1-BUS protects the connected devices against short circuit downstream.

When adding the ISL-1-BUS to the BUS system, BUS will be split into 3 independent BUS segments (BUS line1, BUS line 2, and BUS line 3).

* As shown in the diagram below, Hybrid Panel, as the first BUS device on **BUS line 1** is connected to the ISL-1-BUS input, which is the farthest device on BUS line 1. Be sure to set both the Terminal Resistor Jumpers of the Hybrid Panel and ISL-1-BUS input to ON to serve as a terminating resistor.
* The two individual output terminals of ISL-1-BUS are each connected to separate BUS devices through **BUS line 2** and **BUS line 3**. Output terminal A is the first device on BUS line 2; output terminal B is the first device on BUS line 3. Be sure to set the Terminal Resistor Jumpers to ON for the two ISL-1-BUS outputs as well as for the furthest BUS devices at the end of each BUS line to serve as a terminating resistor.
* The total number of BUS devices (refer to as “nodes”; the Hybrid Panel is counted as one node) on each BUS line must be within 32 or less. Otherwise, BUS signal abnormalities may occur. In the example below, there are a total of 3 BUS lines: **BUS line 1** contains 2 nodes (Hybrid Panel and ISL-1-BUS), **BUS line 2** contains 3 nodes (ISL-1-BUS and 2 BUS devices), **BUS line 3** has 3 nodes (ISL-1-BUS and 2 BUS devices).

![](<.gitbook/assets/5 (3).jpeg>)

_**Please also note:**_

* _**As ISL-1-BUS provides up to 0.5A for each of its 2 output terminals, it is recommended to connect the BUS devices to ISL-1-BUS’s output terminal one by one to ensure optimal system operation. Please try to avoid connecting all the devices to the output terminal at once.**_
* _**Given that the control panel supplies power to ISL-1-BUS, the maximum wiring distance from the control panel to ISL-1-BUS is 300 feet.**_
* _**It is recommended to have only one ISL-1-BUS on a single BUS line.**_

2
