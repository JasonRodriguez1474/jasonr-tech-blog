---
title: Inovato Quadra
description: Discussing my latest power efficient homelab addition
slug: inovato-quadra
date: 2022-10-16 00:00:00+0000
image: inovato-images-4.jpg
categories:
    - server-hardware
tags:
    - server
    - 3d-printing
    - low-power
---
## First Impressions:
Recently, I purchased an inovata quadra for an [octoprint](https://octoprint.org/) server. I had planned on using a RaspberryPi, but stock was nonexistent. I found inovato thanks to a recommendation from the [3d printing subreddit](https://www.reddit.com/r/3Dprinting/). Comparable performance to a Raspberry Pi 3, CPU max TDP 4W, and comes preloaded with Debian? Needless to say I gave it a shot!

I've included pictures to give a sense of the scale and I'm blown away by the punch it packs! The inovato QUADRA scored a [363 multi-core score in Geekbench 5](https://browser.geekbench.com/v5/cpu/17700617). Roughly 29% higher when compared to an [Oracle Cloud E2.1.Micro instance](https://browser.geekbench.com/v5/cpu/17742735). 

## Alternatives:
That Oracle Cloud E2.1 Micro instance I mentioned earlier? That's included in the [Oracle Cloud Always Free tier](https://www.oracle.com/cloud/free/), so if cost is the #1 factor, that'll win almost any comparison. It includes a public IP, and makes more sense if you want to deploy and bring down the server with Terraform. If you need a server for remote development, learning Linux, or serving a website the cloud is very appealing. 

## Strengths:
However, the inovato fills a niche for tasks that need to be completed on-site. Oracle Cloud VPS are incredible, but physically plugging one into my 3D printer for octoprint would be impossible. A few other use cases I can think of where the inovato QUADRA wins are listed below. 

*   Cheap Linux Desktop
*   Local Print Server
*   Local Plex/Kodi/Emby Server
*   Smart Mirror
*   Network Monitoring
*   Webcam stream with mjpg_streamer


![inovato QUADRA side by side with coaster](inovato-images-8.jpg)
![inovato QUADRA packaging](inovato-images-9.jpg)

For more information about this theme, check the documentation: https://docs.stack.jimmycai.com/

Want a site like this? Check out [hugo-theme-stack-stater](https://github.com/CaiJimmy/hugo-theme-stack-starter)

> Product belongs entirely to [Inovato LLC](https://www.inovato.com/)

> All other images on this post were taken by Jason R