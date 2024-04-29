# Power Related Questions  
## 36.Two power components
Low power design is important since battery plays an important role in mobile consumer electronics.  
Static Power, Dynamic Power

## 37. Reduce static power in RTL
Static power is related to the chip area, the area is related to number of logic gates.  
- Minimize the number of gates by resource sharing techniques(RTL coding)
- Turning off the power to that logic.

Isolation cell is placed on the outputs of the powered off circuits to ensure that a know value is driven after the gates are off. It can be instantiated in RTL code or inserted afterwards by backend  physical design team.  

Retention flip flops are used to retain certain important values.
## 38. Dynamic Power
Short Current Power + Switching Power

## 39. Low Power Design technique with RTL code
