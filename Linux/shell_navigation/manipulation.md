#  Wildcards
 <pre>Wildcards allow you to select filenames based on patterns of characters. The table below lists the wildcards and what they select:</pre>
 |Wildcard|Example|Meaning|
 |--------|-------|-------|
 |   *   | **ls &nbsp;  -l &nbsp;l*** |Matches all files with names starting with l (which is the prefix) and ending with one or more occurrences of any character.|
 |    **?**    | **ls &nbsp;l?st.sh**    | Matches all files with names beginning with l followed by any single character and ending with st.sh (which is the suffix).  |
 |   **[ ]**    |  **ls l[aeiou]st.sh** | Matches all files with names starting with l followed by any of the characters in the square bracket but ending with st.sh.|
 |   **[!  ]**    |  **ls l[!aeiou]st.sh** | Matches all files with names starting with l and not followed by any of the characters in the square bracket but ending with st.sh.|
 | **[0-9][a-z0-9][0-9]** |**ls users-[0-9][a-z0-9][0-9]***|This command will match all files whose name starts with users-, followed by a number, a lower case letter or number, then a number and ends with one or more occurrences of any character.



- # cp  [ *copy files and directories* ]
<pre>The cp command copies files and directories. It can copy a single file or multiple files.</pre>

|Command	|Results|
|-----------|-------|
| **cp file1 file2** |	Copies the contents of file1 into file2. If file2 does not exist, it is created; otherwise, file2 is silently overwritten with the contents of file1.|
| **cp -i file1 file2** |	Like above however, since the "-i" (interactive) option is specified, if file2 exists, the user is prompted before it is overwritten with the contents of file1.|
| **cp file1 dir1**	|Copy the contents of file1 (into a file named file1) inside of directory dir1.|
| **cp -R dir1 dir2** |	Copy the contents of the directory dir1. If directory dir2 does not exist, it is created. Otherwise, it creates a directory named dir1 within directory dir2.|

- # mv  [ *move or rename files and directories* ]
<pre>The mv command moves or renames files and directories. It can move one or more files to a different directory.</pre>
|Command    |	Results|
|-----------|----------|
| **mv file1 file2** |	If file2 does not exist, then file1 is renamed file2. If file2 exists, its contents are silently replaced with the contents of file1.|
| **mv -i file1 file2** |	Like above however, since the "-i" (interactive) option is specified, if file2 exists, the user is prompted before it is overwritten with the contents of file1.|
| **mv file1 file2 dir1** |	The files file1 and file2 are moved to directory dir1. If dir1 does not exist, mv will exit with an error.|
| **mv dir1 dir2** |	If dir2 does not exist, then dir1 is renamed dir2. If dir2 exists, the directory dir1 is moved within directory dir2. |


- # rm  [ *remove files and directories* ]
<pre>The rm command removes (deletes) files and directories. Using the recursive option (-r), rm can also be used to delete directories:</pre>

|Command|	Results|
|-------|----------|
| **rm file1 file2** |  Delete file1 and file2.|
| **rm -i file1 file2** | 	Like above however, since the "-i" (interactive) option is specified, the user is prompted before each file is deleted.|
| **rm -r dir1 dir2** |	Directories dir1 and dir2 are deleted along with all of their contents.|

- # mkdir [ *create directories* ]
<pre>The mkdir command is used to create directories.</pre>