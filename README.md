git-breakdown
============

This is a Bash script that shows a breakdown for a Git repository. It will show a graph for the type of files, and 
another graph for commit authors.

![Screenshot](https://cloud.githubusercontent.com/assets/5659221/5065306/2f98c9ce-6de2-11e4-8382-dde1f561bce9.png)

## Usage

I prefer to copy this script somewhere in my path so it can be executed from anywhere. That's optional. But to use the script,
simply run it in any directory that contains a Git repository.

```
$ git-breakdown
file type           	 number of files
html                	 [    19]: #############################
js                  	 [    17]: #########################
css                 	 [     8]: ###########
json                	 [     3]: ###
png                 	 [     2]: ##
md                  	 [     2]: ##
yml                 	 [     1]:
opts                	 [     1]:
jshintrc            	 [     1]:
jade                	 [     1]:
gitignore           	 [     1]:

author              	 commits
TJ Holowaychuk      	 [   148]: #############################
Shuvalov Anton      	 [    67]: ############
Jonathan Ong        	 [    15]: ##
Andy Burke          	 [    14]: #
Dmitrii Pakhtinov   	 [    12]: #
Rico Sta. Cruz      	 [     8]:
```