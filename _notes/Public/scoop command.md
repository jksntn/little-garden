---
title : Scoop Command
feed : show
date : 24-08-2023
description : Beberapa list scoop command yang bisa digunakan
---

Beberapa perintah penting di aplikasi [Scoop](https://scoop.sh/) di windows. Sengaja saya tulis karena di dokumentasi sananya kurang lengkap 🫣

`# To install a package:`<br><br>`scoop install <package>`<br><br>`# To remove a package:`<br><br>`scoop uninstall <package>`<br><br>`# To update all installed packages:`<br><br>`scoop update *`<br><br>`# To list installed packages:`<br><br>`scoop list`<br><br>`# To display information about a package:`<br><br>`scoop info <package>`<br><br>`# To search for a package:`<br><br>`scoop search <package>`<br><br>`# To list all known buckets (a bucket is an application repository):`<br><br>`scoop bucket known`<br><br>`# To add a bucket by its alias or a Git repository URL:`<br><br>`scoop bucket add <bucket>`<br><br>`# ---`<br><br>`# To install scoop (requires powershell >= 3):`<br><br>`iex (``new-object` `net.webclient).downloadstring(``'https://get.scoop.sh'``)`<br><br>`# To uninstall scoop:`<br><br>`scoop uninstall scoop`<br><br>`# To update scoop:`<br><br>`scoop update`<br><br>`# To install several utils at once:`<br><br>`scoop install 7zip curl sudo git openssh coreutils grep sed less`<br><br>`# To install several programming languages at once:`<br><br>`scoop install python ruby go nodejs`<br><br>`# To install php (see https://github.com/lukesampson/scoop/wiki/Custom-PHP-configuration for persisting php.ini settings through updates):`<br><br>`scoop install php`<br><br>`# To install an app (Git) globally:`<br><br>`sudo scoop install git --global`<br><br>`# To update a globally installed app (Git):`<br><br>`sudo scoop update git --global`

sumber: [https://jonlabelle.com/snippets/view/powershell/scoop-command](https://jonlabelle.com/snippets/view/powershell/scoop-command)