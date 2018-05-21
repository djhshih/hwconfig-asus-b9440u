# Inputs
1. Edit `.xinitrc` to source `setup/mouse/setup.up` and `setup/keyboard/setup.up`.
2. `startx`

# Wifi
1. Install `netctl` package.
2. Update wifi profiles in `netctl/` with proper SSID and authentication settings.
3. Copy profiles in `netctl/` to `/etc/netctl/`.
4. Update SSID in scripts in `setup/wifi`.
5. Call a script in `setup/wifi`.
