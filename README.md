# What can I do with this ?

Apart of pihole, each of these services is a part for a completely automated media center. 

In theory, when all is set up, you just have to choose your favourite serie and the media center will download, process, rename, sort and make it ready for you to watch it !

> You have to modify `docker-compose.yml` with PATH to locate your files.

If you don't need pihole, that's not a problem, you can delete line `89->108`.

# Services
## Pihole
https://docs.pi-hole.net/

WEBui available on port `80`
## Plex
https://www.plex.tv/

WEBui available on port `32400`, you might need to search for `http://$IP:32400/web` URL depending on your browser.
## Sonarr
https://sonarr.tv/

WEBui available on port `8989`
## Radarr
https://radarr.video/

WEBui available on port `7878`
## Prowlarr
https://github.com/Prowlarr/Prowlarr

WEBui available on port `9696`
## qBittorrent
WEBui available on port `8080`


## Flaresolverr
https://github.com/FlareSolverr/FlareSolverr

API availabe on port `8191`
# Pre-requisites


Docker (and docker-compose)

https://www.docker.com/

# Setup

These lines must be modified in order for everything to work correctly, it's mainly path to directories where Docker will save config files, tv shows, movies, ... :

- line `7->11`

- line `24->26`

- line `40->42`

- line `69`

- line `82-83`

- line `103 - 105`

> For Sonarr, Radarr and qBittorrent, path to torrents must be the same !
