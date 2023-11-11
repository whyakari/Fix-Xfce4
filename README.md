# Xfce4
> Install xfce using termux and proot-distro or chroot unshare

### xfce4 (Manjaro/Arch Only users)
> **a fix for proot-distro/chroot_unshare for termux users.**
```sh
pacman -S wget unzip --noconfirm; wget https://github.com/whyakari/Fix-Xfce4/releases/download/Arch%2FManjaro/fixInstallXfce.zip; unzip fixInstallXfce.zip; chmod +x tigervnc-fix.sh xfce4_de.sh; ./xfce4_de.sh && ./tigervnc-fix.sh; clear; rm xfce4_de.sh tigervnc-fix.sh fixInstallXfce.zip;
```
---

### xfce4 (Ubuntu v22 Only users)
> **a fix for proot-distro/chroot_unshare for termux users.**
```
 wget https://github.com/whyakari/Fix-Xfce4/releases/download/Ubuntu/xfce4-ubuntu22.zip
```
