---
title: NumLock
nav_order: 8010
has_children: false
parent: Howto
---


# NumLock

## Link

* Arch Wiki / [Activating numlock on bootup](https://wiki.archlinux.org/title/Activating_numlock_on_bootup)
* Ubuntu Help / [NumLock](https://help.ubuntu.com/community/NumLock)


## Explore

run

``` sh
pamac search numlock
```

show

```
numlockx                                                                   [Installed] 1.2-5  community
    Turns on the numlock key in X11.
```


run

``` sh
pacman -Ql numlockx
```

show

```
numlockx /usr/
numlockx /usr/bin/
numlockx /usr/bin/numlockx
numlockx /usr/share/
numlockx /usr/share/licenses/
numlockx /usr/share/licenses/numlockx/
numlockx /usr/share/licenses/numlockx/LICENSE
```


## KDE

### GUI

> System Settings / Input Devices / Keyboard / Hardware / NumLock on Plasma Starup

### Config File Path

> [~/.config/kcminputrc](https://github.com/xerolinux/xero-kde-config/blob/main/etc/skel/.config/kcminputrc#L6) => Setion: [Keyboard]



| Option | Key=Value |
| --- | --- |
| Turn on | `NumLock=0` |
| Turn off | `NumLock=1` |
| Leave Unchanged | **no line for none** |


## SDDM

### Config File Path

> [/etc/sddm.conf](https://github.com/xerolinux/xero_iso/blob/main/archiso/airootfs/etc/sddm.conf#L4) => Setion: [General]

| Option | Key=Value |
| --- | --- |
| Turn on | `Numlock=on` |
| Turn off | `Numlock=off` |
| Leave Unchanged | `NumLock=` |

* $ man [sddm.conf](https://man.archlinux.org/man/sddm.conf.5.en#OPTIONS)


> xerolinux: [/etc/sddm.conf.d/kde_settings.conf](https://github.com/xerolinux/xero_iso/blob/main/archiso/airootfs/etc/sddm.conf.d/kde_settings.conf#L9)
