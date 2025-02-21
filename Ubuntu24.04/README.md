[![Join our Telegram RU](https://img.shields.io/badge/Telegram-RU-03A500?style=for-the-badge&logo=telegram&logoColor=white&labelColor=blue&color=red)](https://t.me/hidden_coding)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aero25x)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=x&logoColor=white)](https://x.com/aero25x)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@flaming_chameleon)
[![Reddit](https://img.shields.io/badge/Reddit-FF3A00?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/r/HiddenCode/)
[![Join our Telegram ENG](https://img.shields.io/badge/Telegram-EN-03A500?style=for-the-badge&logo=telegram&logoColor=white&labelColor=blue&color=red)](https://t.me/hidden_coding_en)



autoinstall config file for Ubuntu 24.04 for ease and fast installtation wthour manual work

Place `autoinstall.yaml` into root folder for installation and update `grub.cfg` in /boot/grub/grub.cfg

```
├───[boot]
├───.disk
├───boot
│   └───grub
│       ├───fonts
│       ├───i386-pc
│       ├───x86_64-efi
        └───grub.cfg
├───casper
├───dists
│   └───noble
│       ├───main
│       │   ├───binary-amd64
│       │   ├───binary-i386
│       │   └───source
│       └───restricted
│           ├───binary-amd64
│           ├───binary-i386
│           └───source
├───EFI
│   └───boot
├───install
│
├───autoinstall.yaml
```
