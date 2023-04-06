---
title: Ubuntu Server
layout: default
parent: VM Installation and Configuration
has_toc: false
---

# Installing Ubuntu
{: .no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Initial Setup
- Configure your language and keyboard as appropriate
![install](imgs/ubuntu_steps/install.png)
![install](imgs/ubuntu_steps/keyboard.png)

## Storage
- Make sure to Turn off LVM!
- Again, **UNCHECK** "Setup this disk as an LVM group"
![lvm_no](imgs/ubuntu_steps/disk.png)
- You will probably want to use your entire disk. This is your entire *virtual* disk, not the disk on your host machine. Y
- It will prompt you if you want to wipe all data on your disk. This is fine (unless you're installing outside of a virtual machine)
![urfine](imgs/ubuntu_steps/del.png)
- press "Yes" or "ok" a bunch

## Software
- Check the "Install openssh server" option
![easy ssh](imgs/ubuntu_steps/ssh.png)
- When it asks if you want to install any snaps, just press "Done". 
![snap sucks](imgs/ubuntu_steps/snap_cringe.png)

## Account Info
- Setup a username and password. These can be anything you want
- You will need to remember your password
- You can set the server name to anything you want
![username](imgs/ubuntu_steps/uname.png)

## Finishing touches
- press "yes" some more