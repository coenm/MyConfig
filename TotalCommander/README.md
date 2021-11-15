# Total Commander
All the settings will be stored in `wincmd.ini` and `DEFAULT.BAR`.

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

## Sort Method
Sorting a directory containing files such as `1.txt`, `2.txt`, .. `9.txt`, `10.txt` can be sorted alphabetically, but so have it sorted numeric you have to change the following setting:

Configuration -> Options -> Display
- Sort Method: 'Natural sorting: by character code and number'.


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
