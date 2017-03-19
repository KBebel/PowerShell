# PowerShell
all projects


$Key = New-Object Byte[] 16
[Security.Cryptography.RNGCryptoServiceProvider]::Create().GetBytes($Key)
$Key | out-file $KeyFile
