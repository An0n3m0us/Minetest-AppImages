# Minetest-AppImages

AppImages for Minetest dev builds in 32 bit[^1] and 64bit! Both client and server are in the same executable.

Tested on fresh installations from the oldest releases to the newest releases tested:
(All of the releases in between should work too)

· Ubuntu (Bionic 18.04, Impish 21.10)

· Fedora (33, 35)

· OpenSUSE (Leap 15.3, Tumbleweed)

· Archlinux (Manjaro 21.1.6)

<sub>For Chromebook users: https://www.linuxmadesimple.info/2020/07/how-to-install-minetest-53-on-chromebook.html</sub>

[^1]: Halted unless a need for i386 arises as it requires extra work to compile, test and manage libraries

## Running
Download the AppImages from the release page! Then, make the AppImage an executable by entering `chmod +x $FILE` in a terminal or by right-clicking the file then selecting "Properties" then "Permissions", and checking the executable checkbox. Then, double-click the AppImage to run Minetest.

The directory used by the Minetest AppImages is `$HOME/.minetest/` so you may place your mods, games and texture packs in there.

To run a Minetest server, enter this command in a terminal:

`$PATH_TO_APPIMAGE/Minetest-$VERSION-$ARCH.AppImage --server`

## Setting up Minetest on your system globally
(i.e running minetest from the terminal with `minetest`)

First, rename the AppImage to minetest-$VERSION or just minetest; eg: minetest-5.1.1

Move the AppImage to $HOME/bin/ then open a terminal and enter `minetest-$VERSION` or `minetest`. Minetest should now launch.

You can now create a launcher in the applications menu to launch it.

## Other

Please let me know if you encounter any errors. Report them on the issues page.
