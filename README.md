# homelab
This is the repository containing some necessary config files for my homelab setup. It is still a work-in-progress as I change things depending on how I'm feeling with my setup at the moment :).

## Hardware
The setup is currently running on a 4 GB Raspberry Pi 4 Model B, with a 1 TB external HDD from WD.

## Software
At the moment the services I host are:
- reverse proxy and HTTPS with Nginx Proxy Manager;
- DNS sinkhole and local resolver with Pi-Hole;
- self-hosted image backup and cloud with Immich;
- Jellyfin media streaming server, with *arr stack for media requesting, indexing and downloading;
- network drive for internal LAN access with Samba;
- Homarr dashboard for an easy overview;
- \[TBD\] Tailscale/OpenVPN for external access;

The majority of the services are inside docker containers, in order to separate the responsibilities and isolate services.