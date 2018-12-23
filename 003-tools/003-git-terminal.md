# Git - Terminal Commands

1. watch [![YouTube](https://i.ytimg.com/vi/yTt0-NBHQ4s/default.jpg)](https://www.youtube.com/watch?v=yTt0-NBHQ4s)
2. open your GitHub account
3. create a new repository 
4. open IntelliJ IDE
5. open the terminal window 
6. `cd` to the directory where you would like your git repository
7. follow the `create a new repository on the command line` instructions provided by GitHub
8. add a new text file to your new repository
9. type `git status` and press `enter` (your text file should be listed in red)
10. type `git add .` and press `enter` (this will track all un-tracked files)
11. type `git status` and press `enter` (your text file should be listed in green)
12. type `git commit -m "initial commit"` and press `enter` (this will add your changes to the history of your local git repository)
13. type `git push origin master` and press `enter` (this will push your changes to GitHub)
14. go to your repository on GitHub and verify that the text file you added is listed
15. attach a link to your GitHub repository to this assignment

## Resources
1. (https://help.github.com/articles/creating-a-new-repository/)
2. (https://www.jetbrains.com/help/idea/settings-tools-terminal.htm)

## Key Concepts
1. `cd` stands for change directory (example: `cd Documents`)
1. `cd ..` changes the current location up one directory (example: if you were in a directory `~/Documents/stuff` `cd ..` would change your current location to `~/Documents`)
1. `ls` lists all of the files and directories in your current location. 
1. `cd ~` takes you back to your home user directory.  
1. `git init` followed by your repository name will create a new Git repository with the name you provide. 
1. `git status` lists the files and identifies which files have been staged to be versioned.  
    1. Red: not staged
    2. Green: staged
1. `git add` followed by the file name or directory you want to stage will stage the changes you specify.  
1. `git commit -m` followed by a descriptive message in double quotes will version your changes locally on your computer.  
1. `git push origin master` will push your locally versioned changes to the cloud on GitHub.
1. `git pull origin master` pulls changes that exist on GitHub to your local machine.  
