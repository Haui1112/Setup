# Setup
Quick description of my Setup

The idea of my Setup is to make myself independent of a working internet connection as much as possible. The next step was the VPS, to separate myself from megacorporations as far as possible (yes, I know this platform is owned by microsoft. Please be patient). So far the newest addition is the "BerryTV" (thats how I call it since it is supposed to rid me of my apple TV). It works wonderfully as a set top box. I overdid it a lot on the ram (8 GB since I wanted to futureproof it with possible games to play over stream or something).

Feel free to contact me on matrix (@haui:matrix.giftedmc.com) or on mastodon (@haui@mastodon.giftedmc.com) if you have further questions or need help with your setup.

## Home Network
### "PiTV" 
[**RaspberryPi 4**](https://www.raspberrypi.com/), replaces appleTV

| Hardware  |                                 |
|-----------|---------------------------------|
| Processor | Quad-core ARM Cortex-A72 @ 1.5 GHz |
| RAM       | 4 GB DDR 4                     |
| Data1     | 16 GB SD Card     |

- [**LibeELEC**](https://libreelec.tv/) ([Source Code](https://github.com/LibreELEC/LibreELEC.tv/)) (lightweight OS that only houses kodi)
  - [**Kodi**](https://kodi.tv/) ([Source Code](https://github.com/xbmc/xbmc)) (media client/server with muliple purposes)
    - **Next Gen Peertube app** ([Source Code](https://github.com/Haui1112/plugin.video.pt)) (A peertube client for kodi which i built myself in lieu of a supported version.)
### Home Server 
| Hardware  |                                 |
|-----------|---------------------------------|
| Processor | Intel Xeon (4 cores, 4 threads) |
| RAM       | 16 GB DDR 3                     |
| Data1     | 2x 8 TB WD RED HDD @ Raid 1     |
| Docker    | 2x 250GB SSDs @ Raid 1          |
| Data2     | 2x 16 TB Seagate X18 @ Raid 1   |

  - [**Docker**](https://www.docker.com/) [Source Code](https://www.docker.com/community/open-source/)
    - [**Pihole**](https://pi-hole.net/) [Source Code](https://github.com/pi-hole/pi-hole) (DNS Server, Network wide Ad Block)
    - [**Plex**](https://www.plex.tv/) [Source Code]() (Replaces Disney+, Netflix, contains 100+ Archived DVDs and BDs)
      - Movies
      - TV-Shows
      - Music
      - Videos
      - Pictures
    - [**Heimdall**](https://heimdall.site/) [(Source Code)](https://github.com/linuxserver/Heimdall) (Dashboard, Replaces Google/Firefox default screen)
    - [**Nginx Proxy Manager**](https://nginxproxymanager.com/) [(Source Code)](https://github.com/NginxProxyManager/nginx-proxy-manager) (Reverse Proxy, enables SSL for all apps)
    - [**SuiteCRM**](https://suitecrm.com/) [(Source Code)](https://github.com/salesagility/SuiteCRM) (Customer relationship management software)
    - [**Portainer**](https://github.com/salesagility/SuiteCRM) [(Source Code)](https://github.com/salesagility/SuiteCRM) (Docker container management tool)
    - [**Vaultwarden**](https://www.vaultwarden.net/) [(Source Code)](https://github.com/dani-garcia/vaultwarden) (Password vault, open source version of bitwarden)
    - [**Nextcloud**](https://nextcloud.com/) [(Source Code)](https://github.com/nextcloud) (Replaces icloud, google cloud)
      - Tasks
      - Calendar
      - Pictures
      - Notes
      - Bookmarks
    - [**Home Assistant**](https://www.home-assistant.io/) [(Source Code)](https://github.com/home-assistant) (replaces amazon home, google home)
      - Heating
      - Lights
    - **Tig-Stack** (Monitoring solution, a collection of programs)
      - [**Telegraf**](https://www.influxdata.com/time-series-platform/telegraf/) [(Source Code)](https://github.com/influxdata/telegraf) (collects data from any source)
      - [**Influxdb**](https://www.influxdata.com/products/influxdb/) [(Source Code)](https://github.com/influxdata/influxdb) (fast and versatile database)
      - [**Grafana**](https://grafana.com/) [(Source Code)](https://github.com/grafana/grafana) (shows beautiful graphs)
    - [**Forgejo**](https://forgejo.org/) [(Source Code)](https://codeberg.org/forgejo/forgejo) (github alternative - federation being tested)
    - [**Dolibarr**](https://www.dolibarr.org/) [(Source Code)](https://www.github.com/dolibarr) (Probably the best FOSS ERP/CRM out there. Module based functions which makes it nimble and highly adaptable.)
## Online/Remote
### Minecraft Server (Java IP: server.gifted-minecraft.com)
  - Server Software: [**PaperMC**](https://papermc.io/) [(Source Code)](https://github.com/PaperMC)
  - [**Dynamic Map**](https://www.spigotmc.org/resources/dynmap%C2%AE.274/) [(Source Code)](https://github.com/webbukkit/dynmap)
### [Website (gifted-minecraft.com)](https://gifted-minecraft.com)
  - Links to different resources

### VPS
  - [**Docker**](https://www.docker.com/) [Source Code](https://www.docker.com/community/open-source/)
    - [**Heimdall**](https://heimdall.site/) [(Source Code)](https://github.com/linuxserver/Heimdall) (Dashboard, Replaces Google/Firefox default screen)
    - [**Nginx Proxy Manager**](https://nginxproxymanager.com/) [(Source Code)](https://github.com/NginxProxyManager/nginx-proxy-manager) (Reverse Proxy, enables SSL for all apps)
    - [**Portainer**](https://github.com/salesagility/SuiteCRM) [(Source Code)](https://github.com/salesagility/SuiteCRM) (Docker container management tool)
    - [**Mastodon**](https://joinmastodon.org/) | [**Instance**](https://mastodon.giftedmc.com) [(Source Code)](https://github.com/mastodon/mastodon) (microblogging plaform of the fediverse, replaces twitter)
    - [**Lemmy**](https://join-lemmy.org/) | [**Instance**](https://lemmy.giftedmc.com/) [(Source Code)](https://github.com/LemmyNet/lemmy) (social forum of the fediverse, replaces reddit)
    - [**Matrix**](https://matrix.org/) | [**Instance**](https://matrix.giftedmc.com/_matrix/static/) [(Source Code)](https://github.com/element-hq/synapse) (chat platform of the fediverse, replaces discord, whatsapp, telegram, signal)
    - [**Peertube**](https://joinpeertube.org/) | [**Instance**](https://peertube.giftedmc.com/) [(Source Code)](https://github.com/Chocobozzz/PeerTube) (video platform of the fediverse, replaces youtube)
    - [**nodebb**](https://nodebb.org/) | [**Instance**](https://forum.giftedmc.com/) [(Source Code)](https://github.com/NodeBB/NodeBB) (forum)
    - [**Wiki.js**](https://js.wiki/) | [**Instance**](https://wiki.giftedmc.com/) [(Source Code)](https://github.com/requarks/wiki) (wiki)
    - **Tig-Stack** (Monitoring solution, a collection of programs)
      - [**Telegraf**](https://www.influxdata.com/time-series-platform/telegraf/) [(Source Code)](https://github.com/influxdata/telegraf) (collects data from any source)
      - [**Influxdb**](https://www.influxdata.com/products/influxdb/) [(Source Code)](https://github.com/influxdata/influxdb) (fast and versatile database)
      - [**Grafana**](https://grafana.com/) [(Source Code)](https://github.com/grafana/grafana) (shows beautiful graphs)
    - Uptime Kuma [(Source Code)]() (**public**, uptime monitor)
### Cloud Backup 
