# gomm3
Heroes of Might and Magic 3 looking like grub2 theme! (for 1920x1080)

!(gomm3-preview)[preview.png]

# Installation

- Clone this repository
```
git clone https://github.com/clean-af/gomm3.git
```

- Copy the folder
```
cd ./gomm3
sudo cp ./gomm3 /boot/grub/themes/
```

- Add this line to `/etc/default/grub`
```
GRUB_THEME=/boot/grub/themes/gomm3/theme.txt
GRUB_BACKGROUND=/boot/grub/themes/gomm3/gomm3-assets/box_bg.png
GRUB_GFXMODE="1920x1080"
```

- Update grub config
```
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

- Astrologers proclaim week of the gomm3
