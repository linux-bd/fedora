## Remove Old Kernels
```sh
rpm -q kernel-core
sudo dnf remove kernel-core-5.11.12-300.fc34.x86_64
sudo grub2-mkconfig -o /boot/grub2/grub.cfg
sudo reboot now
```
