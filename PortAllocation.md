# Port Allocations

Here are the Port Allocations per Container Stack

| Platform                                              | Stack                                | Web UI Ports | Other Ports              |
|-------------------------------------------------------|--------------------------------------|--------------|--------------------------|
| Adguard Home                                          | docker-compose-adguardhome-host.yml  | 3000 *       | 53, 67, 853, 5443, 6060  |
| Ciao                                                  | docker-compose-ciao.yml              | 3001         |                          |
| Dozzle                                                | docker-compose-dozzle.yml            | 3002         |                          |
| Gitea                                                 | docker-compose-gitea.yml             | 3003         | 5432                     |
| Gotify                                                | docker-compose-gotify.yml            | 3004         |                          |
| Homepage                                              | docker-compose-homepage.yml          | 3005         |                          |
| Minecraft Bedrock Server                              | docker-compose-minecraft-bedrock.yml | n/a          | 19132                    |
| NGINX Proxy Manager                                   | docker-compose-nginx.yml             | 80, 81, 443  |                          |
| Open VS Code                                          | docker-compose-openvscode.yml        | 3006         |                          |
| Pi-Hole Bridge Network                                | docker-compose-pihole.yml            | 3007         | 53, 67, 5300             |
| Pi-Hole DHCP                                          | docker-compose-pihole-dhcp.yml       | 3007         | 53, 67, 5300             |
| Pi-Hole Host Network                                  | docker-compose-pihole-host.yml       | 3007 *       |                          |
| Pi-Hole v6 Bridge Network                             | docker-compose-pihole-v6.yml         | 3008         | 53, 67, 5300             |
| Pi-Hole v6 DHCP                                       | docker-compose-pihole-v6-dhcp.yml    | 3008         | 53, 67, 5300             |
| Pi-Hole v6 Host Network                               | docker-compose-pihole-v6-host.yml    | 3008 *       |                          |
| Portainer                                             | docker-compose-portainer.yml         | 3009, 9443   |                          |
| Statping NG                                           | docker-compose-statping.yml          | 3010         |                          |
| Unbound                                               | docker-compose-unbound.yml           | n/a          |                          |
| Vaultwarden                                           | docker-compose-vaultwarden.yml       | 3011         |                          |
| Watchtower                                            | docker-compose-watchtower.yml        | n/a          |                          |
| Yacht                                                 | docker-compose-yacht.yml             | 3012         |                          |
| Gogs Git Version Control                              | docker-compose-gogs.yml              | 3013         | 10022, 5432              |             
| Youtube Downloader                                    | docker-compose-youtubedl.yml         | 3014         |                          |
| PostgreSQL                                            | docker-compose-postgres.yml          |              | 5432                     |
| Neo4J                                                 | docker-compose-neo4j.yml             | 7474         | 7687                     |
| Homeassistant                                         | docker-compose-homeassistant.yml     | 8123 *       |                          |
| Glances                                               | docker-compose-glances.yml           | 61208, 61209 |                          |      

\* 
Note: Specified by configuration not orchestration

