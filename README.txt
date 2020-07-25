This Project is meant to incorperate a fuel economy meter into my friend
Avery's van.

Van Model: 1989 GMC Vandura, G2500, 5.7 V8 auto-trans

Scope: Make the van update an lcd display which displays fuel economy and other information desired.

How: Planning on tapping into connections to gauges and taking those readings into GPIO of microcontroller, which powers LCD.
Also planning on using arduino as it will be much faster.


Possible problems:
- Data from connections are most likely analog. Arduino, has a readAnalogFunction that might be able to be used for that.
- Would like to keep a record of how far the car has driven since first running. This will possibly require permenant memory storage. Also assuming the car has a mechanical odometer, it will make gathering distance covered much harder. Possible that we would need to incorperate a new sensor into the car to get that data if that's the case.



Documentation of Process:

-Contacted Avery about putting a new sensor into the car. Would give him something to do in terms of designing mounts.

- Discovered that arduino's have EEPROM memory built into them (1000Kb). So I can store the car's overall distance covered + other stuff between turning the car on/off.



