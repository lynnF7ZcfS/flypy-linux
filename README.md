#  flypy for linux
[简体中文](https://github.com/imaojun/flypy-linux/blob/master/Chinese.md)

This repository resource is mirrored from the official web disk.

After version 9.7, the official version only provides hooked versions of Windows and MAC OS. The GNU / Linux hooked version is no longer downloadable. Therefore, this version will be taken from the
MACOS version and then modified to the GNU/Linux version.

After version 9.9g, the official removed the flypy-plus configuration and file.

## Supported input method frameworks:
- [x] Fcitx-Rime
- [x] Ibus-Rime
- [x] YONG



## updated version

Please refer to the official website update instructions:
https://flypy.com/bbs/forum.php?mod=viewthread&tid=8&extra=page%3D1


## Structure

flypy for Rime:

```
fcitx/rime-data
├── build
│   ├── flypydz.prism.bin
│   ├── flypydz.reverse.bin
│   ├── flypydz.table.bin
│   ├── flypy.prism.bin
│   ├── flypy.reverse.bin
│   └── flypy.table.bin
├── default.yaml
├── flypy.schema.yaml
├── flypy_sys.txt
├── flypy_top.txt
├── flypy_user.txt
└── rime.lua

```

flypy for IBUS:

```
ibus
├── bus
│   ├── 484233f2569a47908894dd244239e2fd-unix-0
│   └── 8ab79d3e156c46588cf333151756725f-unix-0
└── rime
    ├── build
    ├── default.custom.yaml
    ├── default.custom.yaml.example
    ├── flypy.schema.yaml
    ├── flypy_sys.txt
    ├── flypy_top.txt
    ├── flypy_user.txt
    ├── installation.yaml
    ├── luna_pinyin.userdb
    ├── rime-data
    ├── rime.lua
    ├── trash
    └── user.yaml
```


flypy for Yong:
```
yong
├── mb
│   ├── english.txt
│   ├── pinyin.txt
│   ├── pypre.bin
│   ├── xhbc.txt
│   ├── xhup.ini
│   ├── xhup.txt
│   ├── xhzcm.txt
│   └── yb.txt
├── skin
│   ├── ....
└── yong.ini

```




## Installation and use

See wiki: 

https://github.com/imaojun/flypy-linux/wiki


