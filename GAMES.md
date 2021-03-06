
The ports listed here are not necessarily the port(s) that the game will happen 
over, nor the port(s) that your server(s) are listening on. Listed here are the
ports that a game will use to discover servers or other peers. These ports are 
decided by the client, and are often unchangeable. 

For some games, your server must be set to listen within this range of ports, 
otherwise it will not see the broadcast, and will not respond to the discovery
request. 

Note: network broadcast address is the subnet with all network bits set to 1.
eg, 10.0.0.0/24 has a broadcast address of 10.0.0.255. 

### ARMA 2/ARMA 2:OA/DAYZ
Tested using 1.62.103419. Broadcasts on 255.255.255.255.

Broadcasts on every 12th port, between 2302 and 2470 (inclusive).

### Blur - Works
255.255.255.255

Port 50001

### Flatout 2 - Works
255.255.255.255

Port 23757

### OpenTTD - Not working
Tested using 1.3.1, does not appear to acknowledge broadcasts from other
LANs. Broadcasts using network broadcast address.

Have tried: 
* Changing broadcast address to suit new subnet
* Changing broadcast address to 255.255.255.255

It seems to just continue ignoring it.

Broadcasts on port 3979



### Source Engine (HL2DM, TF2, CS:S, CS:GO, etc) - Works

Tested with TF2 (2013-10-02), but all should be the same. Sends broadcasts on 
255.255.255.255, do not need to rewrite IP dest address.

Broadcasts on ports 27015-27020.

### Trackmania [United|Nations] Forever - Works
Tested on Steam version of United Forever. Broadcasts on 255.255.255.255.

Broadcast ports 2350-2360.

### Trackmania 2, Shootmania - Works
Tested on Steam version of Trackmania 2 Stadium on 2013-10-02.
Broadcasts on 255.255.255.255.

Broadcast ports 2350-2360.

### Unreal Tournamenet 2004 - Works
Tested with version 3369. Sends broadcasts on 255.255.255.255.

Broadcasts on port 10777.


### Warcraft 3/WC3: Frozen Throne - Works
Tested with version 1.23.0.6352. Broadcasts on 255.255.255.255

Broadcasts on port 6112

### Warsow - Works
Tested with version 1.02. Sends broadcasts on 255.255.255.255.

Broadcasts on port 44400.
