CoinyeCoin [COYE]

RPC 41337
P2P 41338

http://coinyeco.in/

Contact:

IRC: irc.freenode.net Channel: #coinyecoin


Grab OSX client here (OSX 10.8+):  https://www.mediafire.com/?dclgrk4u87l6rpd


To build an OSX client, you'll need brew http://brew.sh/

Then install all the stuff as per litecoin building tutorial, but using brew, not macports.

-----  Config -----

Create ~/Library/Application\ Support/CoinyeCoin/coineycoin.conf

with:
```
rpcuser=coinye
rpcpassword=coins
rpcconnect=127.0.0.1
daemon=1
server=1
#port=41338
maxconnections=200
maxsendbuffer=10000
maxreceivebuffer=500000
addnode=72.46.130.53
addnode=108.168.55.170
addnode=94.242.254.73
addnode=199.241.191.148
addnode=37.187.93.104
addnode=23.253.71.20
addnode=94.242.254.73
addnode=24.20.187.178
addnode=37.59.31.34
addnode=37.59.54.28
addnode=62.212.72.31
```
