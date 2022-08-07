# CoolerMaster HAF912 Plus // Mercury + Venus

These small servers are perfect for an ITX sized homelab. They provide enough computing power for most tasks
and combined have 16GB of RAM. These servers were the first of my actual hardware I bought.

## Specifications

| CPU            | RAM | Storage   | OS           | Hostname |
| -------------- | --- | --------- | ------------ | -------- |
| Intel i5-6500T | 4GB | 250GB SSD | Debian 11.04 | Mercury  |
| Intel i5-6500T | 4GB | 250GB SSD | Debian 10.00 | Venus    |

## Services

The services running on the Dell OptiPlexes are listed here. This list is updated frequently.

As my HomeLab has two quite similar Dell OptiPlexes, it can run many services in a hot-hot/hot-cold format.
When listing what services are running, the hostname will be listed beside it.

| Service Name     | Description                                     | Highly Available? | Host   |
| ---------------- | ----------------------------------------------- | ----------------- | ------ |
| Postgres         | Database                                        |                   | Mercury |
| Heimdall         | Application Dashboard                           |                   | Mercury |
| Jellyfin         | Media Server                                    |                   | Mercury |
| Plex             | Media Server                                    |                   | Mercury |
| Tautulli         | Plex Stats and Monitoring                       |                   | Mercury |
| Dozzle           | Real-time Docker Log Viewer                     |                   | Mercury |
| File Browser     | Home Automation Software                        |                   | Mercury |
| Docker-GC        | Automatic Docker Garbage Collection             |                   | Mercury |
| WatchTower       | Automatic Docker Container Updates              |                   | Mercury |
| Uptime Kuma      | Status Page & Monitoring Server                 |                   | Mercury |
| VSCode           | VSCode Editing                                  |                   | Mercury |
| OpenVPN          | VPN for connecting to Homelab from the internet |                   | Zeus   |

!!!info

    Anything marked as Highly Available is run in either a hot-hot or hot-cold
    setup depending on the importance of the service.

## Images

![Optiplex](https://i.dbyte.xyz/2021-07-Iv.jpg)
![Optiplex](https://i.dbyte.xyz/2021-07-EX.jpg)
![Optiplex](https://i.dbyte.xyz/2021-07-00.jpg)
