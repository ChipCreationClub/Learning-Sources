The Universal Patch for Materialise Local License Server v7 (modded for 3-matic 14 / Magics 24)

1. Run "%ProgramFiles%\Common Files\Materialise\LicenseFiles6\LicSrvConfig.exe".
2. Stop "Local License Server".
3. Change "AutoPassword server URL" to "https://localhost/MatPasswordsWS/MatPasswordsWS.asmx".
4. Close it.
5. Copy WINMM.dll to "%ProgramFiles%\Common Files\Materialise\LicenseFiles6\". 
6. Run LicSrvConfig.exe again.
7. Start "Local License Server".
8. Rename the orignal MatSDK.Common.Threads.dll to MatSDK.Common.Thread.dl1.
9. Copy MatSDK.Common.Threads.dll to the same directory as the orignal MatSDK.Common.Threads.dll. / + MatSDK.Common.Thread.dll (taken from Magics 23.01) / + MatGlobal.dll
10. Run the main program.
11. Select "Show license and system infomation" and click "Next" button.
12. Replace "AAAAAAAA-AAAA-AAAA-AAAAAAAAAAAAAAA" in *.matkey with your system id.
13. Select *.matkey and click "Register" button.

Remove all licenses: 
Stop "Local License Server" and Remove "%ALLUSERSPROFILE%\Materialise\LicenseFiles\Matsoft.L7.lic".
