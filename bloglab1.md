# Lab Report 1

## cd examples
![Image](cd.png)
* The purpose of the `cd` terminal command is to move the user to different directores.
* The working directory is `/home/lecture1`, because that is where all of the commands can be ran. The only thing before this working directory is the home directory.
* The `cd` command for the first example did not work, because the user did not add any input to what directory they wished to enter. As no arguments were entered, the command did not know what to proccess The second example did work, because as evident in the next command, the user `user@sahara` was clearly shown to have moved into the directory specified from the home directory `/lecture`. As the directory was specified, it was able to moce into said directory. The third example did not work, because the user attempted to move into a file. As files are not directories, the user cannot move into them. 

## ls examples
![Image](ls.png)
* The purpose of the `ls` terminal command is to list the files of a directory and show them to the user.
* The working directory is `/home/lecture1`, because that is where all of the commands can be ran. The only thing before this working directory is the home directory.
* The ls command for the first example did work, because the user was already in the `/lecture1` directory and was able to see the different directories and files inside that directory. Even if the user was not in `/lecture1` and in the home directory, the command would have still worked and show lecture1 as a directory available. The seccond example did work, as it showed the different files inside the `/messages` directory inside the `/lecture1` directory and generated the availabe files. The third example worked, because it was able to show the only file inside the Hello.java file (which is the Hello.java file). This output it expected, because one can ls files as well as directories.

## cat examples
![Image](cat.png)
* The purpose of the `cat` command is to concatenate the data in a file and print them out in terminal for the user to see what is in the file.
* The working directory is `/home/lecture1`, because that is where all of the commands can be ran. The only thing before this working directory is the home directory.
* The `cat` command for the third example did not work, because no output was produced. This is expected, because as no arguments were given the terminal was not able to figure out what exactly to concatenate. The first example worked and output was passed. We know that this output is expected, because an argument for which file to concactinate was passed, and as such the terminal output reflects the contents of said file. The second example did not work and no output was generated. This is expected, because the argument passed was a directory, and the cat command does not work on directories, it only works on files.
  
