# zramen

Manage zram swap space

## Synopsis

```sh
zramen make
zramen toss
```

## Installation

```sh
install -Dm 755 zramen -t /usr/bin
cp -a sv/zramen /etc/sv
```

### Dependencies

- awk
- bash
- bc
- coreutils
- grep
- kmod
- procps-ng
- util-linux

## See Also

- [runit-swap](https://github.com/thypon/runit-swap)
- [systemd-swap](https://github.com/Nefelim4ag/systemd-swap)
- [zram-init](https://github.com/vaeth/zram-init)
- [zram-swap](https://github.com/foundObjects/zram-swap)
- [zramswap](https://aur.archlinux.org/packages/zramswap/)

## Licensing

This is free and unencumbered public domain software. For more
information, see http://unlicense.org/ or the accompanying UNLICENSE file.
