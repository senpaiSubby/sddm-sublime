## Installation:<br>
First clone the repository:<br>
```https://github.com/Simply-Sublime/sddm-sublime```<br><br>
Make sure that you have sddm, qt5 and fira-mono installed. On arch:<br>
```sudo pacman -S sddm qt5 ttf-fira-mono```<br><br>
Then move it to the sddm-themes directory:<br>
```sudo mv sddm-sublime /usr/share/sddm/themes/sublime```<br><br>
Then set the current theme to sublime in sddm.conf:<br>
```sudo vim /etc/sddm.conf```<br>
and set "Current" equal to "sublime" (no speech marks).

![alt text](/preview.png "login")

## Customisation:
There are a few options that you can edit in "theme.conf" - background, autoFocusPassword and enableHDPI.<br><br>
<b>background</b>: set this equal to the path of your background. I would recommend you place your background in the Assets folder and use the relative path (e.g. the default is Assets/background.jpg).<br><br>
<b>autoFocusPassword</b>: set this equal to 'true' (no quotes) to make the password input to automatically focus after you have chosen your user. To focus the password without using this option you can press the TAB key, or click in the area.<br><br>
<b>enableHDPI</b>: set this equal to 'true' (no quotes) to enable HDPI mode - this decreases some of the font-sized as they are automaticaly scaled up, messing up some of the layout. I can't test this myself on a HDPI screen, so if you have any issues, don't be afriad to open an issue.<br>

