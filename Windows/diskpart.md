| Command Name     | Usage                             | Example                                  | Parameter                                                                        |
|------------------|-----------------------------------|------------------------------------------|----------------------------------------------------------------------------------|
| list disk        | list all disks                    | list disk                                | -                                                                                 |
| select disk      | select a disk                     | select disk 1                            | -                                                                                 |
| clean            | clean selected disk               | clean                                    | -                                                                                 |
| create           | create something                  | create volume raid size=1000 disk=1,2,3  | create partition vdisk                                                           |
| create partition | create partition on selected disk | create partition primary size=10000      | efi extended logical msr primary                                                 |
| list partition   | list partitions on selected disk  | list partition                           | disk partition volume vdisk                                                      |
| select partition | select a partition                | select partition 1                       | disk partition volume vdisk                                                      |
| format           | format a selected partition       | format fs=ntfs quick label=NTFS          | FS= REVISION= RECOMMENDED= LABEL= UNIT= QUICK COMPRESS OVERRIDE DUPLICATE NOWAIT |
| assign           | assign something to a partition   | assign letter=x                          | letter= mount=                                                                   |
