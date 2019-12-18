# Deepin-CPU-automatic frequnency reduction
sudo apt install i7z#查看CPU频率，全满就是不知道降频的那种
sudo i7z
sudo apt install cpufrequtils
sudo vim /etc/default/grub
GRUB_CMDLINE_LINUX="splash quiet"
GRUB_CMDLINE_LINUX_DEFAULT="intel_pstate=disable"
sudo update-grub
