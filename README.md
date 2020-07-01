
**INIT**  
git init  
git add .  
git commit -m "komentaaars"  
git remote add origin https://github.com/Valdiz86/testing.git  
git push -u origin master  

**PUSH ALL FILES**  
git add *  
git commit -m "Jauns komentaars"  
git push  

**PUSH SELECTED FILE OR FOLDER**  
git add jauns_fails.php  
git commit -m "komentaars speciaali izveletajam folderim vai failam"  
git push  

**REMOVE FOLDER OR FILE no githuba**  
git rm -r --cached FolderName  
git commit -m "Removed folder from repository"  
git push

**RENAME FOLDER OR FILE**  
git mv oldFileOrFolder newFileOrFolder  
