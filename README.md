# My GnomeDesktopSettings

## Introduction

This repository contains my Gnome settings that I use on all my managed computers. It's a dirty script that sets some config keys using the dconf command.

## How to use

Just download this script. Set the permissions to executable and run it.

## How to adjust configuration

This is a very complex multi-step approach:

1. Dump your current settings with the command: `dconf dump / > before.dump`
2. Make your changes in the graphical interface
3. Dump your current settings with the command: `dconf dump / > after.dump`
4. Find the differences and add them to the script.

## License

I don't care. Do with this but at your own risk. I do not accept any responsibility or whatsoever.