# PLC-Handling-Arm
# Function of handling Arm is to load and unload an object from a machine

Sequence of operation: 

Loading

•	Detect a new object need to load on the machine 
•	Clamp the object 
•	Attack the machine 
•	Clamp the object by the machine clamping ( interface signal between the machine and the handling  arm )
•	Unclamp the object by the handling arm 
•	Return to the home position (return to meddle position is pounce )

Unloading

•	machine will send finish signal after finishing its process  ( interface signal between the machine and the handling  arm )
•	handling arm will attack the machine 
•	clamp the object by the handling arm clamps  ( interface signal between the machine and the handling  arm )
•	unclamp the object by the machine  ( interface signal between the machine and the handling  arm )
•	return to the home position 
•	unclamp the object on the conveyer 
