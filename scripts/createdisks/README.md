# Create and delete disks

The rebuild script is an example of the necessary sequence of commands
to create or delete a filesystem, its nsds and vdisks.

## Create disks
A configuration stanza is being created automatically based
on the input parameters filesystem name, pool name and (data) disk size.

24 vdisks are created in two recovery groups, one for data and one for metadata

## Delete disks

The filsystem is unmounted and deleted, the nsds and vdisks are deleted
