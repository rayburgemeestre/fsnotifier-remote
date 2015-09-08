I removed the Python part of this stuff, because I had lots of problems getting it to work on non-windows.

So it's a bit more basic, and no longer provides mapping between different folders on remote/local.
See http://blog.cppse.nl/jetbrains-fsnotifier-over-remote-connection for more info on that.

Usage:

- Build `fsnotifier` on the remote host.
- Install `ksh` on your local host (probably `apt-get install ksh` or something similar).
- Edit `fsnotifier` script, setup the correct `ssh` execution
- Edit `fsnotifier` script, tweak the `custom_filter` to your needs.
