# Useful commands

Get information for a window. This information can be used to start applications in specific workspace.
  xprop | grep WM_CLASS

Get name and infos about network adapters
  ip link

# Useful key bindings

## i3 

  $mod+f fullscreen toggle
  $mod + shift + space - toggle tiling / floating

  $mod + [0-9] - switch to workspace
  $mod + shift + [0-9] - move focused container to workspace

  $mod + enter - start urxvt (terminal)
  $mod + shift + q - kill active window

  $mod + shift + c - reload the configuration file
  $mod + shift + e - exit i3
  $mod + shift + r - restart i3 inplace (preserves your layout/session, can be used to upgrade i3)

  $mod + e - toggle split mode (vertical , horizontal)
  $mod + s - stacked windows
  $mod + w - tabbed windows

  $mod + r - switch to resize mode
  return or esc - back to normal mode

  $mod + [l, k, j] - resize active window

# Installed packages

Lock screen for i3:
  sudo pacman -S i3lock
Programm to display immages
  sudo pacman -S feh
