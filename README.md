# IT-test

chkdsk d: /R /F /X

SFC /SCANNOW 

DISM /Online /Cleanup-image /Scanhealth
DISM /Online /Cleanup-image /Restorehealth
systemreset -cleanpc
