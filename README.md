<h1 align="center">
  
Homelab

  ![Unraid](https://img.shields.io/badge/unraid-%23F15A2C.svg?style=for-the-badge&logo=unraid&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

</h1>

## Homepage

![Homepage](homepage.png)

## Description

I purchased an old office PC to use as a Homelab setup with the main purpose of reducing costs associated with common digital services like Google Photos, iCloud, or Spotify. Along the way, it has also helped me solidify my knowledge in DevOps, network administration, and IT deployment.

I would say this project will never be truly complete, as there is always something I want to change, whether it's the storage size or the implementation of more Docker services.

One of my plans is to implement a larger storage size, hopefully enabling me to store Blu-Ray-sized movies and stream them over the internet. I also hope to host a Minecraft server for friends to play on.

UNRAID is not a safe operating system in terms of an enterprise environment, primarily because everything you run operates mostly as root. It's great for home use as it gets things running quickly. However, if I had to run virtualization in an enterprise setting, I would use Proxmox or ESXi as they are much more secure and reliable.

## Hosted services

+ [Trillium](https://github.com/zadam/trilium) - A knowledge database, offering a good alternative to common services such as Notion, Evernote, etc.
+ [Calibre Web](https://github.com/janeczku/calibre-web) - A book media server where I keep all my ebooks accessible from anywhere. I use it to send ebooks to my Kindle.
+ [Immich](https://github.com/immich-app/immich) - A Google Photos alternative that features things such as facial recognition, which uses machine learning for facial recognition.
+ [Navidrome](https://github.com/navidrome/navidrome) - A music media server where I keep all my ripped music. It is accessible from anywhere, and I can also allow my music to cache on my phone so I can access it when I am not connected.
+ [Vaultwarden](https://github.com/dani-garcia/vaultwarden) - A password manager, which is a fork of Bitwarden. It's great as a privacy alternative, allowing me to keep sensitive information offsite.
+ [Bookstack](https://github.com/BookStackApp/BookStack) - This is where I keep sensitive information about the server. I do not expose this service, and it can only be accessed from the LAN.
+ [Pi Hole](https://github.com/pi-hole/pi-hole) - A DNS server that also serves as an ad blocker for my home network.
+ [Red-Discordbot](https://github.com/Cog-Creators/Red-DiscordBot) - I use this to play music on my Discord servers. Previously, there were public music bots like Groovy or Hydra that allowed you to play music on Discord servers. However, due to copyright reasons, they had to be taken down. I now choose to run a private music bot, which is only available for personal use.
+ [Nginx](https://nginx.org/) - This is a web server, i use this run my personal [website](https://qltcloud.com/).

## Hardware

Dell Precision 3420:
- CPU: i5-6500
- RAM: ECC DDR4-2133 16 GB x 4
- Motherboard:  Intel C236 chipset
- Storage (Parity Drive): 4 TB Western Digital WD4000FYYZ
- Storage (Primary Drive): 2 TB Patriot P210

# Reference
+ [awesome-selfhosted/awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) - A list of Free Software network services and web applications which can be hosted on your own servers.
+ [UNRAID](https://https://unraid.net/) - Operating system i use to run the services i use.
