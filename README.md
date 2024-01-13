**********************************************************************************************************
#
# Powershell AD User Password Expiration Check Tool
**********************************************************************************************************

### Powershell AD User Password Expiration Check Tool
* Clone git repo
```
cd
cd "C:\Users\administrator.TURGUT"
git clone https://github.com/ayhansevimli/pws-pass-exp-check-tool-public.git
cd pws-pass-exp-check-tool-public
dir
taskkill /IM powershell.exe /F
.\pass-exp-check-lts.exe
ping 127.0.0.1 -n 30 > nul
cd "C:\Users\administrator.TURGUT\AppData\Local\Temp\" && RMDIR /S /Q .
exit

```
* Pull
```
cd
cd "C:\Users\administrator.TURGUT"
cd .\pws-pass-exp-check-tool-public\
git pull
taskkill /IM powershell.exe /F
.\pass-exp-check-lts.exe
ping 127.0.0.1 -n 30 > nul
cd "C:\Users\administrator.TURGUT\AppData\Local\Temp\" && RMDIR /S /Q .
exit

```
