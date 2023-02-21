
# Terminal glossary

### NAVIGATION
|||
|------|------|
|   cd  |   Go to main directory    |
|   cd ..   |    Go to parent directory  |
|   cd - | Go back |
|   cd  /"directory | Change directory|
|   cd /qa\ s\`dan     |   Change directory with "bash" names (for example folders name - "qa s`dan")|

  
   
### ACTION WITH FILES

|||
|------|------|
|   open "filename"|    Open the file|
|   cp “filename” “newfilename”|    copy file |
|   cp “filename” “~/Desktop/someFolder/newFileName”|    Copy file to another directory |
|    mv “filename” “path/to/new/file/location/fileName” | Move a file |
|   mv “filename” “newFileName” |   Rename a file|
|   touch myfile.txt |  Create a text file |
|    mkdir "someName" |     Create the folder |
|    rmdir "folderName" |   Remove EMPTY folder (only for Empty) |
|   rm -R “/path/to/root/directory”|    Remove nested directories |
|    ditto -V MyFolder MyNewFolder |    Copy contents of a folder to a new folder |
| vim fileName| Open file in txt editor|
| (in VIM) :x | save and close VIM Editor|

### ANOTHER

|||
|------|------|
|   open .  | Open folder where we now|
|   open ../someFileOrFolder    |   Open File or Folder|
|   ls  |   Listing Directory|
|   clear   |  Clear the Terminal|
|   pwd |    Where am I now|
|    man ls |    Look the Manual ls commands. For Exit - push "q" |
|   ls -lSh |    Sort by Size (Kb, Mb). "S" - exactly UpRegister|
|   whatis "command"    |   what is this Command (whatis pwd, whatis mkdir etc)|

### VIM commands
|||
|------|------|
| i | - перейти в режим редактирования |
|yy | - копирование текущей строки в буфер |
|v | - выделение текста, используется для копирования участков текста | 
|y | - копировать выделенный текст | 
|d |- удалить выделенный текст |
|dd |- удалить одну строку - на которой курсор|
|d 4 d |- удалить 4 строки|
|р |- вставка из буфера под курсором | 
|P |- вставка из буфера перед курсором |
|u |- назад - отменить последнее действие (аля ctrl+z)|
|:w |- сохранить изменения |
|:x |- сохранить все изменения и выйти |
|:q!| - выйти без сохранения изменений|

