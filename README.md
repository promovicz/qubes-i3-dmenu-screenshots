## Screenshots and notes on qubes-i3-dmenu

Here are some screenshots of qubes-i3-dmenu. The user interface is as simple as dmenu itself. The only extension with respect to the defaults is the VM-sensitive coloring. Dark blue is the default color.

It definitely is minimalist.

### Desktop file launching

Note that views for the launch action that select VMs are just the first step of a two-step process.

First you select the VM and then the application within the VM. This is easier to navigate than the default.

VM coloring gives the user an extra hint at which VM the launch will happen in.

For the dom0 there is a special launch mode separate from other modes because dom0 launches are seldom required because of VM control through dmenu.

### VM action selectors

There are start/shutdown/pause/unpause actions. Menus are filtered for VMs that are in a state appropriate for the respective action.

### Quit/shutdown/reboot confirmation

The "session quit" example requires the user to press cursor-right several times so that a session is not terminated inadvertently.

Similar confirmations are used for shutdown and reboot.

