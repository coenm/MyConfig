# Everything

http://www.voidtools.com/

## Hotkey

Tools -> Options -> General -> Keyboard
Set "Toggle Window Hotkey" to Ctrl+Shift+Q

## Exclude list

Tools -> Options -> Indexes -> Exclude
 
 - Check 'Enable exclude list'

### Exclude list

```
C:\Temp
D:\Projects\**\obj
C:\$Recycle.Bin
D:\$Recycle.Bin
_ReSharper.Caches
_NCrunch_*
.svn
.git
.tmp.drivedownload
$Recycle.Bin
%userprofile%\AppData

```

### Bookmarks

Usage: `git: cc: vsext: abcdef`

# Search in git repo
- name: `git`
- search: `"C:\Users\coenm\source\" !.nuget !.sonarlint !.tmp`
- macro: `git`

# Exclude compiled
- name: `Exclude compiled`
- search: `!bin\ !obj\`
- macro: `cc`

# visual studio extensions
- name: `Visual studio extensions`
- search: `ext:cs;csproj;sln;editorconfig;md;config;DotSettings`
- macro: `vsext`
