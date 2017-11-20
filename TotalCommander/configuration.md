# Total Commander
I can commit my config file `wincmd.ini` but it contains also a lot of junk. Besides that, after updating the configuration like this (following these steps) i'm much more aware of the settings im updating. 

## Quick Search
Configuration -> Options -> Quick Search
- Quick Search: Letters with search dialog.
- Exact name match: both unchecked.

## Editor (F4)
Configuration -> Options -> Edit/View
- Editor for F4: `"C:\Program Files (x86)\Notepad++\notepad++.exe" "%1"`


## Button bar
Configuration -> Button Bar. Here i've added a few buttons. This button configuration is saved as `DEFAULT.BAR`

### Git Bash

| Option    	|  Value                             	|
|------------	|-----------------------------------	|
| Command    	| `C:\Program Files\Git\bin\sh.exe`  	|
| Parameters 	| `--login -i`                        	|
| Start Path 	|                                   	|
| Icon file  	| `C:\Program Files\Git\git-bash.exe` 	|
| Tooltip    	| Git Bash Here                     	|


### Beyond Compare
| Option     	| Value                                                  	|
|------------	|--------------------------------------------------------	|
| Command    	| `C:\Program Files (x86)\Beyond Compare 3\BCompare.exe` 	|
| Parameters 	| `%X%P%N %X%T%M`                                          	|
| Start Path 	| `C:\Program Files (x86)\Beyond Compare 3\`               	|
| Icon file  	| `C:\Program Files (x86)\Beyond Compare 3\BCompare.exe`   	|
| Tooltip    	| Beyond Compare                                         	|

### Dos Command
| Option     	| Value                       	|
|------------	|-----------------------------	|
| Command    	| `cm_ExecuteDOS`              	|
| Parameters 	|                             	|
| Start Path 	|                             	|
| Icon file  	| `C:\Windows\System32\cmd.exe` |
| Tooltip    	| Command                     	|