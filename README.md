# kisok
depoy ml
test pile ml



connet Guest，
net user installuser 22354940
net user user /add
wmic UserAccount where "Name='installuser'" set PasswordExpires=False
wmic UserAccount where "Name='user'" set PasswordExpires=False

reg add "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon" /v DefaultUserName /t REG_SZ /d USER /f
