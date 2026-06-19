# VMAX BUS TIPS

**V-MAX BUS SYSTEM in VESTA panels tips:**

## **GENERAL RULES:**

* From one device or bus start to the next, no more than 300 metres may be exceeded.
* Take into account the current required for the system (use calculator or consumption table of the devices).
* Take into account the voltage drop (calculator) If there is a voltage drop, a power supply or isolator-amplifier can be used
* The limit of the BUS system at distance level will depend on the consumption and voltage at each point, if a sufficient current and voltage is guaranteed at each device, the system will operate correctly.

![](<../.gitbook/assets/4 (80).jpeg>)

## **CASE 1: ONE LINE OF BUS**

![](<../.gitbook/assets/5 (64).jpeg>)

## **CASE 2: TWO LINES OF BUS (STAR)**

![](<../.gitbook/assets/6 (71).jpeg>)

## **CASE 3: TREE LINES**

### **CASE 3A. WITH ISOLATOR (Recomended for this CASE)**

![](<../.gitbook/assets/7 (71).jpeg>)

### **CASE 3B. WITH NO ISOLATOR (TIP: Place resistors in the longest BUS sections.)**

![](<../.gitbook/assets/8 (62).jpeg>)

## **CASE 4: FOUR LINES OF BUS**

![](<../.gitbook/assets/9 (47).jpeg>)

## CONSUMPTION TABLE OF V-MAX BUS DEVICES

<table data-header-hidden data-full-width="false"><thead><tr><th></th><th></th><th></th><th></th></tr></thead><tbody><tr><td>DEVICE</td><td>Current Consumption (mA)</td><td>Current Consumption (A)</td><td>Voltage</td></tr><tr><td>892-EX-BUS</td><td>130</td><td>0,1300</td><td>4,50</td></tr><tr><td>KPT-35-BUS</td><td>171</td><td>0,1710</td><td>4,50</td></tr><tr><td>BX-32-BUS</td><td>364,9</td><td>0,3649</td><td>4,50</td></tr><tr><td>892-BUS</td><td>229,8</td><td>0,2298</td><td>4,50</td></tr><tr><td>892-EX-BUS</td><td>397,7</td><td>0,3977</td><td>4,50</td></tr><tr><td>DC-23-BUS</td><td>30,6</td><td>0,0306</td><td>4,50</td></tr><tr><td>DCSV-29-BUS</td><td>13,2</td><td>0,0132</td><td>4,50</td></tr><tr><td>IR-35-BUS</td><td>41,4</td><td>0,0414</td><td>4,50</td></tr><tr><td>SR-35-BUS</td><td>64,4</td><td>0,0644</td><td>4,50</td></tr><tr><td>AMP-BUS</td><td>3,58</td><td>0,0036</td><td>4,50</td></tr><tr><td>WEZ</td><td>31</td><td>0,0310</td><td>4,50</td></tr><tr><td>WEZC-8</td><td>95</td><td>0,0950</td><td>4,50</td></tr><tr><td>WEP</td><td>240</td><td>0,2400</td><td>6,50</td></tr><tr><td>TSP-BUS</td><td>1038</td><td>1,0380</td><td>6,00</td></tr><tr><td>WGT-1-COMBO-F1</td><td>354,6</td><td>0,3546</td><td>8,00</td></tr><tr><td>KP-35-COMBO</td><td>82,7</td><td>0,0827</td><td>4,50</td></tr></tbody></table>

## **Vesta V-MAX Bus - Recommended Cable Type**

The Vesta V-MAX BUS uses RS485 communication. Cable choice matters for reliable operation.

#### **Recommended: Twisted Pair + Shielded**

Use a twisted pair cable with shielding. Twisted pair is optimal for RS485 bus communication as it reduces interference and ensures stable data transmission over long runs.

#### **Alternative: 4+2 Shielded alarm cable**

If twisted pair is not available, a standard **4+2** shielded alarm cable can be used:

* Use the **0.75mm² or thicker** conductors for power (2 wires)
* Use the remaining wires for the RS485 data signals (A/B)

{% hint style="info" %}
**Maximum distance:** 100 meters. Do not exceed this when using 4+2 cable.
{% endhint %}

#### **Summary**

| Cable Type                                  | Max Distance from 1 device to other | Notes                                      |
| ------------------------------------------- | ----------------------------------- | ------------------------------------------ |
| Twisted Pair + Shielded                     | 300m                                | Best option. Always recommended.           |
| 4+2 Shielded alarm cable (0.75mm²+ 0.25mm²) | 100m                                | Use only if twisted pair is not available. |

In installations close to the distance limit, measure the voltage at the last BUS device while the system is operating. If the voltage is unstable or below the required value, shorten the BUS run or add an isolator-amplifier or auxiliary power supply. This prevents intermittent faults, missed events, and BUS communication loss.
