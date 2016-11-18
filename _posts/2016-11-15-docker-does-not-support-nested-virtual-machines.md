---
published: true
title: Docker for Windows
layout: post
---
I was trying to play with Docker for Windows. I can faithfully say that trying to use docker in a Windows 10 VM using VirtualBox on OSX does not work. You cannot nest Hyper-V vm's inside VirtualBox. I was somewhat successful with VMWare Syncfusion, but it was painfully slow. However you can run Windows Server 2016 Containers on a VM (using VirtualBox) and then run the docker client from OSX with the DOCKER_HOST environment variable set.