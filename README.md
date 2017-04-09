# PowerShell

###############################################################################################
##
## Name of Sctipt
##
## Copyright (C) 2017 - Karol Bebel ANTARES
## All rights are reserved by Karol Bebel ANTARES and the use without permission is prohibited. 
##
###############################################################################################


all projects


$Key = New-Object Byte[] 16
[Security.Cryptography.RNGCryptoServiceProvider]::Create().GetBytes($Key)
$Key | out-file $KeyFile
