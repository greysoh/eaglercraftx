# EaglercraftX 1.8
## Info
This repository was imported from https://gitlab.com/lax1dude/eaglercraftx-1.8, which was running on version `u4`.
### Play real Minecraft 1.8 in your browser, currently only supports multiplayer

![EaglercraftX 1.8 Screenshot Main Menu](https://g.deev.is/eaglercraft/eaglerx-480p.png)

## ATTENTION MOJANG/MICROSOFT EMPLOYEE ASSIGNED TO STALK ME:

### THIS REPOSITORY DOES NOT CONTAIN YOUR INTELLECTUAL PROPERTY

### FILING A FALSE DMCA IS ILLEGAL AND IMMORAL

### This repository contains:

 - **Utilities to decompile Minecraft 1.8 and apply patch files to it**
 - **Source code to provide the LWJGL keyboard, mouse, and OpenGL APIs in a browser**
 - **Source code for an OpenGL 1.3 emulator built on top of WebGL 2.0**
 - **Patch files to mod the Minecraft 1.8 source code to make it browser compatible**
 - **Browser-modified portions of Minecraft 1.8's open-source dependencies**
 - **Plugins for Minecraft servers to allow the eagler client to connect to them**

### This repository does NOT contain:

 - **Any portion of the decompiled Minecraft 1.8 source code or resources**
 - **Any portion of Mod Coder Pack and it's config files**
 - **Data that can be used alone to reconstruct portions of the game's source code**
 - **Code configured by default to allow users to play without owning a copy of Minecraft**

## Getting Started:

### To compile the latest version of the client, on Windows:

1. Make sure you have at least Java 11 installed and added to your PATH
2. Download (clone) this repository to your computer
3. Double click `CompileLatestClient.bat`, a GUI resembling a classic windows installer should open
4. Follow the steps shown to you in the new window to finish compiling

### To compile the latest version of the client, on Linux/macOS:

1. Make sure you have at least Java 11 installed
2. Download (clone) this repository to your computer
3. Open a terminal in the folder the repository was cloned to
4. Type `chmod +x CompileLatestClient.sh` and hit enter
5. Type `./CompileLatestClient.sh` and hit enter, a GUI resembling a classic windows installer should open
6. Follow the steps shown to you in the new window to finish compiling

## Making a Server:

**EaglercraftX 1.8's server is a BungeeCord/Waterfall PLUGIN, not an entire "fork" of bungeecord like the 1.5 Eaglerbungee was, and I can't believe I have to clarify this too but the EaglerXBungee 1.8 plugin is not compatible with the old 1.5 bungee, you must migrate to the latest version of official BungeeCord/Waterfall to use it**

Simply set up the latest version of BungeeCord or Waterfall and download [EaglerXBungee-Latest.jar](https://gitlab.com/lax1dude/eaglercraftx-1.8/-/raw/main/gateway/EaglercraftXBungee/EaglerXBungee-Latest.jar) and place it in the plugins directory.

Then to actually log in to the server with Eaglercraft, first join your server using vanilla Minecraft Java Edition 1.8 and run the new `/eagler` command to set a password. Then leave the server and switch to your EaglercraftX client. 

Set your EaglercraftX username to the same username as the vanilla minecraft account you set the password with, then when you try to join your server it will present you with a login screen where you can enter the password you set. If the password is correct it will let you join the server.

**NOTE: If you set `online_mode` to `false` on BungeeCord/Waterfall's config.yml, the password system will be disabled and you will be able to join with any username without setting a password like Eaglercraft 1.5. This should only ever be used for testing.**

A config guide will be added here too eventually

## Contributing:

This part of the guide is incomplete

## Developing a Client:

There is currently no system in place to make forks of 1.8 and merge commits made to the patch files in this repository with the patch files or workspace of the fork, you're on your own if you try to keep a fork of this repo for reasons other than to contribute to it
