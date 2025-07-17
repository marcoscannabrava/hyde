# a minimal opinionated fork of [HyDE](https://github.com/HyDE-Project/HyDE)
<div align = center>
  <a href="https://discord.gg/AYbJ9MJez7">
    <img alt="Dynamic JSON Badge" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fdiscordapp.com%2Fapi%2Finvites%2FmT5YqjaJFh%3Fwith_counts%3Dtrue&query=%24.approximate_member_count&suffix=%20members&style=for-the-badge&logo=discord&logoSize=auto&label=The%20HyDe%20Project&labelColor=ebbcba&color=c79bf0">
  </a>
</div>

###### _<div align="right"><a id=-design-by-t2></a><sub>// design by t2</sub></div>_

![hyde_banner](Source/assets/hyde_banner.png)

<br>

&nbsp;|&nbsp;
<span><a href="#installation">Installation</a></span>&nbsp;|&nbsp;
<span><a href="#updating">Updating</a></span>&nbsp;|&nbsp;
<span><a href="#themes">Themes</a></span>&nbsp;|&nbsp;
<span><a href="#styles">Styles</a></span>&nbsp;|&nbsp;
<span><a href="CONTRIBUTING.md">Contributing</a></span>&nbsp;|&nbsp;
<span><a href="KEYBINDINGS.md">Keybindings</a></span>&nbsp;|&nbsp;
<span><a href="https://www.youtube.com/watch?v=2rWqdKU1vu8&list=PLt8rU_ebLsc5yEHUVsAQTqokIBMtx3RFY&index=1">Youtube</a></span>&nbsp;|&nbsp;
<span><a href="https://hydeproject.pages.dev/">Wiki</a></span>&nbsp;|&nbsp;
<span><a href="https://discord.gg/qWehcFJxPa">Discord</a></span>&nbsp;|&nbsp;

<br><br>

# installation

```shell
git clone --depth 1 https://github.com/HyDE-Project/HyDE ~/HyDE
cd ~/HyDE/Scripts
./install.sh
reboot
```

> [!TIP]
> You can also add any other apps you wish to install alongside HyDE to `Scripts/pkg_user.lst` and pass the file as a parameter to install it like so:
>
> ```shell
> ./install.sh pkg_user.lst
> ```

> [!IMPORTANT]
> Refer your list from `Scripts/pkg_extra.lst`
> or you can `cp Scripts/pkg_extra.lst Scripts/pkg_user.lst` if you wish to install all extra packages.

