juno
====

X-IO volume driver for OpenStack Juno release.

This version tracks with the driver in the OpenStack master branch heading for the Kilo release. It has been modified to remove dependencies on Cinder framework features not available in Juno.

It requires ISE FW 2.8.0 / 3.1.0 or higher.

Features supported:

Create/delete volume
Initialize/Terminate connection
Create/delete snapshot from volume
Create volume from volume (clone)
Extend volume
Retype
Manage existing volume
Unmanage
