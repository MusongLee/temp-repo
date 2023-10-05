# CLI(Command Line Interface)

## >  
- redirect output using ">" after a command (e.g., ls) to create and save the output in a file.  
- $ ls -lh > file_list.txt  
- Command "cat" displays the content of a text file.  
- $ cat file_list.txt  
<hr/>  

## >>
- Using “>>” appends output to an extising file(if it already exitsts), or create and write to a new file if it doesn’t exist.
- $ ls -lh >> file_list.txt  

<hr/>

## <
- By default, standard input is from keyboard.
- You can redirect input from a file using “<”.
- You can mix “<“ and “>” together in a single line.
- $ sort < words.txt > sorted_words.txt
<hr/>

## Pipelines |
- Pipeline feeds output of previous command to input of next command.
- command1|command2|command3|…
<hr/>

## Permissions 
- Linux is a multi-user system.
- Files and directories have a permission assigned differently to owner/group/others.
- rwx = read write execute
  
- "chmod" changes permissions
- $ chmod 600 some_file

6 = 110 = rw- for owner  
0 = 000 = --- for group  
0 = 000 = --- for others

rwx = 111 in binary = 7  
rw- = 110 in binary = 6  
r-x = 101 in binary = 5  
r-- = 100 in binary = 4  
<hr/>

## Superuser
- A superuser has all system administation authority.
- Some commands need superuser's privilleges.
- Put "sudo" before the command if you are a superuser.
- Type "exit" to get out of a superuser session. 
