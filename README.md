# Deepin-CPU-automatic frequnency reduction
```
sudo apt install i7z#check CPU frequency
sudo i7z
sudo apt install cpufrequtils
sudo vim /etc/default/grub
GRUB_CMDLINE_LINUX="splash quiet"
GRUB_CMDLINE_LINUX_DEFAULT="intel_pstate=disable"
sudo update-grub
```
