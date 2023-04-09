# Flatpak

## Installation instructions link:

https://flatpak.org/setup/

## Flathub link:

https://flathub.org/

## Command arguments documentation:

https://docs.flatpak.org/en/latest/flatpak-command-reference.html

## Add flathub repository:

`flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo`

## Enable flathub repository:

`flatpak remote-modify --enable flathub`

## Update Flatpaks:

`flatpak update -y`

## Repair Flatpak:

`sudo flatpak repair`

## Remove unused runtimes:

`flatpak uninstall --unused -y`

---

### Flatpak apps:

```
flatpak install flathub -y com.google.Chrome &&
flatpak install flathub -y com.parsecgaming.parsec &&
flatpak install flathub -y com.anydesk.Anydesk &&
flatpak install flathub -y com.transmissionbt.Transmission &&
flatpak install flathub -y io.github.TransmissionRemoteGtk &&
flatpak install flathub -y org.videolan.VLC &&
flatpak install flathub -y com.obsproject.Studio &&
flatpak install flathub -y org.libreoffice.LibreOffice &&
flatpak install flathub -y org.gnome.SimpleScan &&
flatpak install flathub -y org.gnome.Firmware &&
flatpak install flathub -y org.gnome.Connections &&
flatpak install flathub -y org.gnome.Boxes &&
flatpak install flathub -y org.gnome.Extensions &&
flatpak install flathub -y com.mattjakeman.ExtensionManager &&
flatpak install flathub -y io.github.realmazharhussain.GdmSettings &&
flatpak install flathub -y com.github.tchx84.Flatseal &&
flatpak install flathub -y tv.kodi.Kodi &&
flatpak install flathub -y com.usebottles.bottles &&
flatpak install flathub -y org.gimp.GIMP &&
flatpak install flathub -y org.kde.krita &&
flatpak install flathub -y org.kde.kdenlive &&
flatpak install flathub -y org.inkscape.Inkscape &&
flatpak install flathub -y com.boxy_svg.BoxySVG &&
flatpak install flathub -y io.github.prateekmedia.appimagepool &&
flatpak install flathub -y org.telegram.desktop &&
flatpak install flathub -y com.discordapp.Discord &&
flatpak install flathub -y com.vscodium.codium &&
flatpak install flathub -y com.visualstudio.code &&
flatpak install flathub -y io.podman_desktop.PodmanDesktop &&
flatpak install flathub -y com.google.AndroidStudio &&
flatpak install flathub -y fr.handbrake.ghb &&
flatpak install flathub -y net.lutris.Lutris &&
flatpak install flathub -y com.valvesoftware.Steam &&
flatpak install flathub -y com.valvesoftware.SteamLink &&
flatpak install flathub -y com.heroicgameslauncher.hgl &&
flatpak install flathub -y org.libretro.RetroArch &&
flatpak install flathub -y com.mojang.Minecraft &&
flatpak install flathub -y net.minetest.Minetest &&
flatpak install flathub -y net.openra.OpenRA &&

flatpak install flathub -y org.blender.Blender &&
flatpak install flathub -y org.darktable.Darktable &&
flatpak install flathub -y org.audacityteam.Audacity &&
flatpak install flathub -y org.onlyoffice.desktopeditors &&
flatpak install flathub -y com.mattermost.Desktop &&
flatpak install flathub -y net.cozic.joplin_desktop &&
flatpak install flathub -y fr.natron.Natron &&
flatpak install flathub -y org.freecadweb.FreeCAD &&
flatpak install flathub -y ca.desrt.dconf-editor &&
flatpak install flathub -y com.github.marktext.marktext &&
flatpak install flathub -y com.github.GradienceTeam.Gradience &&
```

---

### Defaults:

#### Fedora Silverblue:

```
flatpak install fedora -y org.fedoraproject.Platform &&
```

```
flatpak install flathub -y org.fedoraproject.MediaWriter &&
flatpak install flathub -y org.gnome.Calculator &&
flatpak install flathub -y org.gnome.Calendar &&
flatpak install flathub -y org.gnome.Characters &&
flatpak install flathub -y org.gnome.Connections &&
flatpak install flathub -y org.gnome.Contacts &&
flatpak install flathub -y org.gnome.Evince &&
flatpak install flathub -y org.gnome.Extensions &&
flatpak install flathub -y org.gnome.FileRoller &&
flatpak install flathub -y org.gnome.Logs &&
flatpak install flathub -y org.gnome.Maps &&
flatpak install flathub -y org.gnome.NautilusPreviewer &&
flatpak install flathub -y org.gnome.TextEditor &&
flatpak install flathub -y org.gnome.Weather &&
flatpak install flathub -y org.gnome.baobab &&
flatpak install flathub -y org.gnome.clocks &&
flatpak install flathub -y org.gnome.eog &&
flatpak install flathub -y org.gnome.font-viewer &&
```

