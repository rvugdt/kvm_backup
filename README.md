# script for searching qcow2 disks of SHUT DOWN VMs and copying them to the backup server
# exec this on your hypervisor

USAGE EXAMPLE:

root@myhypervisor ~ # ./backup_vm_drives.sh

Remote user: root
Remote storage address: mybackupserver.net
Remote storage folder: /storage/backups

[VM01] /vds/kvm/VM01.qcow2 >>> root@mybackupserver.net:/storage/backups/myhypervisor/2024-01-30/VM01/VM01.qcow2
[VM02] /vds/kvm/VM02.qcow2 >>> root@mybackupserver.net:/storage/backups/myhypervisor/2024-01-30/VM02/VM02.qcow2
[VM03] /vds/kvm/VM03.qcow2 >>> root@mybackupserver.net:/storage/backups/myhypervisor/2024-01-30/VM03/VM03.qcow2
