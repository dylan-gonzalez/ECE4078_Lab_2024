# Description

Operating the robot works by using the `self.command['motion']` attribute, of which the first index corresponds to forward speed and the second index corresponds to turning speed.

Forward: [1, 0]
Reverse: [-1, 0]
Left: [0, 1]
Right: [0, -1]

I have also implemented speed control, which increases the values of the commands based on the sign of the value (to maintain the forward/reverse direction, or left/right direction). Speed control works by ppressing +/-. 
