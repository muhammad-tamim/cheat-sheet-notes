<h1>Cheat Sheet Notes</h1>

- [CMD Commands:](#cmd-commands)
  - [Common Commands:](#common-commands)
  - [Exercise:](#exercise)
- [Chrome Shortcuts:](#chrome-shortcuts)
- [Windows Shortcuts:](#windows-shortcuts)
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

# Chrome Shortcuts:
# Windows Shortcuts: 
# VS Code Shortcuts: