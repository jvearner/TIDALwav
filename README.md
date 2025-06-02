# TIDAL<sub>wav</sub>
## A self-hosted music streaming platform

### Hardware Used 
- Raspberry Pi 4
- 128gb SD card
- 16gb USB-A flash drive

### Programs Used
- [Ubuntu Server LTS](https://ubuntu.com/server)
- [Docker](https://www.docker.com/)
- [Navidrome](https://www.navidrome.org/)
- [Tailscale](https://tailscale.com/)
- [Samba](https://www.samba.org/)

### Setup Instructions

1. [Install Ubuntu Server](https://ubuntu.com/tutorials/how-to-install-ubuntu-on-your-raspberry-pi#4-boot-ubuntu-server) on the Raspberry Pi
2. [Install Docker](https://docs.docker.com/engine/install/ubuntu/) on the server
3. [Add Navidrome to Docker Compose](https://www.navidrome.org/docs/installation/docker/)
4. [Add Tailscale to Docker Compose](https://tailscale.com/kb/1282/docker)
5. [Install and Configure Samba](https://ubuntu.com/tutorials/install-and-configure-samba#3-setting-up-samba) for file transfer as my server is headless

### Listening Instructions

Because Navidrome is developed using the [Subsonic API](https://www.navidrome.org/docs/developers/subsonic-api/), you can listen to your music files using any number of [music players](https://airsonic.github.io/docs/apps/). I am partial to [Symfonium](https://symfonium.app/).
