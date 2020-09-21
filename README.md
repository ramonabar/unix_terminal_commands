
# Unix Commands Cheatsheet    

## **ls**   
*Lists contents of a directory.*   
    
    Usage:
    Without arguments: Lists contents of current directory   
    With arguments: Lists contents of given directory   
    
    Example Usage:
    ls
    ls ~/
    ls -a    
    
    
 ## **cd**   
*Changes directory.*   

    Usage:   
    Without parameters: Changes to user's home directory.   
    With an argument: Changes to given directory.   
    
    Example Usage:   
    cd
    cd test  
    
    
 ## **pwd**   
*Path to Working Folder.*   

    Usage:   
    Allways without arguments: Checks what is the current folder you are in.   
       
    Example Usage:   
    pwd
   

 ## **mkdir**   
*Makes a directory.*   

    Usage:   
    Allways with an parameter: is a command to make a folder. *Test* is the name you gave to the folder.    
    
    Example Usage:   
    mkdir test  
    
    
  ## **. and ..**   
*Targets current or parent directory.*   

    Usage:   
    Allways after a command: **.** Targets the current directory. _Test_ is the current folder.  
    Allways after a command: **..** Targets the parent directory.     
    
    Example Usage:   
    ls ./test
    cd ..  


## **man**   
*Invokes the built-in manual and shows how commands work and what arguments you can give to them.*   

    Usage:   
    Allways after a command: **.** Targets the current directory. *Test* is the current folder.  
    Allways after a command: **..** Targets the parent directory.     
    
    Example Usage:   
    ls ./test
    cd ..  
    
    
 ## **touch**
 *Creates a file in the current directory*
 
    Usage:
    Allways with an parameter: is a command to make a file. *Hello* is the name you gave to the file.    
    
    Example Usage:   
    touch hello.py  
    
    
 ## **cp**
 *Copy: use this command to copy files or folders*
 
    Usage:
    First argument for the cp command the **source file** and the second argument is the **destination file**.   
    To copy directories pass additional argument **-r** (*recursive operation*).      
    
    Example Usage:   
    cp testfile testfile_copy   
    cp  -r testdir testdir_copy   
    
    
 ## **mv**
 *Move: use this command to move or rename files or folders*   
 
    Usage:
    First argument for the mv command the **source file** and the second argument is the **destination file**.   
     
    Example Usage:   
    mv testfile testfile_copy   
   
   
 ## **rm**
 *Remove: use this command to remove or rename files or folders*     
 
    Usage:   
    To remove files: first the command for the rm and then the name of the file.     
    To remove directories pass additional argument **-r** (*recursive operation*).       
     
    Example Usage:     
    rm testfile      
    rm -r testdir   
   
   
  ## **~**
 *Tilde: points to home folder*     
 
    Usage:   
    Use the **~** character to navigate to your home directory ot to move a file from a current directory to our **home/testdir/code** folder.   
     
    Example Usage:     
    mv testfile ~/testdir/code/testfile    
    cd ~/tesstdir/code   
    
    
 ## **clear**
 *Clear the terminal*     
 
    Usage:   
    Use *clear* command to clear the terminal.   
     
    Example Usage:     
    clear    
    
    
 ## **history**
 *Shows the commands that you have used*     
 
    Usage:   
    Use *history* command to view the commands you have used.   
     
    Example Usage:     
    history    
