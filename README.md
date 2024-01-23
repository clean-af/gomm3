# gomm3
Heroes of Might and Magic 3 looking like grub2 theme!

![]

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
```

- Update grub config
```
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

- Astrologers proclaim week of the gomm3
