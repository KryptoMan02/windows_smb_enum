# windows_smb_enum
## crackmap exec for enumerating shares if guest login is enabled or we know the credentials

1. for guest login ---> crackmapexec smb 10.129.209.121 -u guest -p '' --shares
2. if username/password are known ----> crackmapexec smb 10.129.209.121 -u $USER -p $PASS --shares 

