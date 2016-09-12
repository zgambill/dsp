# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

---

###Q1.  Cheat Sheet of Commands  

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do, focused on things that are new, interesting, or otherwise worth remembering.

- **touch <file>** -- creates a new file
- **cp <file/directory> <directory>** -- copies a file/directory into another file/directory
- **rm [-r] <file/directory>** -- removes a file; use -r to remove a directory and all child directories/files
- **mv <file/directory> <file/directory>** -- moves a file/directory to another file/directory. Move multiple files by making the last argument the destination.
- **echo <string>** -- prints the given string
- **[command] > [file]** -- redirects standard output into a file and overwrites all original content
- **[command] >> [file]** -- redirects standard output into a file after original content
- **[command] < [file]** -- takes a [file] as standard input for the [command]
- **cat <file>** -- outputs contents of a file
- **<command> | <command> ** -- pipe: takes standard output of the command and makes it the input of a second command
- **wc** -- line count, word count, character count
- **sort** -- sorts standard input alphabtically for the standard output
- **uniq** -- removes lines from a file that are the same and adjacent
- **grep [-i] <string> <file/directory/input>** -- finds all lines with the "string". Use "-i" to make "string" case insensitive
- 
 
---

###Q2.  List Files in Unix   

What do the following commands do:  
`ls` 
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  



- 'ls' lists files and directories within the working directory
- 'ls -a' lsits all files and directories within the working directory, including those starting with "." that are normally hidden
- 'ls -l' lists all files/directories within the working directory in long format
- 'ls -lh' same as -l, but lists human-readble file size
- 'ls -lah' lists ALL filles/directories, even those hidden, in long format with human-readable file size
- 'ls -t' lists all files/directories and orders them by date of last modification


---

###Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > REPLACE THIS TEXT WITH YOUR RESPONSE

---

###Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > REPLACE THIS TEXT WITH YOUR RESPONSE

 

