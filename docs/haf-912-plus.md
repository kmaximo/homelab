
# CoolerMaster HAF912 Plus // Mercury + Venus

Transformei meu antigo PC Gamer(que estava parado acumulando poeira) em servidor(Homelab), aproveitando
toda a capacidade computacional para rodar todos os serviços instalados. 


## Especificações

| CPU            | RAM | Storage   | OS           | Hostname |
| -------------- | --- | --------- | ------------ | -------- |
| Intel i7-3770  | 4GB | 250GB SSD | Debian 11.04 | Mercury  |
| Intel i7-3770  | 4GB | 250GB SSD | Debian 10.00 | Venus    |

## Serviços

Os serviços que estão em execução no HAF912, estão listados aqui. A lista é atualizada frequentemente.
Os serviços estaram listados junto com o hostname a qual ele pertence.


| Service Name     | Description                                     | Highly Available? | Host    |
| ---------------- | ----------------------------------------------- | ----------------- | ------  |
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

!!!info

    Anything marked as Highly Available is run in either a hot-hot or hot-cold
    setup depending on the importance of the service.

## Images

![Optiplex](https://cdn.coolermaster.com/media/assets/1021/912p_01-hover.png)
