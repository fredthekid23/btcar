Trivial Bluetooth Controlled Car

Description:
2 Arduinos will be used in this project, one for the remote and one attached
to the car. The arduino on the remote will be used to transfer data 
while the one on car will be used to control the car. Data transfer will
be handled with serial communication using bluetooth.

///////////////////////
//Remote Arduino (TX)//
///////////////////////
Each control from the remote will be mapped to a character which will be
sent to the car through bluetooth

CONTROLS:
Potentiometer: Controls the steering 
(need to figure out how
 
Button 1: Turn on/ Turn Off

Button 2: Forward/ Reverse
'f' = forward, 'r' = reverse

Photoresistor: Speed of the car (covered=faster, uncovered=slower orviceversaw.e.idc)

////////////////////
//Car Arduino (RX)//
////////////////////
Each character recieved will represent an action to perform on the car


Communication
