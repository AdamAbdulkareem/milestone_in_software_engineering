Below points out an important concept about commands. Most commands operate like this:
<pre>command -options arguments</pre>
Where command is the name of the command, -options is one or more adjustments to the command's behavior, and arguments is one or more "things" upon which the command operates.

- # ls [ *list files and directories* ]
<pre>The ls command is used to list the contents of a directory.</pre>

|Command | Result |
|--------|--------|
|   ls   |List the files in the working directory|
| ls &nbsp; /bin |List the files in the /bin directory (or any other directory we care to specify)|
|ls&nbsp; -l	| List the files in the working directory in long format|
|ls &nbsp;-l &nbsp;/etc &nbsp;/bin|	List the files in the /bin directory and the /etc directory in long format|
|ls -la |List all files (even ones with names beginning with a period character, which are normally hidden) in the parent of the working directory in long format||

- # less [ *view text files* ]
Less is a program that lets us view text files. The less program is invoked by simply typing: <pre>less text_file</pre>
This will dispaly the file.

- # file  [ *classify a file's content* ]
The file command will examine a file and tell us what kind of file it is. To use the file program, we just type:
<pre>file name_of_file</pre>
