pi-plex-server

Simple ansible playbook for deploying a plex server to a pi3. 

Assumes: you have a nfs server (a synology diskstation in this example), exporting /volume1/movies.

Extra features: 
* puts an apache proxy to do port forwarding of the plex interface to port 80, so you can just log into http://plex-server.local
