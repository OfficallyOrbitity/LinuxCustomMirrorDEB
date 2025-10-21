# LinuxCustomMirrorDEB
# 🧩 Custom .deb Repository for Debian & Ubuntu

The **Custom .deb Repository** is a self-hosted APT mirror designed to host and distribute custom-built Debian packages for **Debian** and **Ubuntu** systems.  
It allows seamless installation and updates of `.deb` packages through the standard APT system, providing an easy and reliable way to share software across multiple machines or users.

---

## 📖 Overview
This repository acts like a traditional Debian or Ubuntu mirror but only contains **custom software** that Orbitity build and maintain.  
It’s ideal for developers, system administrators, or organizations that need to deploy private packages internally or provide easy public access to their applications.

Once set up, users can add the repository to their system’s APT sources and install packages with:
```bash
sudo apt update
sudo apt install <package-name>
