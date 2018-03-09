# FortniteProcessPriority
Permanently set process priority in Fortnite.

Before executing, ensure the .reg files are safe. They should look like this:
-----------------------------------------------------------------------------

Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\FortniteClient-Win64-Shipping.exe\PerfOptions]
"CpuPriorityClass"=dword:00000003
