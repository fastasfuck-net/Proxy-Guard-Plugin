# FastAsFuck - Official Proxy Guard Plugin

## ✨ Overview
The **FastAsFuck Proxy Guard Plugin** is the official extension for the **FastAsFuck** DDoS protection system.  
It enhances your server's security by enforcing **proxy-only access** and enabling **secure, private IP bans** — all while ensuring that player IPs are never exposed to the server owner.

## ✨ How It Works
- Instead of banning IP addresses directly, server owners **ban the username** (e.g., `/ipban Brion`).
- The plugin **encrypts** this ban request using a secure **authentication code** from the config file.
- It then **sends** the encrypted username to the **FastAsFuck backend**.
- On the backend:
  - We **associate usernames with IP addresses** for up to **30 days**.
  - When a ban request is made, **the correct IP is banned** permanently — **without revealing it** to the server owner.
- The server owner **never knows** the IP address, maintaining **full player privacy**.

## ✨ Privacy First
At **FastAsFuck**, we prioritize **player privacy** above all else.  
Thanks to our system:
- **Server owners never see or store IP addresses**.
- **Username-IP mappings** are stored securely on the backend for a limited time (30 days).
- Once a ban is processed, **the IP is banned permanently**, and unnecessary data is securely deleted.

## ✨ Features
- **Strict proxy-only access** enforcement
- **Secure username-based banning** system
- **End-to-end encryption** for communication with the FastAsFuck backend
- **Automatic IP bans** processed on the backend, with no exposure to sensitive data
- **30-day username/IP mapping** storage, ensuring compliance with privacy standards
- **Enhanced DDoS protection** while maintaining **full player privacy**

## ✨ Installation
1. Download the latest release from the GitHub **Releases** page.
2. Place the `.jar` file into your Minecraft server’s `plugins/` directory.
3. Set your **authentication code** in the plugin's `config.yml` file.
4. Restart your server.

## ✨ Requirements
- A Minecraft server protected by the **FastAsFuck** DDoS Protection system
- A server platform that supports plugins (e.g., Paper, Purpur)

## ✨ About FastAsFuck
**FastAsFuck** provides **fast**, **reliable**, and **privacy-focused** DDoS protection for Minecraft servers.  
We safeguard your server from attacks while ensuring your players' data remains protected at all times.
