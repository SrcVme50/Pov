# Pov

User

LFI

https://book.hacktricks.xyz/pentesting-web/deserialization/exploiting-__viewstate-parameter#test-cases


ysoserial

https://github.com/pwntester/ysoserial.net


Root

https://mcpmag.com/articles/2017/07/20/save-and-read-sensitive-data-with-powershell.aspx


Other

https://book.hacktricks.xyz/v/cn/windows-hardening/windows-local-privilege-escalation/privilege-escalation-abusing-tokens#qi-yong-suo-you-ling-pai
https://book.hacktricks.xyz/windows-hardening/basic-powershell-for-pentesters#secure-string-to-plaintext

$credential = Import-Clixml -Path "c:\users\sfitz\documents\connection.xml"
echo ($credential.UserName + ":" + $credential.GetNetworkCredential().Password)
