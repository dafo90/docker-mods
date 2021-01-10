# MariaDB as database - Docker mod for papermerge

This mod adds MariaDB library (`libmariadb-dev`) to papermerge, to be installed/updated during container start.

In papermerge docker arguments, set an environment variable `DOCKER_MODS=linuxserver/mods:papermerge-mariadb` to enable this mod.

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/mods:papermerge-mariadb|linuxserver/mods:papermerge-mod2`

Then set an environment variable named `MARIADBLIB` and set it to `true`.
