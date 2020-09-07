---
title: Uji Coba Markdown, Tag, Kategori, dll
author: Albawid
date: 2020-09-06 14:32
categories: [Test, Demo]
tags: [markdown, linux]
---

# Orientasi
---

Rencananya didalam tulisan blog akan dibagi menjadi beberapa kategori:

1. Orientasi
2. Permasalahan
3. Pemecah Masalah
4. Kesimpulan

Kategori diatas bisa berubah sesuai dengan artikel yang dibahas

# Uji Coba Syntax Highlighting
---

### Info Istilah

1. **$** : artinya `user`
2. **#** : artinya `root`

### Console

```console
ini adalah syntax untuk code biasa
```

### Terminal

```terminal
$ sudo pacman -Syyuw
Password:
:: Synchronizing package databases...
core                  132.5 KiB   589 KiB/s 00:00 [#########] 100%
extra                1667.3 KiB   621 KiB/s 00:03 [#########] 100%
community               5.2 MiB   965 KiB/s 00:05 [#########] 100%
multilib              160.2 KiB   454 KiB/s 00:00 [#########] 100%
home_metakcahura...     4.3 KiB  0.00   B/s 00:00 [#########] 100%
home_metakcahura...   280.0   B  0.00   B/s 00:00 [#########] 100%
:: Starting full system upgrade...
resolving dependencies...
warning: insufficient columns available for table display
Packages (41) at-spi2-core-2.36.1-1  cryptsetup-2.3.4-1
             faudio-20.09-1  gnupg-2.2.23-1  gnutls-3.6.15-1
             gtk-update-icon-cache-1:3.24.23-1  gtk3-1:3.24.23-1
             htop-3.0.1-1  iana-etc-20200905-1
             lib32-faudio-20.09-1  lib32-gnutls-3.6.15-1
             lib32-mesa-20.1.7-1  lib32-systemd-246.4-1
             lib32-vulkan-radeon-20.1.7-1  libao-1.2.2-5
             libcap-ng-0.7.11-2  libmpdclient-2.19-3
             libsidplayfp-2.0.2-1  libutil-linux-2.36-3
             libwacom-1.5-1  linux-5.8.6.arch1-1
             linux-headers-5.8.6.arch1-1  mesa-20.1.7-1
             mkinitcpio-busybox-1.31.1-2
             mlocate-0.26.git.20170220-5  mpc-0.33-3
             mpd-0.21.25-3  node-gyp-7.1.0-1  poppler-20.09.0-1
             poppler-glib-20.09.0-1  python-3.8.5-2
             python-attrs-20.2.0-1  python2-2.7.18-2
             reflector-2020.9-1  systemd-246.4-1
             systemd-libs-246.4-1  systemd-sysvcompat-246.4-1
             util-linux-2.36-3  vim-8.2.1584-1
             vim-runtime-8.2.1584-1  vulkan-radeon-20.1.7-1

Total Download Size:  208.74 MiB

:: Proceed with download? [Y/n]
```

### Shell

```shell
if [ $? -ne 0 ]; then
    echo "The command was not successful.";
    #do the needful / exit
fi;
```

### HTML

```html
<div class="sidenav">
  <a href="#contact">Contact</a>
  <button class="dropdown-btn">Dropdown
    <i class="fa fa-caret-down"></i>
  </button>
  <div class="dropdown-container">
    <a href="#">Link 1</a>
    <a href="#">Link 2</a>
    <a href="#">Link 3</a>
  </div>
  <a href="#contact">Search</a>
</div>
```

### HTML (dengan scroll horizontal)

```html
<div class="panel-group">
  <div class="panel panel-default">
    <div class="panel-heading" id="{{ category_name }}">
      <i class="far fa-folder"></i>
      <p>Ini adalah contoh kalimat yang sangat panjaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaang.</p>
      </a>
    </div>
  </div>
</div>
```

### Kesimpulan
---

Nyatanya menulis artikel menggunakan format `markdown` `contoh-file.md`, tidaklah sulit jika dibandingkan menulis dengan format `.xml` atau bahkan `html` itu sendiri, meskipun user yang menulis termsuk *masih baru* sudah tersedia official cheat sheet atau panduan yang bisa kalian liat [disini](https://www.markdownguide.org/cheat-sheet/)

Sebagai contoh saya tunjukkan workflow saat menulis markdown.
![contoh-md](/assets/img/pic/contoh-md.png)
