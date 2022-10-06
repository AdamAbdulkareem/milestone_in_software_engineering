# File System Organization
 The files on a Linux system are arranged in what is called a hierarchical directory structure. This means that they are organized in a tree-like pattern of directories (called folders in other systems), which may contain files and subdirectories. The first directory in the file system is called the root directory. The root directory contains files and subdirectories, which contain more files and subdirectories and so on.

 One important difference between Windows and Unix-like operating systems such as Linux is that Linux does not employ the concept of drive letters. While Windows drive letters split the file system into a series of different trees (one for each device), Linux always has a single tree. Different storage devices may be different branches of the tree, but there is always just a single tree.

- # pwd [ *print working directory* ]
The directory we are standing in is called the working directory. To see the name of the working directory, we use the pwd command.
- # cd [ *change working directory* ]

To change the working directory (where we are standing) we use the cd command. To do this, we type cd followed by the pathname of the desired working directory.
 A pathname is the route we take along the branches of the tree to get to the directory we want.</br>Pathnames can be specified two different ways; absolute pathnames or relative pathnames
 An absolute pathname begins with the root directory and follows the tree branch by branch until the path to the desired directory or file is completed.
 A relative pathname starts from the working directory. To do this, it uses a couple of special notations to represent relative positions in the file system tree. These special notations "." and ".."
  The "." notation refers to the working directory itself and the ".." notation refers to the working directory's parent directory.


        
