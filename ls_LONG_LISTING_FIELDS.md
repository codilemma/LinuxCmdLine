### ls -l
#### returns:

**-rw-r--r-- 1 root root   32059 2017-04-03 11:05 oo-cd-cover.odf**

| Field | Meaning |
| ----- | ------- |
| -rw-r--r-- | Acess rights to the file.  The first character indicates the type of file. Among the different types, a leading dash means a regular file, while **a d** indicates a directory. The next three characters ar ethe access rights for the file'sowner, hte next three are for memebers of the file's group, and the final three are for everyone esle. **See Chapter 9** |
| 1 | File's number of hard links. See "Symbolic Links" on page 21 |
| root | The username of the file's owner. |
| root | The name of the group that owns the file |
| 32059 | Size of the file in bytes |
| 2017-04-03 11:05 | date and time of the file's last modification
| 00-cd-cover.odf | Name of the file |

