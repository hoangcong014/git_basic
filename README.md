# Git Basic
  
## Ghi chú lại những thao tác liên quan đến Git
  
  
### Thêm Git Bash vào context menu Windows Explorer 
  
https://stackoverflow.com/questions/24386657/how-to-add-a-open-git-bash-here-context-menu-to-the-windows-explorer

### Long path file on
  
#### Your project sometimes has a file with a long path, Gitlab Runner will cause an error when clone your project, to fix it, run the below command with admin privilege:
  
    git config --system core.longpaths true
