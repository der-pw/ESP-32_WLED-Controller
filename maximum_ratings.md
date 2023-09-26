## Maximum Ratings

![IR-Capture](/images/title_maximum_ratings.jpg)  

I did a few tests to check how much power the board can operate with.  
After I parked the board and components in the heated 50°C 3D printer housing for about 2 hours, I set the emissivity for the PCB surface and the components (AMS1117 and IRF4710) to near 0.95. This corresponded very well with my reference values ​​from the insulating tape and Kapton tape, which was stuck to the shield to measure the temperature of the ESP housing.
I've tested with about 6m WS2812B Strip with 375Pixels. Connected on booth sides.
The Current was measured with a KAIWEETS HT206D clamp meter in good condition.  
Thermal images were made with an Infratec Vario Cam HD, 30mm Lens.

## Front Side
"M-Wert" is average of the area. But it's also the value for one point. I forgot to switch the language. 
### 5 Ampere
![Front 5A](/images/mr_frontside_5A.jpg)  
MOSFET is almost still cold.
### 7.5 Ampere
![Front 7.5A](/images/mr_frontside_7-5A.jpg)  
MOSFET completely uncritical at 45°C, the trace at 40°C. Hold time in this state was 30 minutes.
### 10 Ampere
![Front 10A](/images/mr_frontside_10A.jpg)  
MOSFET housing was at almost 70°C, the trace scratched at the 60°C mark.
Not super critical, but this is where I would start thinking about how to start cooling.
Accumulated heat should be avoided in the housing or even actively removed.

## Back Side
### 5 Ampere
![Back 5A](/images/mr_backside_5A.jpg) 

### 10 Ampere
![Back 10A](/images/mr_backside_10A.jpg) 

## Summary

I think the board is not suitable for the very, very large projects. At least not if you want to chase all the current through the MOSFET. Of course you can also switch an external relay via "STRP_5V". If I had to answer the question of how long the strip can be, I would say. maximum 3m to 4m with 60LED/m. That's a good value.  
In this case, shorter is better. 😁  
It's often the case that you never set the full brightness, but remember that may errors can occur. You just have to decide that for yourself. I hope the metrics will help you.
