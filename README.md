## Installation

```bash
git clone https://github.com/rhino-linux/grub.git rhino-grub
sudo mkdir -p /usr/share/grub/themes/rhino
sudo cp -r rhino-grub/* /usr/share/grub/themes/rhino
```

Then, add this line to `/etc/default/grub`:
```
GRUB_THEME=/usr/share/grub/themes/rhino/theme.txt
```

And finally run `sudo update-grub`.
