# Some builded disk images of [xe303c12_play_linux](https://github.com/quarkscript/xe303c12_play_linux)

## Devuan 4 / Chimaera (stable) disk image
[Link to releases](https://github.com/quarkscript2/xe303c12_arm_linux/releases/tag/Devuan_Chimaera_Arm_for_Google_Snow_Chromebook)
- DE: LXQT + OPENBOX + SDDM autologin / XFCE4 + XFWM + LightDM autologin
- Disk size: 1882M
- Filesystem: btrfs
- Init: sysvinit
- External apps: thunderbird (inst-d at LXQt ver) , neovim, lite-xl, patched mesa, custom kernel.

Licenses depends of used apps, mostly it some of [GNU GPL](https://www.gnu.org/licenses/)

![](demo.jpg)

> mesa-utils and neofetch are not installed by default

> Extra instructions could be found at source repo

## Alpine disk images
[Link to releases](https://github.com/quarkscript2/xe303c12_arm_linux/releases/tag/Alpine_for_Google_Snow_Chromebook)

- DE:  LXQT + OPENBOX autologin / XFCE4 + XFWM autologin
- Filesystem: btrfs
- Kernel: 5.15.106, taken from [Void-linux musl for xe303c12](https://github.com/quarkscript/linux-armv7-xe303c12-only) (actually from gitlab mirror) re-signed with diferent init path and manually installed

## Gentoo (stage 3) disk image
[Link to release](https://github.com/quarkscript2/xe303c12_arm_linux/releases/tag/Gentoo_armv7hf_for_Google_Snow_Chromebook)

In case you want to play with Gentoo Linux on Google Snow Chromebook (XE303C12) this may be a solution for it. 
- DE: none, "stage3" console
- Disk size: 15028M
- Filesystem: btrfs
- Kernel: 5.15.102 (manually installed)
- Init: openrc
- System lib: glibc
- Login: root
- Password: q
> There is no point in compiling a new kernel during installation, unless you write your own recipe for it

> If you need hw-acceleration, the mesa sources should be downgraded to 20.3.x and [patch](https://github.com/quarkscript/linux-armv7-xe303c12-only/blob/master/archlinuxarm/some_forked_apps/mesa/gpuac.patch) applied

## OpenSUSE disk image
[Link to release](https://github.com/quarkscript2/xe303c12_arm_linux/releases/tag/Opensuse_Arm_for_Google_Snow_Chromebook)
- DE: LXQT + XFWM4 (OPENBOX) + LightDM autologin (RaspberryPi-2 ver)
- Disk size: 1882M
- Filesystem: btrfs
- Init: systemd
- System lib: glibc
- Kernel 6.3.4 extracted and flashed from [debian package](https://gitlab.com/quarkscript/linarm/-/blob/master/pkg/linux-kernel-xe303c12-6.3.4.deb)

## Debian 11 (minimal) disk image
[Link to release](https://github.com/quarkscript2/xe303c12_arm_linux/releases/tag/Debian_Arm_for_Google_Snow_Chromebook)
- DE: none, console
- Disk size: 1882M
- Filesystem: btrfs
- Init: systemd
- System lib: glibc
- Kernel 6.3.4 

Login: root 

Pass: toor
