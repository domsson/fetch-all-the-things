# fetch-all-the-things 

A list of scripts and programs that can fetch information and print it to `stdout`. Possible use cases for such utilities:

- Check information on the CLI
- For use in custom fetch scripts
- For use in notifications
- For use in status bars

Please open an issue or send a pull request to add to the list.

# Collections

These are projects that contain a multitude of fetch scripts / programs.

- [candies](https://github.com/domsson/candies) C programs made with status bars in mind; most of these have the option to be kept running
  - [cpu-proc](https://github.com/domsson/candies/tree/master/cpu-proc) CPU usage in %
  - [datetime](https://github.com/domsson/candies/tree/master/datetime) date and time
  - [disk-statvfs](https://github.com/domsson/candies/tree/master/disk-statvfs) disk usage in %
  - [mc-server](https://github.com/domsson/candies/tree/master/mc-server) Minecraft Server Info
  - [mem-proc](https://github.com/domsson/candies/tree/master/mem-proc) RAM usage in % via /proc/meminfo
  - [mem-sysinfo](https://github.com/domsson/candies/tree/master/mem-sysinfo) RAM usage in % via sysinfo()
  - [temp-sensors](https://github.com/domsson/candies/tree/master/temp-sensors) system temperature via libsensors
  - [twitch-chat](https://github.com/domsson/candies/tree/master/twitch-chat) Twitch chat messages (filtered)
  - [volume-pulse](https://github.com/domsson/candies/tree/master/volume-pulse) volume via libpulse
- [fetchutils](https://github.com/lptstr/fetchutils) small Shell scripts to retrieve system information; made with fetch scripts in mind
  - [disk.sh](https://github.com/lptstr/fetchutils/blob/master/src/disk.sh) disk usage
  - [editor.sh](https://github.com/lptstr/fetchutils/blob/master/src/editor.sh) get editor name
  - [mem.sh](https://github.com/lptstr/fetchutils/blob/master/src/mem.sh) RAM usage
  - [os.sh](https://github.com/lptstr/fetchutils/blob/master/src/os.sh) operating system
  - [pkgs.sh](https://github.com/lptstr/fetchutils/blob/master/src/pkgs.sh) number of packages
  - [res.sh](https://github.com/lptstr/fetchutils/blob/master/src/res.sh) screen dimensions
  - [cpu.sh](https://github.com/lptstr/fetchutils/blob/master/src/temp.sh) CPU temperature
  - [upt.sh](https://github.com/lptstr/fetchutils/blob/master/src/upt.sh) uptime
  - [wm.sh](https://github.com/lptstr/fetchutils/blob/master/src/wm.sh) window manager
- [i3blocks-contrib](https://github.com/vivien/i3blocks-contrib) mostly Shell and Python scripts; made with i3blocks in mind
  - [afs](https://github.com/vivien/i3blocks-contrib/tree/master/afs) AFS directory usage
  - [apt-upgrades](https://github.com/vivien/i3blocks-contrib/tree/master/apt-upgrades) pending aptitude upgrades
  - [aur-update](https://github.com/vivien/i3blocks-contrib/tree/master/arch-update) AUR updates
  - [backlight](https://github.com/vivien/i3blocks-contrib/tree/master/backlight) screen brightness
  - [bandwidth](https://github.com/vivien/i3blocks-contrib/tree/master/bandwidth) bandwidth information
  - [bandwidth2](https://github.com/vivien/i3blocks-contrib/tree/master/bandwidth2) bandwidth usage (written in C)
  - [bandwidth3](https://github.com/vivien/i3blocks-contrib/tree/master/bandwidth3) bandwidth usage
  - [battery-poly](https://github.com/vivien/i3blocks-contrib/tree/master/battery-poly) battery info
  - [battery](https://github.com/vivien/i3blocks-contrib/tree/master/battery) battery info
  - [battery2](https://github.com/vivien/i3blocks-contrib/tree/master/battery2) battery info
  - [batterybar](https://github.com/vivien/i3blocks-contrib/tree/master/batterybar) battery level in squares
  - [calendar](https://github.com/vivien/i3blocks-contrib/tree/master/calendar) current date and time
  - [cpu\_usage](https://github.com/vivien/i3blocks-contrib/tree/master/cpu_usage) CPU usage
  - [cpu\_usage2](https://github.com/vivien/i3blocks-contrib/tree/master/cpu_usage2) CPU usage (written in C)
  - [cpu\_util\_detailed](https://github.com/vivien/i3blocks-contrib/tree/master/cpu_util_detailed) CPU utilization
  - [disk\_io](https://github.com/vivien/i3blocks-contrib/tree/master/disk-io) disk reads/writes
  - [disk](https://github.com/vivien/i3blocks-contrib/tree/master/disk) disk usage
  - [docker](https://github.com/vivien/i3blocks-contrib/tree/master/docker) number of running Docker containers
  - [email](https://github.com/vivien/i3blocks-contrib/tree/master/email) number of new emails via IMAP
  - [essid](https://github.com/vivien/i3blocks-contrib/tree/master/essid) wifi ESSID
  - [go](https://github.com/vivien/i3blocks-contrib/tree/master/go) installed Go version
  - [gpu-load](https://github.com/vivien/i3blocks-contrib/tree/master/gpu-load) nVidia GPU load
  - [iface](https://github.com/vivien/i3blocks-contrib/tree/master/iface) network interface status
  - [kbdd\_layout](https://github.com/vivien/i3blocks-contrib/tree/master/kbdd_layout) keyboard layout via dbus and kbdd
  - [key\_layout](https://github.com/vivien/i3blocks-contrib/tree/master/key_layout) keyboard layout via setxkbmap
  - [keyindicator](https://github.com/vivien/i3blocks-contrib/tree/master/keyindicator) capslock / numlock status indicator
  - [kubernetes](https://github.com/vivien/i3blocks-contrib/tree/master/kubernetes) current Kubernetes context and namespace
  - [load\_average](https://github.com/vivien/i3blocks-contrib/tree/master/load_average) system load average
  - [mediaplayer](https://github.com/vivien/i3blocks-contrib/tree/master/mediaplayer) generic media player status
  - [memory](https://github.com/vivien/i3blocks-contrib/tree/master/memory) RAM usage
  - [nm-vpn](https://github.com/vivien/i3blocks-contrib/tree/master/nm-vpn) VPN status/name via nmcli
  - [openvpn](https://github.com/vivien/i3blocks-contrib/tree/master/openvpn) OpenVPN
  - [ssid](https://github.com/vivien/i3blocks-contrib/tree/master/ssid) wifi SSID
  - [sway-focusedwindow](https://github.com/vivien/i3blocks-contrib/tree/master/sway-focusedwindow) Sway WM focused window title
  - [systemd\_unit](https://github.com/vivien/i3blocks-contrib/tree/master/systemd_unit) systemd unit status
  - [tahoe-lafs](https://github.com/vivien/i3blocks-contrib/tree/master/tahoe-lafs) tahoe-lafs grid status
  - [temperature](https://github.com/vivien/i3blocks-contrib/tree/master/temperature) system temperatures
  - [time](https://github.com/vivien/i3blocks-contrib/tree/master/time) current time
  - [usb](https://github.com/vivien/i3blocks-contrib/tree/master/usb) USB device info
  - [volume-pulseaudio](https://github.com/vivien/i3blocks-contrib/tree/master/volume-pulseaudio) system volume and default playback device
  - [volume](https://github.com/vivien/i3blocks-contrib/tree/master/volume) system volume
  - [wifi](https://github.com/vivien/i3blocks-contrib/tree/master/wifi) wifi connection strength
  - [wlan-dbm](https://github.com/vivien/i3blocks-contrib/tree/master/wlan-dbm) wifi interface link quality in dBm or percent
  - [xkb\_layout](https://github.com/vivien/i3blocks-contrib/tree/master/xkb_layout) keyboard layout
- [polybar-scripts](https://github.com/polybar/polybar-scripts) Shell and Python scripts; written with polybar in mind
  - [battery-combined-shell](https://github.com/polybar/polybar-scripts/tree/master/polybar-scripts/battery-combined-shell) battery status
  - [battery-combined-tlp](https://github.com/polybar/polybar-scripts/tree/master/polybar-scripts/battery-combined-tlp) battery status via TLP
  - [battery-combined-udev](https://github.com/polybar/polybar-scripts/tree/master/polybar-scripts/battery-combined-udev) battery status via udev
  - [battery-cyberpower](https://github.com/polybar/polybar-scripts/tree/master/polybar-scripts/battery-cyberpower) battery status for CyberPower UPS devices
  - [inbox-imap-pythonpgp](https://github.com/polybar/polybar-scripts/tree/master/polybar-scripts/inbox-imap-pythongpg) shows if there are unread mails in your IMAPs inbox
  - [inbox-imap-shellnetrc](https://github.com/polybar/polybar-scripts/tree/master/polybar-scripts/inbox-imap-shellnetrc) shows if there are unread mails in your IMAP inbox
  - [inbox-imap-shellpass](https://github.com/polybar/polybar-scripts/tree/master/polybar-scripts/inbox-imap-shellpass) shows if there are unread mails in your IMAP inbox
  - [inbox-pop3-shellnetrc](https://github.com/polybar/polybar-scripts/tree/master/polybar-scripts/inbox-pop3-shellnetrc) shows if there are unread mails in your POP3 inbox
  - [info-airqualityindex](https://github.com/polybar/polybar-scripts/tree/master/polybar-scripts/info-airqualityindex) local World Air Quality Index
  - [info-docker](https://github.com/polybar/polybar-scripts/tree/master/polybar-scripts/info-docker) number of docker containers in a certain state
  - [info-dualshock4](https://github.com/polybar/polybar-scripts/tree/master/polybar-scripts/info-dualshock4) battery level of a DualShock 4 Controller
  - [info-ethermine](https://github.com/polybar/polybar-scripts/tree/master/polybar-scripts/info-ethermine) current hashrate (in MH/s) for your ethermine account
  - [info-eyestrain](https://github.com/polybar/polybar-scripts/tree/master/polybar-scripts/info-eyestrain) eyestrain break indicator according to 20-20-20 rule
  - ... and many more (todo)

## Invidiual projects

These are projects that contain only one fetch script or program, focusing on a particular piece of information.

- [xtmon](https://github.com/vimist/xtmon) X window title monitoring (C)
- [pavolmon](https://github.com/everard/pavolmon) PulseAudio volume monitoring (C)
- [xkblayout-state](https://github.com/nonpop/xkblayout-state) XKB keyboard layout (C++)
- [light](https://github.com/haikarainen/light) get and set backlights (C)
- [brightnessctl](https://github.com/Hummer12007/brightnessctl) get and set device brightness (C)
- [ansiweather](https://github.com/fcambus/ansiweather) Shell script for weather conditions

# Buried in code

These are projects that _contain_ scripts or pieces of code that can collect information, but aren't necessarily available as individual programs. It should still be possible to extract the relevant pieces of code, or at least use them as reference / inspiration.

- [slstatus](https://github.com/drkhsh/slstatus) status monitor written in C; individual components in separate C files
  - [battery.c](https://github.com/drkhsh/slstatus/blob/master/components/battery.c) battery percentage/state/time left
  - [cpu.c](https://github.com/drkhsh/slstatus/blob/master/components/cpu.c) CPU usage / frequency
  - [datetime.c](https://github.com/drkhsh/slstatus/blob/master/components/datetime.c) date and time
  - [disk.c](https://github.com/drkhsh/slstatus/blob/master/components/disk.c) disk status (free storage, percentage, total storage and used storage)
  - [entropy.c](https://github.com/drkhsh/slstatus/blob/master/components/entropy.c) available entropy
  - [user.c](https://github.com/drkhsh/slstatus/blob/master/components/user.c) username/GID/UID
  - [hostname.c](https://github.com/drkhsh/slstatus/blob/master/components/hostname.c) hostname
  - [ip.c](https://github.com/drkhsh/slstatus/blob/master/components/ip.c) IP address (IPv4 and IPv6)
  - [kernel\_release.c](https://github.com/drkhsh/slstatus/blob/master/components/kernel_release.c) Kernel version
  - [keyboard\_indicators.c](https://github.com/drkhsh/slstatus/blob/master/components/keyboard_indicators.c) keyboard indicators
  - [keymap.c](https://github.com/drkhsh/slstatus/blob/master/components/keymap.c) keymap
  - [load\_avg.c](https://github.com/drkhsh/slstatus/blob/master/components/load_avg.c) load average
  - [netspeeds.c](https://github.com/drkhsh/slstatus/blob/master/components/netspeeds.c) network speeds (RX and TX)
  - [num\_files.c](https://github.com/drkhsh/slstatus/blob/master/components/num_files.c) number of files in a directory
  - [ram.c](https://github.com/drkhsh/slstatus/blob/master/components/ram.c) Memory status (free memory, percentage, total memory and used memory)
  - [run\_command.c](https://github.com/drkhsh/slstatus/blob/master/components/run_command.c) custom shell commands
  - [swap.c](https://github.com/drkhsh/slstatus/blob/master/components/swap.c) swap status (free swap, percentage, total swap and used swap)
  - [temperature.c](https://github.com/drkhsh/slstatus/blob/master/components/temperature.c) temperature
  - [uptime.c](https://github.com/drkhsh/slstatus/blob/master/components/uptime.c) uptime
  - [volume.c](https://github.com/drkhsh/slstatus/blob/master/components/volume.c) volume percentage (OSS/ALSA)
  - [wifi.c](https://github.com/drkhsh/slstatus/blob/master/components/wifi.c) WiFi signal percentage and ESSID

## Services

These aren't actual programs, but online services that can be queried from scripts, programs or the command line, for example via `curl`, to obtain information.

See [awesome-console-services](https://github.com/chubin/awesome-console-services)
