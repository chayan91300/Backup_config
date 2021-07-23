# Réparer GRUB

## Pour avoir le nom du disque windows

```Bash
lsblk
```

## Installation de grub sur le disque Windows

```Bash
sudo apt install grub-pc

sudo grub-install /dev/sdX (sda) 232G
```

## Mise à jour et reboot

```Bash
sudo update-grub2

sudo reboot
```
