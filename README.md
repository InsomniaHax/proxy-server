# proxy-server
This script is initializing a proxy that functions as a relay between client and server, it helps to observe and analyse packets via hexdump which i created, but also the data gets decoded into plain text.

## Note:
`request_handler` and `response_handler` functions are meant to be modified to your favor so you can easily edit packets. 

## Dependencies:
- sys (builtin)
- socket (builtin)
- threading (builtin)
