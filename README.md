# baresipCIDHack

This is baresip v0.5.11 with a minor modification in the send_invite method that allows one to
set the callerid to whatever they choose by creating a 1 line text file located at /tmp/.cid_baresip with 
the desired outgoing callerid. It's a dirty hack and it's the wrong way, but it does work.

just get the source code for baresip 0.5.11 from the official repo and replace src/call.c with the one included in this repository and build as normal.
