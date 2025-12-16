xf86-video-vboxvideo - VirtualBox video driver for the XLibre X server
--------------------------------------------------------------------

This driver is only for use in VirtualBox guests without the
vboxvideo kernel modesetting driver in the guest kernel, and
which are configured to use the VBoxVGA device instead of a
VMWare-compatible video device emulation.

Guests with the vboxvideo kernel modesetting driver should use the
Xorg "modesetting" driver module instead of this one.

The primary development code repository can be found at:

  https://github.com/X11Libre/xf86-video-vbox

Please submit bug reports and requests to merge patches there.

This driver is dedicated to the memory of Michael Thayer, who brought
it to X.Org and made the initial release before he passed away in 2019.
