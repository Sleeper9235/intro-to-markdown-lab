# How to create a file using the Terminal

![html banner](https://images.unsplash.com/photo-1629654291663-b91ad427698f?q=80&w=1074&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

##  Opening the Terminal: 
1. start by exploring the computer for the terminal application. Once located run that application.  

## Understanding the basics
* CLI - Command Line Interface - A text-based user interface (*UI*) used to run programs, manage files, and interact with the computer.
* Filesystem - Organized structure of the computer

## Breaking down the commands
* __pwd__ - Prints the working directory - Shows the current location of the user, better explained as the current directory (file/folder)

```
➜ intro-to-markdown-lab pwd
kylej/code/ga/labs/intro-to-markdown-lab
```

* __ls__ - Lists content of current folder
```
➜ intro-to-markdown-lab ls
README.md TUTORIAL.md
```
* __cd__ - Change Directory - changes user into designated directory if applicable. 
```
➜  intro-to-markdown-lab cd ..
➜  labs  
```
cd .. changed our current location to the parent location. Look at the result of pwd, what folder comes before the intro-to-markdown-lab? The same can be said if we wanted to move into a folder. 

```
➜ labs cd intro-to-markdown-lab
➜ intro-to-markdown-lab
```
* __mkdir__ - Make Directory - creates a directory (folder)

```
➜ intro-to-markdown-lab mkdir example
```

* __touch__ - Create an empty file 
```
➜ intro-to-markdown-lab touch index.html app.js style.css
```
The example above not only creates an index.html file in our current directory, in this case, intro-to-markdown-lab. But also creates a Javascript file named app and a CSS stylesheet named style.

## Putting it all together

```
➜  kylej cd code/ga/labs
➜  labs mkdir intro-to-markdown-lab
➜  labs cd intro-to-markdown-lab
➜  intro-to-markdown-lab touch index.html app.js style.css
➜  intro-to-markdown-lab ls
index.html app.js style.css
```