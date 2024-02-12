1. Completed.  
2. We use .md, which stands for Markdown, and it is used because it allows us to use Markdown syntax to to style and format text.
3. No  
4. Yes  
5. The purpose of a .git folder is to hold all work in a project, once it is committed to the repository.  
6. The command cd is used to change the directory. If the directory is not specified after, it will change to home.  
7. The command ls -a is used to list everything in the current directory, including hidden files.
8. The command pwd stands for "print working directory," and it will list what directory you are actively in, as well as the absolute path to said directory.  
9. The three different areas include the working directory, the staging area, and the .git directory. The working directory is where you create any changes you would like to create to your project. The data is then sent to the staging area, where it holds and stores the information to later be committed. Once committed, it ends up in the .git directory, or the repository. Once here, the changes become permanent.  
10. A VCS records changes to files over a period of time that can be recalled later.
11. Six major benefits to a distributed VCS are that you can work with others on a project, each callaborator have a copy of the project to work on, the changes each person makes are synchronized with the rest of the group, the evolution of all files are tracked, the data is backed up, and the projects are decentralized.
12. Local VCS, Centralized VCS, and Distributed VCS.  
13. Git is the software that allows for data to be pushed and pulled from multiple different servers/computers. GitHub is the central repository that we use to actually store the data, using Git.  
14. Git status is used to check the status of the project beign worked on.  
15. Git push --all is used to push all of your commits and data from the local repository to the remote repository.  
16. Git pull is used to pull all of the commits and changed made by other collaborators onto your local respository from the remote repository.  
17. Markdown is a type of syntax that is used to style text on the web.
18. You make text boldface as by surrounding it with two asterisks on both ends of the text, as **such**.  
19. You make text italic as by surrounding it with one asterisk on both ends of the text, as *such*.  
20. Git innit.  
21. In directory path names, . will direct you to the previous directory, and .. will direct you to the home directory. They stand in place for each.
22. 3) $ pwd  
/c/Users/16824  
4) $ mkdir testdir  
5) Completed.  
6) No, this is not currently a git repository because I have not created one yet using used the command git init. This can be proven using the command ls -a, which lists all files within my current directory, including hidden files, such as a potential .git file.  
7) I would make this folder a git project by using the command git init.  
8) The vim command allows me to add and/or edit text within a file. After creating a README.md file, I saved and exited out of the file by first exiting the text box by clicking escape, then by typing :wq, then enter.
9) $ cat README.md  
This is a README.md file for the test project of quiz1.
10) $ git status  
On branch master  
No commits yet  
Untracked files:  
  (use "git add <file>..." to include in what will be committed)  
        README.md  
nothing added to commit but untracked files present (use "git add" to track)
11) $ git add --all  
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
$ git commit -m"This is my first commit for quiz1."  
[master (root-commit) bd5ca32] This is my first commit for quiz1.  
 1 file changed, 1 insertion(+)  
 create mode 100644 README.md
12) $ git status  
On branch master  
nothing to commit, working tree clean  
13) Using this command, I removed the directory testdir. The command -rf will ensure this directory is only deleted and no adverse effects occur.

   
23.  A relative path directs you to a file/folder in respect to another, wheras an absolute path lists the full path from the home directory all the way to the file in question. It is more appropriate to use relative paths in our GitHub projects. This is because, if files are ever changed, an absolute path would be deemed unusable in the future.
24. The command to see all git commands is git help -a  









 


