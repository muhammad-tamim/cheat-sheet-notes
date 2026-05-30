<h1>Cheat Sheet Notes</h1>

- [CMD Commands:](#cmd-commands)
  - [Common Commands:](#common-commands)
  - [Exercise:](#exercise)
- [Windows Shortcuts:](#windows-shortcuts)
- [Chrome Shortcuts:](#chrome-shortcuts)
- [VS Code Shortcuts:](#vs-code-shortcuts)

# CMD Commands: 
CMD (Command Prompt) is a command-line interface built into Windows that allows us to interact computer using text commands instead of a graphical interface.

To Open it: 

```bash
Win + R = type cmd = Enter
// or
Win = search cmd = Enter
```
## Common Commands: 

- `dir`: Lists all files and folders in the current directory.
  
![image](./assets/images/cmd/dir.png)

- `PartitionName:`: Change the current partition (drive).

![alt text](./assets/images/cmd/partitionName.png)

- `cd directory_name`: changes to a specified directory.

![alt text](./assets/images/cmd/cd.png)

Note: For changes multiple directories at a time: `cd directory_name\directory_name\directory_name`

- `cd ..`:  Out form one directory level.

![alt text](./assets/images/cmd/cd1.png)

- `cd ../..`: Out form two directory levels.

![alt text](./assets/images/cmd/cd2.png)

- `cd \`: Go to root:
  
![alt text](./assets/images/cmd/cdroot.png)

- `mkdir`: Creates a directory (folder).

![alt text](./assets/images/cmd/mkdir.png)

Note: For creates nested directory: `mkdir src\modules\notes`
Note: For creates multiple directory at a time: `mkdir src src\controllers src\routes src\models`

- `rmdir`: Delete a directory (folder).

![alt text](./assets/images/cmd/rmdir.png)

- `echo. > filename.extension`: Create a empty file.

Note: We can use `type nul > filename.extension`  instead of `echo. >filename.extension`

![alt text](./assets/images/cmd/echo.png)

- `echo hello world > text.txt`: Creates a file with content.

Note: we can use `type hello world > text.txt` instead of `echo hello world > text.txt` 

![alt text](./assets/images/cmd/echo1.png)

- `type filename.extension`: show text based file (txt, html, c, c++, etc).

![alt text](./assets/images/cmd/type.png)

- `del filename.Extension`:  Deletes a file.

![alt text](./assets/images/cmd/del.png)

- `cls`: Clears the CMD screen.

- `Tab`: Auto-completes file and folder names.

- `up arrow` and `down arrow`: For navigating history previous and next commands.


## Exercise: 
Create this structure using only CMD:

```bash
src/
│
├── app.ts
├── server.ts
│
├── config/
│   ├── db.ts
│   └── env.ts
│
├── modules/
│   └── notes/
│       ├── notes.route.ts
│       ├── notes.controller.ts
│       ├── notes.service.ts
│       ├── notes.validations.ts
│       └── notes.types.ts
│
├── middlewares/
│   └── validate.ts
```

- commands: 
  
```bash
mkdir src

mkdir src\config
mkdir src\modules
mkdir src\modules\notes
mkdir src\middlewares

type nul > src\app.ts
type nul > src\server.ts

type nul > src\config\db.ts
type nul > src\config\env.ts

type nul > src\modules\notes\notes.route.ts
type nul > src\modules\notes\notes.controller.ts
type nul > src\modules\notes\notes.service.ts
type nul > src\modules\notes\notes.validations.ts
type nul > src\modules\notes\notes.types.ts

type nul > src\middlewares\validate.ts
```

- Output: 

```bash
// To verify
tree src /f
```

```bash
C:\Users\Tamim\Desktop\test\testDirectory>tree src /f
Folder PATH listing
Volume serial number is 000000C0 D2F2:FC70
C:\USERS\TAMIM\DESKTOP\TEST\TESTDIRECTORY\SRC
│   app.ts
│   server.ts
│
├───config
│       db.ts
│       env.ts
│
├───middlewares
│       validate.ts
│
└───modules
    └───notes
            notes.controller.ts
            notes.route.ts
            notes.service.ts
            notes.types.ts
            notes.validations.ts

```

# Windows Shortcuts: 
- `Alt + Tab`: Switch between open apps.

![images](./assets/images/windows/alt-tab.gif)

- `Windows + Tab`: Open task view.

![images](./assets/images/windows/win-tab.gif)

- `Windows + Ctrl + left / right`: Switch between virtual desktops.

![images](./assets/images/windows/win-ctrl-left-right.gif)

- `Windows + Ctrl + d / Windows + Ctrl + F4`  = Add a virtual desktop / Remove current virtual desktop.

![images](./assets/images/windows/windows-ctrl-d.gif)
![images](./assets/images/windows/win-ctrl-f4.gif)

- `Windows + e / Ctrl + w` = Open file Explorer / Close active window.

![images](./assets/images/windows/win-e-ctrl-w.gif)

- `Alt + F4`: Close active window. (If no active window is present, a shutdown box appears.)

![images](./assets/images/windows/alt-f4.gif)

- `F2`: Rename folder or file 

![images](./assets/images/windows/f2.gif)

- `Windows + v`: open clipboard

![images](./assets/images/windows/win-v.gif)

- `windows + Down Arrow (double Click) / windows + Up Arrow (double Click)`: Minimize / Un-minimize a app

![images](./assets/images/windows/win-down-win-up.gif)

- `windows + Left / Right / Up / Down Arrow`: Moved app on left/right/up/down.

![images](./assets/images/windows/win-left-right-up-down.gif)

- `windows + l`: Jump to the search bar:

![images](./assets/images/windows/win-l.gif)

# Chrome Shortcuts:

- `Ctrl + n`: Open a new window.

![image](./assets/images/chrome/ctrl-n.gif)

- `Ctrl + Shift + n`: Open a new window in incognito mode.

![image](./assets/images/chrome/ctrn-shift-n.gif)

- `Ctrl + T`: Open a new tab and jump to it.

![image](./assets/images/chrome/ctrl-t.gif)

- `Ctrl + Shift + Tab`: Jump to the previous open tab.

![image](./assets/images/chrome/ctrl-shift-tab.gif)

- `Ctrl + tab`: Jump to the next open tab.

![image](./assets/images/chrome/ctrl-tab.gif)

- `Ctrl + W`: Close the current tab.

![image](./assets/images/chrome/ctrl-w.gif)

- `Ctrl + K`:  Search form anywhere on the page.

![image](./assets/images/chrome/ctrl-k.gif)

- `Ctrl + R`: Reload
 
- `Ctrl + Shift + R`: Hard reload

- `Ctrl + Click a link`: Open a link in new tab

![image](./assets/images/chrome/ctrl-click.gif)

- `Ctrl + Shift + Click a link`: Open a link and jump to it.

![image](./assets/images/chrome/ctrl-shift-click.gif)

# VS Code Shortcuts: