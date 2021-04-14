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
```

### Bookmarks

Usage: `git: cc: *.cs`

# Search in git repo
- name: `git`
- search: `"C:\Users\coenm\source\" !.nuget !.sonarlint !.tmp`
- macro: `git`

# Search in git repo
- name: `Exclude compiled`
- search: `!bin\ !obj\`
- macro: `cc`

# visual studio extensions
- name: `Visual studio extensions`
- search: `ext:cs;csproj;sln;editorconfig`
- macro: `vsext`
