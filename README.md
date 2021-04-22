<h2 align="center">WPS Office Theme Patcher</h2>

<p align="center">Easily patch WPS Office Theme to solve QT problems with Dark GTK Themes on GNU/Linux</p>

##  
### Dependencies <img alt="" align="right" src="https://badges.pufler.dev/visits/owl4ce/wpsotp?style=flat-square&label=&color=000000&logo=GitHub&logoColor=white&labelColor=373e4d"/>
`sh/bash` `sed` `sudo/doas` `wps-office`

##  
### Patching
cURL/wget **wpsotp** then enter your Light GTK Themes e.g **Adwaita**.
```sh
$ sh <(curl -s "https://raw.githubusercontent.com/owl4ce/wpsotp/main/wpsotp")
```

> :heavy_check_mark: **WPS 2019**

##  
### Undo patch
```sh
$ sh <(curl -s "https://raw.githubusercontent.com/owl4ce/wpsotp/main/wpsotp") -u
```

##  
### Re-patch
Just [undo patch](#undo-patch) and [patch](#patching) again.

##  

<p align="center"><img src="./screenshots/wpsotp.jpg" align="center"/></p>

Dark GTK Themes|Light GTK Themes
|--|--|
<img src="./screenshots/dark-theme.jpg"/>|<img src="./screenshots/light-theme.jpg"/>

##  
### Credits
- *https://tan.my.id/post/fix-dark-theme-wps*
