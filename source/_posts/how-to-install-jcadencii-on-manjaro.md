---
title: how to install jcadencii on manjaro
date: 2020-02-03 17:52:33
tags: 
 - manjaro
 - AUR
 - software
---
1. Download the PKGBUILD file from aur
2. edit the PKGBUILD file
3. there is a error about mirror and version name,so let us correct it!
pay attention to this place
```
pkgver=3.3.9%2Bsvn20110818.r1732
pkgrel=6
source=("https://mirrors.ustc.edu.cn/debian/pool/main/c/cadencii/jcadencii_${pkgver}-${pkgrel}_all.deb")
sha1sums=('41bbffe0e34f95fd1c69d819fdcc621cf266fb83')
```
4. ok!let us `makepkg` !
5. done!
