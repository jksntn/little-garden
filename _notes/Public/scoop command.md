---
title : Scoop Command
feed : show
date : 24-08-2023
description : Beberapa list scoop command yang bisa digunakan
---

Beberapa perintah penting di aplikasi [Scoop](https://scoop.sh/) di windows. Sengaja saya tulis karena di dokumentasi sananya kurang lengkap 🫣

`# To install a package:`
`scoop install <package>`

`# To remove a package:`
`scoop uninstall <package>`

`# To update all installed packages:`
`scoop update *`

`# To list installed packages:`
`scoop list`

`# To display information about a package:`
`scoop info <package>`

`# To search for a package:`
`scoop search <package>`

`# To list all known buckets (a bucket is an application repository):`
`scoop bucket known`

`# To add a bucket by its alias or a Git repository URL:`
`scoop bucket add <bucket>`

`# ---`
`# To install scoop (requires powershell >= 3):`
`iex (``new-object` `net.webclient).downloadstring(``'https://get.scoop.sh'``)`

`# To uninstall scoop:`
`scoop uninstall scoop`

`# To update scoop:`
`scoop update`

`# To install several utils at once:`
`scoop install 7zip curl sudo git openssh coreutils grep sed less`

`# To install several programming languages at once:`
`scoop install python ruby go nodejs`

`# To install php (see https://github.com/lukesampson/scoop/wiki/Custom-PHP-configuration for persisting php.ini settings through updates):`
`scoop install php`

`# To install an app (Git) globally:`
`sudo scoop install git --global`

`# To update a globally installed app (Git):`
`sudo scoop update git --global`

sumber: https://jonlabelle.com/snippets/view/powershell/scoop-command