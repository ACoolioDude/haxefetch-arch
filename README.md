# Official Arch Linux repo for Haxefetch

## How to install this?

1. Add repo into `/etc/pacman.conf`
`[haxefetch] SigLevel = Optional TrustAll Server = https://acooliodude.github.io/haxefetch-arch/x86_64`

2. Refresh Arch repos
`pacman -Syu`

3. Install Haxefetch
`pacman -S haxefetch`