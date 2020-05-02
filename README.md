# BitTorrent
This a implementation of BitTorrent application using socket programming in Java.

1) Intialize the file owner:

filerowner.java  ownerport
peer.java         myport1
peer.java         myport2
peer.java         myport3
peer.java         myport4

2) Initialize the download peers:
peer1 > init ownerport myport2 myport3

peer2 > init ownerport myport3 myport1

peer3 > init ownerport myport4 myport2

peer4 > init ownerport myport1 myport3

Components of the project:
connection management system
actor types
control port and data port
thread management
file management system
breaking file into chunks
merging chunks into file
logging
