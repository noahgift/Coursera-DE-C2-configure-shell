# Coursera-DE-C2-configure-shell
Learn to configure the shell environment by editing .bashrc

![Config == Automation](https://user-images.githubusercontent.com/58792/142741497-f0c58775-c85f-4185-9657-9d2c77e7e546.png)
![bash-config](https://user-images.githubusercontent.com/58792/142743753-e787d965-a15f-43c8-a07a-296bf311fbef.png)

## Goal:   Learn to configure 

Let's practice configuring the Bash shell

### Part 1: Open ~/.bashrc and edit it

1.  Edit the Bash configuration file `~/.bashrc` by using Vim, `vim ~/.bashrc`  or opening the Visual Studio Code Editor
2.  Add the following statements at the end of the file:

```
export API="API-Key-Goes-Here"
echo "This is an example of using a variable at shell launch: " $API

```

3.  Test this out by sourcing the new config:  `source ~/.bashrc`.  What did you see?

### Part 2:  Open a second shell and interact with new environment

1. Open a new shell.  What did you see?
2. Echo the variable $API `echo $API`
3. What do you see?

### Part 3:  Create an alias in ~/.bashrc and use it

1.  Edit the Bash configuration file `~/.bashrc` by using Vim, `vim ~/.bashrc`  or opening the Visual Studio Code Editor
2.  Add the following statements at the end of the file:

```
alias root="cd /"

```
3. Test this out by sourcing the new config:  `source ~/.bashrc`.  What did you see when you type in `alias`?
4. What do you see when you type in `root`?  Why could this be helpful to you personally?
