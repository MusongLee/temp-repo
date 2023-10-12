# Git

System level: --system option. Affects all uses and repositories on the system(administrative)    
file:/etc/gitconfig  
Global(user) level: --global option. Affects all repositories of a current user    
file:~/.config/git/config  
Local level: --local option. Specific to the current repository    
file: .git/gitconfig   

$ git config --global user.name "Musong Lee"    
$ git config --global user.email your-email-address@gachon.ac.kr  
$ git config --global init.defaultBranch main  

$ git config --list  
$ git config --list --show-origin  

### Initializing a Repository in an Existing Directory  
$ git init  
### Checking Repository Status  
$ git status  
### Adding a new file to be staged(tracked)  
$ git add [file_name]  
### Adding all files to be staged(tracked)  
$ git add .  
### Unstaging a file  
$ git rm -cached[file_name]  
### Ignoring a file  
.gitignore file
