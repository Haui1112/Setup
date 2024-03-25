# Setup
Quick description of my Setup

The idea of my Setup is to make myself independent of a working internet connection as much as possible. The next step was the VPS, to separate myself from megacorporations as far as possible (yes, I know this platform is owned by microsoft. Please be patient). So far the newest addition is the "BerryTV" (thats how I call it since it is supposed to rid me of my apple TV). It works wonderfully as a set top box. I overdid it a lot on the ram (8 GB since I wanted to futureproof it with possible games to play over stream or something).

Feel free to contact me on matrix (@haui:matrix.giftedmc.com) or on mastodon (@haui@mastodon.giftedmc.com) if you have further questions or need help with your setup.

## Home Network
### "PiTV" 
[RaspberryPi](https://www.raspberrypi.com/), replaces appleTV
- [LibeELEC](https://libreelec.tv/) ([Source Code](https://github.com/LibreELEC/LibreELEC.tv/)) (lightweight OS that only houses kodi)
  - [Kodi](https://kodi.tv/) ([Source Code](https://github.com/xbmc/xbmc)) (media client/server with muliple purposes)
### Home Server 
Intel Xeon, 4 cores, 16 GB RAM, 8 TB HDD Raid 1, 2x 250GB SSDs @ Raid 1
  - Docker
    - Pihole (DNS Server, Network wide Ad Block)
    - Plex (Replaces Disney+, Netflix, 100+ Archived DVDs and BDs)
      - Movies
      - Series
    - Heimdall (Dashboard, Replaces Google/Firefox default screen)
    - Nginx Proxy Manager (Reverse Proxy, enables SSL for all apps)
    - SuiteCRM (Customer relationship management software)
    - Portainer (Docker container management tool)
    - Vaultwarden (Password vault, open source version of bitwarden)
    - Nextcloud (Replaces icloud, google cloud)
      - Tasks
      - Calendar
      - Pictures
      - Notes
      - Bookmarks
    - Home Assistant (replaces amazon home, google home)
      - Heating
      - Lights
    - Tig-Stack (Monitoring solution)
      - Telegraf (collects data from any source)
      - Influxdb (fast and versatile database)
      - Grafana (shows beautiful graphs)
## Online
- Minecraft Server (server.gifted-minecraft.com)
  - Player Analytics
  - Dynamic Map
- VPS
  - Docker
    - Heimdall
    - Nginx Proxy Manager
    - Portainer
    - Mastodon (microblogging plaform of the fediverse, replaces twitter)
    - Lemmy (social forum of the fediverse, replaces reddit)
    - Matrix (chat platform of the fediverse, replaces discord, whatsapp, telegram, signal)
    - Peertube (video platform of the fediverse, replaces youtube)
    - nodebb (forum)
    - Wiki.js (wiki)
    - Tig-Stack (monitoring)
- Cloud Backup 
