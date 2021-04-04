| Option | Meaning |
| ------ | ------- |
| -a, -- | Archive. Copy the files and directories and all of their attributes, including ownerships and permissions.  Normally, copies take on the default attributes for the user performing the copy.|
| -i, -- | Interactive.  Before overwriting an existing file, prompt the user for confirmation. |
| -r, -- | Recursive.  Recursively copy directories and their contents.  This option (or the -a option) is quired when copying directories |
| -u, -- | Update.  When copying files from one directory to another, only copy files that either don't exist or are newer than the existing corresponding files in the destination directory. This is useful when copying large numbers of files as it skips files that don't need to be copied.
| -v, -- | Verbose.  Display informative messaes as the copy is performed. |
| Examples | Examples|
| **cp** *file1 file2* | Copy file1 to file2.  If file2 exists, it is overwritten with the contents of file1. If file2 does not exist, it is created. |
| **cp** -i *file1 file2* | Same as previous command, except that if file2 exists, the user is prompted before it is overwritten |
| **cp** *file1 file2 dir1* | Copy file1 and file2 into directory dir1.  The directory dir1 must already exist. |
| **cp** dir1|* dir2 | Using a wildcard, opy all the files in dir1 into dir2. The directory dir2 must already exist|
| **cp** -r *dir1 dir2* | Copy the contents of directory dir1 to directory dir. If directory dir2 does not exist, it is created and, after the copy, will contain the same contents as directory dir1.  If directory dir2 exists, dir1 contents will be copied to dir2 |

 