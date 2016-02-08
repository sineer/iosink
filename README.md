iosink: The iocage friendly zfs replication manager.

WARNING! STILL ALPHA, NOT PRODUCTION READY! USE AT YOUR OWN RISKS...

I/O Sink are ZREP destination; read-only ZFS file system(s).

iosink allows one to keep hot copies of local and remote ZFS file systems
with the ability to do quick failover or cloning of I/O Sink into Jail.

iosink rely on zrep to do super efficient incremental zfs replication.

iosink is iocage friendly because it knows how to replicate iocage(s) jails
zfs fs including and their children fs that along with the zfs properties.

TODO: link to future website with hosted doc and man page.
