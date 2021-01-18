# FolderLocker
Open a text editor
Copy the code from locker.bat
Paste the code
Save it with any name you want with bat extension

title Folder Locker <- For this project the folder name will be Locker
if NOT EXIST Locker goto MDLOCKER <- For this project the folder name will be Locker
md Locker <- For this project the folder name will be Locker
echo Locker created successfully <- For this project the folder name will be Locker
if NOT %pass%==password123 goto FAIL <- For this project the password will be password123

These are the only lines you need to modify.
Enjoy!
