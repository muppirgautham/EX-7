## EX-7 IMPLEMENTATION OF TRACEROUTE COMMAND:
```
DATE : 20-04-2023
```
## AIM :
To write the python program for simulating Traceroute command.

## ALGORITHM :
```
1.Start the program.
2.Get the frame size from the user.
3.To create the frame based on the user request.
4.To send frames to server from the client side.
5.If your frames reach the server, it will send ACK signal to client otherwise it will 
  sendNACK signal to client.
6.Stop the program.
```
## PROGRAM :
```
Developed by :M Gautham
Register Number : 212221230027
```
```
from scapy.all import*
target = ["www.google.com"]
result, unans = traceroute(target,maxttl=32)
print(result,unans)
```

## OUTPUT :

![image](https://github.com/muppirgautham/EX-7/assets/94810884/e7a34357-d33c-4288-b5c1-03de76b4bb96)

## RESULT :
Thus, the python program for simulating Traceroute command was successfully executed.


