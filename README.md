# What can I do with this ?

Apart of pihole, each of these services is a part for a completely automated media center. 

In theory, when all is set up, you just have to choose your favourite serie and the media center will download, process, rename, sort and make it ready to go !

> You have to modify `docker-compose.yml` with PATH to locate your files.

If you don't need pihole, that's not a problem, you can delete line `89->108`.

# Services
## Pihole
https://docs.pi-hole.net/
## Plex
https://www.plex.tv/
## Sonarr
https://sonarr.tv/
## Radarr
https://radarr.video/
## Prowlarr
https://github.com/Prowlarr/Prowlarr
## qBittorrent
https://www.qbittorrent.org/




#Pre-requisites


Docker and docker-compose



# Setup

These lines must be modified in order for everything to work correctly, it's mainly path to directories where Docker will save config files, tv shows, movies, ... :

- line `7->11`

- line `24->26`

- line `40->42`

- line `69`

- line `82-83`

- line `7->11`

- line `103 - 105`
