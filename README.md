# Stop-And-Wait-Protocol

Stop And Wait Protocol under TCP connection written in python.

The server sends a single datagram, and blocks until an acknowledgment from the client is received, If the server receives a nack from the client then it will retransmits the datagram.
