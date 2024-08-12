# KDE Ctrl+Alt+Del

KDE Ctrl+Alt+Del is a bash script that mimics the menu that is displayed in Windows systems when pressing CTRL + ALT + DEL. 

It uses [Rofi](https://github.com/davatorium/rofi) for window management. 

Rofi is overkill to display a simple KDialog, but it is convenient to make a menu that you can just "click" without selecting and then pressing an "OK" button below, in the spirit of mimicking the Windows-style menu.

## Installation

Make sure rofi is installed, or install it with the command below:

```bash
sudo apt install rofi
```
Clone this repository and place the "ctrlaltdel" file wherever you wish.

Lastly, run:
```bash
chmod +x ctrlaltdel
```
to give executable permissions.

## Set the keyboard shortcut
1. Go to KDE System Settings
2. Select "Shortcuts"
3. Select "+ Add Application..."
4. Click the Browse button and select the location where you've placed the ctrlaltdel script.
5. Add custom shortcut (CTRL+ALT+DEL or whatever you want)
6. Apply changes


## License

[MIT](https://choosealicense.com/licenses/mit/)
