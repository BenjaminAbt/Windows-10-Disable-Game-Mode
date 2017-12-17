# Windows 10 - Disable Game Mode

Until the Windows 10 Fall Creators Update there was a simple switch to disable the Windows 10 Game Mode.

Now you have to disable the Game Mode via the Windows registry.

## Disable

Create a new value named `AllowAutoGameMode` in `HKEY_CURRENT_USER\Software\Microsoft\GameBar

Set the value as `DWORD 32 bit` with following value data (hex): 0

If you want to enable it again, just set the value to 1.
