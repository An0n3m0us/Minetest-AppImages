# Minetest-Appimages

AppImages for Minetest 5.0+ for 32bit and 64bit! Both client and server AppImages are provided.

Tested on fresh installations (32bit and 64bit) of:

· Ubuntu (Trusty 14.04, Xenial 16.04, Bionic 18.04)

· Debian 8 and 9

· Fedora 30 (only 32bit works)

· Linux Mint 19.1

## Running
Download the AppImages from the release page! Then, make the AppImage an executable by using `chmod +x <file>` in the terminal or by right-clicking the file then selecting "Properties" then "Permissions", and checking the executable checkbox. Double-click the AppImage to run Minetest.

The directory used by the Minetest AppImages is $HOME/.minetest/ so you may place your mods, games and texture packs in there.

## Setting up Minetest globally
(i.e running minetest from the terminal with `minetest-$VERSION`)

First, rename the AppImage to minetest-$VERSION, eg: minetest-5.0.1

Move the AppImage to $HOME/bin/ then open a terminal and run `minetest-$VERSION`. Minetest should now launch.

You can now create a launcher in the applications menu to launch it.

## Other

Please let me know if you encounter any errors. Report them on the issues page.

Credit to [Calinou](https://forum.minetest.net/memberlist.php?mode=viewprofile&u=194) for the x64 Appimages he created. I used the libraries from them.
