# exe2powershell
exe2powershell - exe2bat reborn for modern Windows

exe2bat reborn in exe2powershell for modern Windows
initial author ninar1, based on riftor work, and modernized by ycam
exe2powershell - keep up to date : www.asafety.fr
         
Main code taken from Riftors "exe2hex".

Adapted for Windows BAT file by ninar1.

Modernized to newer Windows systems by Yann CAM (ycam - http://www.asafety.fr)

This version is modernized from exe2bat to work with modern Windows version.
exe2bat have limitation :
- Need "debug.exe" available on the target computer (16-bit application removed on Windows 7 x64 but available on Windows 7 x86)
- Limit input exe to 64kB

exe2powershell replace the need of "debug.exe" by a PowerShell command line available on all Windows since Windows 7 / 2008.
There is no more limitation in input exe size.

How to use :

C:\Users\admin\Desktop>exe2powershell.exe nc.exe nc.bat

[*] Finished: nc.exe > nc.bat

Credits : Riftor, ninar1, BCK and ycam
