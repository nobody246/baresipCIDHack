# baresipCIDHack

This is a modification of 1 file in baresip v0.5.11.

The send_invite method is modified to allow the user to set the callerid to whatever they choose by creating a 1 line text file located at /tmp/.cid_baresip with the desired outgoing callerid in the sip address format. It's a somewhat dirty hack and it's the wrong way, but it does work for my purposes.

just get the source code for baresip 0.5.11 from the official repo and replace src/call.c with the one included in this repository and build as normal.
