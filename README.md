# Command-Prompt-Trick

####Feature: Commmand Prompt Option appere on DesktopBackground, DirectoryBackground, Directory Right Click Options. 

####Supported Platform:
1. Windows

####Usage:
1. Open Notepad
2. Copy this code 
```
Windows Registry Editor Version 5.00

[HKEY_CLASSES_ROOT\DesktopBackground\Shell\CommandPrompt]
"icon"="cmd.exe"
@="Command Prompt Here"

[HKEY_CLASSES_ROOT\DesktopBackground\Shell\CommandPrompt\command]
@="cmd.exe"

[HKEY_CLASSES_ROOT\directory\background\shell\CommandPrompt]
@="Command Prompt Here"
"icon"="cmd.exe"

[HKEY_CLASSES_ROOT\directory\background\shell\CommandPrompt\command]
@="cmd.exe"

[HKEY_CLASSES_ROOT\directory\shell\CommandPrompt]
@="Command Prompt Here"
"icon"="cmd.exe"

[HKEY_CLASSES_ROOT\directory\shell\CommandPrompt\command]
@="cmd.exe /k cd %1"

```
3. Save this file as CommandPrompt.reg
4. Close and Open this CommandPrompt.reg file by double click.
5. Enjoy :-)
