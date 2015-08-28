# Stinger-Tor
Python-coded Tor DoS tool with slow-GET and GET flood that can't be filtered by anti-DoS systems.
Coded by @WhitePacket ~ whitepacket.org
Utilizes multi-threading with 256 threads default, and a thread capacity of 376.
Waits 5-20 seconds between each HTTP header in slow-GET mode to consume all web-server sockets, possibly crashing or over-loading it. Sends HTTP requests as fast as possible with the flood option; This ends up being a battle of application-layer server power, or bandwidth.
The payload is an exact replica of the latest version of the Tor Browser Bundle sending a GET request. This way if they end up filtering the traffic, almost all users can't visit the website anyways. All requests under Tor come from 127.0.0.1 so our DoS tool is completely identical to a Tor Browser Bundle user looking to visit your homepage.
Hopefully this is used for good, not bad. Maybe a few unmentionable, illegal Tor servers go down.
Donate BTC (nobody ever does): 1MfxuyEFY6StHo3gBPdNyRWGFDMxRutEXp
