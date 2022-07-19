![GitHub](https://img.shields.io/badge/Ubuntu%2022.04%20LTS-green)
![GitHub](https://img.shields.io/badge/Arch-arm64-green)
# Init My RPi4
A collection of tools to make RPi4 awesome home server. 

![image](https://user-images.githubusercontent.com/8393701/139601021-2884d09e-b8e7-47eb-8a93-66e5047a36b0.png)

## Run
```
$ git clone https://github.com/veerendra2/init-my-rpi4.git
$ cd init-my-rpi4
## Update inventory file
$ ansible-playbook -i inventory.yml main.yml
```
## Current Status
Kanban Broards for this projects
* [RPi Utils](https://github.com/veerendra2/init-my-rpi4/projects/1)
  
  This projects aims to install necessary packages and setup home server/router
* [Evil Pi](https://github.com/veerendra2/init-my-rpi4/projects/2)
  
  This project aims to make RPi4 as a hacking tool kit

| Components                                        | Status                   | Remark |
| ------------------------------------------------- | ------------------------ | ------ |
| Necessary Packages                                | :heavy_check_mark:       |        |
| Prometheus + Grafana to monitor RPi4 and Internet | :heavy_check_mark:       |        |
| Nginx reverse proxy config for containers         | :heavy_check_mark:       |        |
| File Browser                                      | :heavy_check_mark:       |        |
| Pihole                                            | :heavy_multiplication_x: |        |
| OpenWRT                                           | :heavy_multiplication_x: |        |
| DuckDNS                                           | :heavy_multiplication_x: |        |
| Home Assistant                                    | :heavy_multiplication_x: |        |
| Bittorrent with Tor                               | :heavy_multiplication_x: |        |
| Next Cloud                                        | :heavy_multiplication_x: |        |


## Shoutout :thumbsup:
| Components                  | Project                                                                                         |
| --------------------------- | ----------------------------------------------------------------------------------------------- |
| Home Page                   | [bastienwirtz/homer](https://github.com/bastienwirtz/homer)                                     |
| Web File Browser            | [filebrowser/filebrowser](https://github.com/filebrowser/filebrowser)                           |
| NordVPN in Docker           | [bubuntux/nordvpn](https://github.com/bubuntux/nordvpn)                                         |
| Internet Speedtest Exporter | [MiguelNdeCarvalho/speedtest-exporter](https://github.com/MiguelNdeCarvalho/speedtest-exporter) |
| PiHole                      | [pi-hole/pi-hole](https://github.com/pi-hole/pi-hole)                                           |
| Prometheus + Grafana        | [stefanprodan/dockprom](https://github.com/stefanprodan/dockprom)                               |
| Internet Pi                 | [geerlingguy/internet-pi](https://github.com/geerlingguy/internet-pi)                           |
| OpenWRT in Docker           | [oofnikj/docker-openwrt](https://github.com/oofnikj/docker-openwrt)                             |