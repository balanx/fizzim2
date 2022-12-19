Fizzim2 (obsoleted ! New tool has been written [here](https://github.com/balanx/FsmLog/))
======

A FSM (Finite State Machine) tools for Verilog HDL.

This project was forked from [Fizzim](http://www.fizzim.com), a very good works, but [**Fizzim2**](https://github.com/balanx/fizzim2) enhances the following features.

- all java, NOT need perl
- add HDL-View, what you see is what you get
- focus on design entry, ignore some features e.g. 'statebit' which can be accomplished by synthesizer
- more explicitly in use, change OUTPUTS type from 'statebit, regdp, comb, flag' to 'onstate, ontransit, ontransit-dd, hold'
- add 'signals' & 'page_mode' feature, support complicated FSM design model
- modify priority feature, use 'UserAttrs' of transition as priority
- 'reset_state' can be set by right-click on state
- fix some bugs

So Fizzim2 will NOT be compatible with the original Fizzim.

![snap1](https://raw.github.com/balanx/fizzim2/master/snap1.png)

![snap2](https://raw.github.com/balanx/fizzim2/master/snap2.png)

### Compile ###
> ant build.xml

### Prerequisites
> Jre (java runtime environment) version 1.6 or above

### Running ###
> java -jar Fizzim2-xxxxxx.jar

### Help ###
> http://www.jianshu.com/p/3562a8a72cb7

### Todo ###
- rules check

### History ###

16.04.26
- change outputs/signals type to 'dff-*, comb-*, *-onboth'
- fix bugs

16.03.22
- initial
