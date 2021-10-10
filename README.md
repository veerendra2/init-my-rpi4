![GitHub](https://img.shields.io/badge/OS-Ubuntu%2020.04.3%20LTS-green)
![GitHub](https://img.shields.io/badge/Arch-arm64-green)
# Init My RPi4
A collection of tools to make RPi4 more powerful home server/router. 

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
| DuckDNS                                           | :heavy_check_mark:       |        |
| Home Assistant                                    | :heavy_multiplication_x: |        |