# My Modded Minecraft Server

This repository documents the setup and configuration for a private modded Minecraft server, which has been repurposed from an old laptop. The primary goal of this project is to provide a stable, cost-effective, and secure gaming environment for a closed group of whitelisted friends, while also serving as a valuable learning experience in Linux server administration and Git version control.

## Key Features

- **Modpack:** All the Mods 10  
- **Minecraft Version:** 1.21.1  
- **Operating System:** Ubuntu Server 22.04 LTS  
- **Hardware:** Repurposed Dell Latitude E5470 laptop  
- **Optimized Performance:** Configurations tuned for efficient resource usage on older hardware.

## Included Files & Configuration

This repository tracks essential configuration files and custom scripts for the server. It does **not** include large, dynamic, or sensitive data such as:

- Minecraft world files (`world/`, `world_nether/`, `world_the_end/`)
- Log files (`logs/`, `crash-reports/`)
- Player data (`world/playerdata/`, `world/stats/`, `world/tombstone/saved_players/`, `world/skinrestorer/`)
- Mod or plugin `.jar` files
- Temporary files (`session.lock`, `usercache.json`)

**Key configurations you will find here include:**

- `server.properties`
- Mod-specific configuration files
- Custom startup or maintenance scripts

## Server Access with Playit.gg

This server utilizes the [playit.gg](https://playit.gg) service to establish a public-facing connection without the need for traditional router port forwarding. The playit.gg agent runs on the server to create a secure tunnel, making the server accessible to the internet for authorized players only.

**Minecraft Server Address:**  
209.25.143.16:1291

### Safer than Port Forwarding

Using playit.gg offers a significant security advantage over direct port forwarding. It routes your server's traffic through their cloud infrastructure, meaning your home network's public IP address and the Minecraft server's port (25565 by default) are not directly exposed to the internet. This greatly reduces the risk of targeted attacks, port scanning, or malicious activity directly against your home network.

## How to Connect

This is a private server. Only whitelisted players can connect. If you are a whitelisted player, you can connect to the server using the Minecraft Server Address provided above. Please ensure you have the correct modpack and Minecraft version installed on your client.

## Setup and Administration Notes

- Initial server setup process on Ubuntu Server  
- Steps for configuring the playit.gg agent  
- How to update mods/plugins  
- Backup strategy *(currently not implemented)*

## Credits

- Mojang for Minecraft  
- All the amazing mod and plugin developers  
- playit.gg for their tunneling service  
- My friends for testing and playing!  
- **Lakshay Gusain** - Project maintainer
