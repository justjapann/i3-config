# i3-config
my i3 arch config

## Basic
- `sudo pacman -S firefox`
- `sudo pacman -S dmenu`
- `sudo pacman -S polybar`
- `sudo pacman -S rofi`
- `sudo pacman -S kitty`
- `sudo pacman -S nano`
- `sudo pacman -S neofetch`
- `sudo pacman -S pulseaudio`
- `sudo pacman -S pavucontrol`
- `sudo pacman -S pcmanfm`
- `sudo pacman -S feh`
- `sudo pacman -S flameshot`
- `sudo pacman -S git`

## Themes
- `git clone https://github.com/Kthulu120/i3wm-themes`
- `cd i3wm-themes/scripts`
- `./apply_theme.sh Water`
- `git clone https://github.com/Kthulu120/i3wm-themes](https://github.com/adi1090x/polybar-themes`
- `cd polybar-themes`
- `chmod +x setup.sh`
- `./setup.sh`
- `1`
- `bash ~/.config/polybar/launch.sh --hack`
- Add the `monitor = ${env:MONITOR:HDMI-1}` in `.config/polybar/hack/config.ini`

## Bluetooth
- `sudo pacman -S bluez bluez-utils blueman`
- `sudo pacman -S bluez bluez-utils blueman`
- `lsmod | grep btusb`
- `sudo nano /etc/bluetooth/main.conf`
- `sudo systemctl start bluetooth.service`
- `sudo systemctl enable bluetooth.service`

## Snap
- `git clone https://aur.archlinux.org/snapd.git`
- `cd snapd`
- `makepkg -si`
- `sudo systemctl enable --now snapd.socket`
- `sudo ln -s /var/lib/snapd/snap /snap`
- `reboot`

## Utilits
- `sudo snap install code --classic`
- `sudo snap install discord`
- `sudo snap install spotify`

## Terminal
- `sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
- `nano ~/.zshrc`
- insert at the end of the file: `neofetch`