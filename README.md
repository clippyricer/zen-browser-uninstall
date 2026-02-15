## Zen Browser Uninstall Script
**This script will fully uninstall zen browser and delete all data**

For some reason when installing zen browser from the `install.sh` script</br>
Zen Browser dosen't have a offical uninstall method</br>
So I made this simple uninstall script

### How to use
1. Run the `uninstall.sh` script with
```bash
$ bash uninstall.sh
```
2. Reboot to see changes
3. Your done!

### What this script does
Table of files/dirs the script delets

| File/Dir |
| -------- |
| ~/.tarball-installations/zen* |
| ~/.zen/ |
| ~/.local/bin/zen* |
| ~/.local/share/applications/zen* |
| ~/.config/zen/ |
| ~/.cache/zen/ |
