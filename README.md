# Minetest-AppImages

AppImages for Minetest in 32bit and 64bit! Both client and server are in the same executable.

Tested on fresh installations from the oldest release it works on to the newest release tested:
(All of the releases in between should work too)

· Ubuntu (Trusty 14.04, Zesty 17.04, Focal 20.04)

· Fedora (30, 32)

· OpenSUSE (Leap 15.1, Tumbleweed)

· Archlinux (Manjaro 20.0.3)

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

Credit to [Calinou](https://forum.minetest.net/memberlist.php?mode=viewprofile&u=194) for the x64 AppImages he created. I used the libraries from them.
