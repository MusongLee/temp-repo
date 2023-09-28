# Git Bash
### Shell Commands
- $pwd = shows the current path in a hierarchical directory
- $cd = change directory (Case sensitive)
- $ls = list files and directories
- $clear  

  
#### arguments :  

[directory name]  
/ root   
. current directory  
.. upper-level directory  
~ home of current user  
/[directory name]: absolute path  
./[directory name]: relative path  
../[directory name]: relative path  

#### options :  

- -l show detailed information (long format) ($ls -l)
- -lh same as above, but size in units (-l=2705, -lh=2.7K)  

More on ls   
> ls : List the files in the working directory  
> ls /bin : List the files in the /bin directory (or any other directory we care to specify)   
> ls -l : List the files in the working directory in long format   
> ls -l /etc /bin : List the files in the /bin directory and the /etc directory in long format   
> ls -la .. : List all files (even ones with names beginning with a period character, which are normally hidden) in the parent of the working directory in long format


### Manipulation
- $cp : copy files and directories  
- $mv : move files and directories or rename them
- $rm : delete files and directories permantely and irreversevely!!!
- $mkdir : make a new directory
- Wildcards
> \* : All filenames  
> g* : All filenames that begin with the character "g"  
> b*.txt : All filenames that begin with the character "b" and end with the characters ".txt"   
> Data??? : Any filenames that begins with the characters "Data" followed by exactly 3 more characters


### Exiting terminal 
- $exit
