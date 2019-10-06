# mkdir (make a new directory)


* To create a new folder, we call the "make directory" command

![Image of mkdir](/images/mkdir.png)

* It takes in a directory name as an argument, and then creates a new directory in the current working directory
* It is important to note that the user executing this command must have enough permissions to create a directory in the parent directory, or they may recieve a ‘permission denied’ error.
* -m: This option is used to set the file modes, i.e. permissions, etc. for the created directories. 
* The syntax  below specifies that the directories created give access to all the users to read from, write to and execute the contents of the created directories 
* mkdir -m a=rwx [directories]



