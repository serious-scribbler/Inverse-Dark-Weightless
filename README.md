# Inverse-Dark-Weightless Theme
A modification of the Inverse-dark Kvantum Theme for Qt 5. I modified this theme to fit the transparent aesthetic of my [Weightless-Theme](https://github.com/serious-scribbler/WeightlessTheme) for awesomeWM.

## Screenshots
<div>
  <table>
    <tr>
      <th>Ark with Inverse-Dark-Weightless-Theme</th>
      <th>Dolphin with Inverse-Dark-Weightless-Theme</th>
    </tr>
    <tr>
      <td><img src="screenshots/weightless-ark.png" alt="Ark with Inverse-Dark-Weightless-Theme"></img></td>
      <td><img src="screenshots/weightless-dolphin.png" alt="Ark with Inverse-Dark-Weightless-Theme"></img></td>
    </tr>
  </table>
</div>

## Getting started (and requirements)
1. This theme requires a compositor like compton. **(If you found this through my awesomeWM-Weightless-Theme continue with step 2)**
  Install ```compton``` and add it to your ```xinitrc```
2. Install ```qt5ct```, ```qt5-style-plugins```, ```qt5-style-kvantum```
3. Start ```qt5ct``` and select your icon theme. I like to use ```nuoveXT .2.2```
4. Add ```export QT_QPA_PLATFORMTHEME="qt5ct"``` to your ```.xinitrc```
5. Download this theme
6. Log out and back in again to apply the change to use qt5ct
7. Open ```kvantummanager```, select the *Inverse-dark-weightless* directory (The one with the svg file, not the git repo) and press *"Install this theme"*
8. Click on ```Change/Delete Theme```, select ```Inverse-dark-weightless``` from the dropdown list and press *"Use this theme"*
9. Quit kvantummanager and open a Qt5 program (examples: dolphin, pcmanfm, ark)


## Known issues
- The disk usage indicator in dolphin is basically unreadable

## Attribution
This theme is a modification of the Inverse-dark Kvantum theme by yeyushengfan258 and is licensed under GPLv3. You can find the original theme [here](https://github.com/yeyushengfan258/Inverse-dark-kde)
