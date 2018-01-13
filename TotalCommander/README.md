# Total Commander
I can commit my config file `wincmd.ini` but it contains also a lot of junk. Besides that, after updating the configuration like this (following these steps) i'm much more aware of the settings im updating. 

## Quick Search
Configuration -> Options -> Quick Search
- Quick Search: Letters with search dialog.
- Exact name match: both unchecked.

## Editor (F4)
Configuration -> Options -> Edit/View
- Editor for F4: `"C:\Program Files (x86)\Notepad++\notepad++.exe" "%1"`


## Reverse History
Using Alt + Down you can open the history which has the last visited folder at the bottom and the oldest at the top. To reverse this order, you have to update the `wincmd.ini` yourself:

```
[Configuration]
ReverseHistory=1
```

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


### Tortoise SVN commands
#### SVN Log
| Option     	| Value                       	                                |
|------------	|-------------------------------------------------------------- |
| Command    	| `C:\Program Files\TortoiseSVN\bin\TortoiseProc.exe`           |
| Parameters 	| `/command:log /path:"%P%N"`                                   |
| Start Path 	| `%P`                        	                                |
| Icon file  	| `C:\Program Files\TortoiseSVN\bin\TortoiseProc.exe` (icon 17) |
| Tooltip    	| SVN Log                     	                                |

#### SVN Update
| Option     	| Value                       	                                |
|------------	|-------------------------------------------------------------- |
| Command    	| `C:\Program Files\TortoiseSVN\bin\TortoiseProc.exe`           |
| Parameters 	| `/command:update /path:"%P%N"`                                |
| Start Path 	| `%P`                        	                                |
| Icon file  	| `C:\Program Files\TortoiseSVN\bin\TortoiseProc.exe` (icon 3)  |
| Tooltip    	| SVN Update                  	                                |


#### SVN Update
| Option     	| Value                       	                                |
|------------	|-------------------------------------------------------------- |
| Command    	| `C:\Program Files\TortoiseSVN\bin\TortoiseProc.exe`           |
| Parameters 	| `/command:update /path:"%P%N"`                                |
| Start Path 	| `%P`                        	                                |
| Icon file  	| `C:\Program Files\TortoiseSVN\bin\TortoiseProc.exe` (icon 3)  |
| Tooltip    	| SVN Update                  	                                |


#### SVN Commit
| Option     	| Value                       	                                |
|------------	|-------------------------------------------------------------- |
| Command    	| `C:\Program Files\TortoiseSVN\bin\TortoiseProc.exe`           |
| Parameters 	| `/command:commit /path:"%P%N"`                                |
| Start Path 	| `%P`                        	                                |
| Icon file  	| `C:\Program Files\TortoiseSVN\bin\TortoiseProc.exe` (icon 4)  |
| Tooltip    	| SVN Commit                  	                                |


#### SVN Revert
| Option     	| Value                       	                                |
|------------	|-------------------------------------------------------------- |
| Command    	| `C:\Program Files\TortoiseSVN\bin\TortoiseProc.exe`           |
| Parameters 	| `/command:revert /path:"%P%N"`                                |
| Start Path 	| `%P`                        	                                |
| Icon file  	| `C:\Program Files\TortoiseSVN\bin\TortoiseProc.exe` (icon 6)  |
| Tooltip    	| SVN Revert                  	                                |


#### SVN Cleanup
| Option     	| Value                       	                                |
|------------	|-------------------------------------------------------------- |
| Command    	| `C:\Program Files\TortoiseSVN\bin\TortoiseProc.exe`           |
| Parameters 	| `/command:cleanup /path:"%P%N"`                               |
| Start Path 	| `%P`                        	                                |
| Icon file  	| `C:\Program Files\TortoiseSVN\bin\TortoiseProc.exe` (icon 7)  |
| Tooltip    	| SVN Cleanup                  	                                |