# FortniteProcessPriority
Permanently set process priority in Fortnite.

These registry fixes will allow you to change Fortnite's process priority, and permanently. For streamers, I recommend using the High Priority file and setting your streaming program's priority to Above Normal. For everyone else, use High Priority. To revert to normal, use the Normal file.

Before executing, ensure the .reg files are safe. They should look like this:
-----------------------------------------------------------------------------

Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\FortniteClient-Win64-Shipping.exe\PerfOptions]
"CpuPriorityClass"=dword:00000003
