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
