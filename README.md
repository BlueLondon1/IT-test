# IT-test

chkdsk directory: /R /F /X

SFC /SCANNOW 

DISM /Online /Cleanup-image /Scanhealth


DISM /Online /Cleanup-image /Restorehealth


systemreset -cleanpc

# W.7 :
## All the Re-Installation come with de Live-CD / USB

From the command prompt : (F8 before shut down, F8 when rebooting)

With UEFI : (Beware, it can be a legacy bios, if that's it, it won't work at all)
bootrec /rebuildbcd

bootrec /fixmbr

bootrec /fixboot

# W.8 ~8.1 :

## All the Re-Installation come with de Live-CD / USB

From the command prompt : (F8 before shut down, F8 when rebooting)

With UEFI : (Beware, it can be a legacy bios, if that's it, it won't work at all)
bootrec /rebuildbcd

bootrec /fixmbr

bootrec /fixboot
