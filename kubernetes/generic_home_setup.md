# Generic home setup commands and helpful details

## Connect to the server
`ssh <<local-ip>>` or use external ip(domain) if exposed on the internet
> Example: `ssh linux-server` -- I set up a hostname in the .ssh/config

## Port forwarding for lens needs
`ssh -L 6443:localhost:6443 <<server-ip>>`
> Example: `ssh -L 6443:localhost:6443 linux-server`