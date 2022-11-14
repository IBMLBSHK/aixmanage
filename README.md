# AIX management ansible tools target include

1. User management (role: userman)
    - List user
    - Add user
    - Delete user
    - Assign user to group
2. PAM management (role: pamman)
    - Reset password
    - Reset login count
    - Set password requirement
3. LVM management (role: lvmman)
    - Create / delete / import VG
    - Create / delete LV
    - Create / delete / mount / unmount FS
4. NIM management (role: nimman)
    - Add NIM client
    - Configure Lpp Soure / Spot / mksysb / savevg
    - Backup / Restore AIX
    - Backup / Restore VIOS
    - Update / Upgrade OS version / patch
5. File management (role: fileman)
    - Check file consistent (sha1sum)
    - Sync files
6. Disk clone management (role: diskman)
    - Alt disk clone
    - Mirror disk
    - Unmirror disk
