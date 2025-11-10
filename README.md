# CMOS-demo

CMOS simulator for ENR325

To try out, click here: https://xlicoe.github.io/CMOS-demo/

**The state changes across wires, especially in the floating state, are not realistic.**

## How to use this demo:
![GUI](/../main/graph/1-1.png)

### Step 1: select componnets by click the **Select** button, then pick and place the components on the board.
![GUI](/../main/graph/2.png)

![GUI](/../main/graph/3-1.png)

Above shown is the layout of a classic inverter (NOT gate).

The truth table will be updated in real-time. Right now output (O1) is floating since there are no connection. 

![GUI](/../main/graph/4.png)

### Step 2: select **Wire**, then drag and connect all dots or wires.

![GUI](/../main/graph/how_to_wire.png)

Again, it's 

2.1) Select wire:

![GUI](/../main/graph/5-0.png)

2.2) Connect wires:

![GUI](/../main/graph/5.png)

2.3) Truth table updated in real-time:

![GUI](/../main/graph/6.png)

![GUI](/../main/graph/8.png)
Above shown is a fully built inverter.

### Miscellaneous:

+ For wire connection, use your left click to point, click, hold, drag and connect.

+ Right now it only works for CMOS simulation. Not for PMOS/NMOS only.
+ You can actually save and load your design locally (or clear all), at the manage tab.
+ Edit tool can copy/paste, or go back/forward with operations.
  
![GUI](/../main/graph/7.png)







