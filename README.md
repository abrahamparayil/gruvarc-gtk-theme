## gruvarc-gtk-theme
A gtk theme based on Materia theme and Gruvbox color palette. Created overnight becuase the my brain refused to sleep without seeing a coherent and consistant color scheme throughout my desktop. It's not perfect yet, still a working progress, so go ahead hack on it, make it better or mke your own versions of it.:)

### How to install
Just cole the repo and copy it to the .themes folder in your home. If you wish to apply the theme system-wide regardless of the user you must place it in /usr/share/themes.
```sh
git clone https://github.com/avronr/gruvarc-gtk-theme
cp -r gruvarc-gtk-theme ~/.themes #if this folder does not exist make it using mkdir or your file manager

#For applying it system-wide
sudo cp -r gruvarc-gtk-theme /usr/share/themes
```

## Parent Projects

### Materia

<img src="https://github.com/nana-4/materia-theme/blob/images/materia-logo.svg" alt="materia-logo" align="right" />

[Materia](https://github.com/nana-4/materia-theme) is a [Material Design](https://material.io) theme for GNOME/GTK based desktop environments.
It supports GTK 2, GTK 3, GNOME Shell, Budgie, Cinnamon, MATE, Unity, Xfce, LightDM, GDM, Chrome theme, etc.

### Gruvbox
[Gruvbox](https://github.com/morhetz) is heavily inspired by [badwolf][], [jellybeans][] and [solarized][].

Designed as a bright theme with pastel 'retro groove' colors and light/dark mode switching in the way of [solarized][]. The main focus when developing gruvbox is to keep colors easily distinguishable, contrast enough and still pleasant for the eyes.

<p align="right"><img src="http://svgur.com/i/3Dp.svg"></p>

   [badwolf]: https://github.com/sjl/badwolf
   [jellybeans]: https://github.com/nanotech/jellybeans.vim
   [solarized]: http://ethanschoonover.com/solarized
