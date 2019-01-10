# zfsnap-quota
Removes zfs snapshots until specified disk space amount is freed. 

When performing regular snapshots, it is easy to fill up the disk space. So i wrote this simple tool to be run every hour, which checks if the disk space is below a threshold and if it is not, it will start destroying zfs snapshots until it reaches the requested threshold.

