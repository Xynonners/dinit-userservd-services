# dinit-userservd-services
Artix services for dinit-userservd (https://github.com/chimera-linux/dinit-userservd).

Artix fork of dinit-userservd located at: https://github.com/XynonWasTaken/dinit-userservd

PKGBUILDs for dinit-userservd located at: https://github.com/XynonWasTaken/dinit-userservd-PKGBUILD

To use these services, place them in one of the following locations:

~/.config/dinit.d/

/etc/dinit/user/

/usr/lib/dinit.d/user/

/usr/local/lib/dinit.d/user/

Run mkdir -p ~/.local/share/dinit

This is the log directory or the services will fail to start.
Start the services using the user dinit instance spawned by dinit-userservd.

NOTE: These services are experimental and may not work correctly. 

NOTE: Currently scripts in the scripts directory must be placed within /etc/dinit/user/scripts and not any other location.
