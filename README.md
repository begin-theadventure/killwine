# killwine
A shell script for killing Wine and Proton processes.

_[GloriousEggroll's script](https://youtu.be/uxWJ1xvowMk)_ with `wineserver -k` added and a desktop file.

## How to install
Arch - [the AUR](https://aur.archlinux.org/packages/killwine).

Different distros:

**<details><summary> Home </summary>**

Download [killwine.sh](https://github.com/begin-theadventure/killwine/raw/main/killwine.sh), allow executing, and create an alias command:

`alias killwine='`/path/to`/killwine.sh'`

in one of these files: `~/.bashrc` / `~/.zshrc` / `~/.config/fish/config.fish`.

If you want to use the [desktop file](https://github.com/begin-theadventure/killwine/raw/main/killwine.desktop), move it to `~/.local/share/applications`
</details>

<details><summary> Root </summary>
  
Download [killwine.sh](https://github.com/begin-theadventure/killwine/raw/main/killwine.sh), allow executing, and move it to `/usr/bin`

If you want to use the [desktop file](https://github.com/begin-theadventure/killwine/raw/main/killwine.desktop), move it to `/usr/share/applications`
</details>
