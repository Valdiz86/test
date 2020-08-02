
**INIT**  
git.exe file url:  
https://git-scm.com/download/win
```bash
git init  
git add .  
git commit -m "komentaaars"  
git remote add origin https://github.com/Valdiz86/testing.git  
git push -u origin master  
```
___
**PUSH ALL FILES**  
```bash
git add *
git commit -m "Jauns komentaars"  
git push  
```
  
add * means add all files in the current directory, except for files whose name begin with a dot. This is your shell functionality and Git only ever receives a list of files.  
  
add . has no special meaning in your shell, and thus Git adds the entire directory recursively, which is almost the same, but including files whose names begin with a dot.

add folder_name  
add test.extension
___
**PUSH SELECTED FILE OR FOLDER** 
```bash 
git add jauns_fails.php  
git commit -m "komentaars speciaali izveletajam folderim vai failam"  
git push  
```
___
**REMOVE FOLDER OR FILE no githuba**  
```bash
git rm -r --cached FolderName  
git commit -m "Removed folder from repository"  
git push
```
___
**RENAME FOLDER OR FILE**  
```bash
git mv oldFileOrFolder newFileOrFolder  
```