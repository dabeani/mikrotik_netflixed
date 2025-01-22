# mikrotik_netflixed
Mikrotik Wiregurad Netflix Tunnel

Preps:
- one main internet exit for netflx
- other locations need to have a Wireguard tunnel to this location
- this script, with the scheduler need to be created on the "other" locations. Not needed on the Main Exit point.

Tested with 3 Wireguard tunnels - each locations are connected with the main exit point via wireguard tunnels.
You need to change some Variables like USERNAME (Username to run the script), WG-Tunnels (my Tunnel Interface List), and WAN (my External internet Interface list). You can change this to the raw interfaces, but its easier, to create the interface list one time, and you dont need to change any line of the code!

If it does not work, or smashed something, take it easy, no one forced you to do it :).
have fun.
