# Install2Docker

Sometimes Docker, Boot2Docker and/or VirtualBox get really messed up. Completely
removing Boot2Docker and Docker data and settings, uninstalling VirtualBox, then
reinstalling Boot2Docker is a fail-proof way to get a working environment back.

## Usage

```bash
$ ./install2docker --uninstall
Password:

...

Do you wish to continue none the less (Yes/No)?
Yes

...

Do you wish to uninstall VirtualBox (Yes/No)?
Yes

$ ./install2docker
```

If you get the uninstall error "Failed to unload one or more KEXTs, please
reboot the machine to complete the uninstall," try the uninstaller again.
Otherwise you probably ignore this error, and install without rebooting.