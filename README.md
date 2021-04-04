# The Linux Command Line, 2nd Edition
by Wiliam E. Shotts
https://learning.oreilly.com/library/view/the-linux-command/9781492071235/


## Book Notes
***
### Part 1: Learning the shell

#### P1 - Ch1: What is the SHELL?
    
  - Highlight text in the terminal to copy to buffer.  
    Press middle mouse button to paste copied text to terminal

#### P1 - Ch2: Navigation
    
  - dot(.) = Current working dir
  - dot-dot(..) = Parent dir
  - absolute dir = begins at root dir
  - relative dir = begins at working dir


#### P1 - Ch3: Exploring the system
 
  - ls (list dir contents), file (Determine file type),
    less (View file contents)
  - Options and Arguments
    * options modify command behavior
    * arguments enhance the options for further command modification
    * **command** *-opitons arguments*
  - long options consist of a word preceded by two dashes
    * ls -lt --reverse

  - ##### ls Command
  - **specify directory to list:** 
    * ls /usr
  - **list multiple dirs (home '~' and /usr):**
    * ls ~ /usr 
  - **list dir content details of specific dir (-l = long):**
    * ls -l /usr
  - **Long options word preceded by two dashes**
    * ls -lt --reverse
  - **See table .md's for more info**
    * ls_LONG_LISTING_FIELDS.md
    * ls_OPTION_TABLE.md
  
  - ##### file Command
  - **Will print a brief description of the file contents:**
    * **file** *filename*

  - ##### less Command
  - **shows file contents in the terminal**
    * **less** *filename*
    * to exit press **q**
    * fuck this use nano!!!!!!!


#### P1 - Ch4: Manipulating File and Directories.

  - **cp** = Copy files and directories
  - **mv** = Move/rename files and directories
  - **mkdir** = Create directories
  - **rm** = Remove files and directories
  - **ln** = Create hard and symbolic links

  - ##### Wildcards
    * Using wildcards (also known as *globbin*)
    * Allows you to select filenames based on patterns of characters. 
    * Can also be used in the GUI.  in Nautulus you can go to Edit -> Select Pattern  to filter files in the currently viewed directory.

  - ##### MKDIR - Creating Directories
    * **mkdir** *directory...*
    * Create multiple directories, **mkdir** *dir1 dir2 dir3*
  
  - ##### CP - Copy Files and Directories
    * Copy single file or directory from *item 1* to *item 2*
      * **cp** *item1 item2*
    * Copy multiple items (either files or directories) into a directory.
      * **cp** *item... directory*
      * see cp_OPTIONS.md for more info.

  - ##### MV - Move and Rename files.
    * Behaves just like the **cp** command.

  - ##### RM - Remove Files and Directories
    * -i,-r,-v options can be used.
    * -f, --force = Ignore nonexisten files and do not prompt.
    * rm is permanent!! There is no undo.
  
  - ##### LN - Create Links
    * Hard Links:
      * **ln** *file link*
      * every file has a hard link by default that gives it it's name.  
      * creates an additional directory entry for a file.
      * Limitation 1: cannot reference a file outside it's own file system. 
        (ie. not on the same disk partition as the link itself.)
      * Limitation 2: can not reference a directory.
      * File is not deleted (memory still allocated) until all hard links are deleted.
      * Not typically used in modern software.

    * Symbolic Links:
      * **ln** *-s item link*
      * creates a special type of file that contains a text pointer to the
        referenced file or directory. (think Windows shortcut)
      
#### P1 - Ch5: Working with Commands

  - **type** = Indicate how a command name is interpreted
  - **which** = Display wich executable program will be executed
  - **help** = Get help for shell builtins
  - **man** = Display a list of appropriate commands
  - **apropos** = Display a list of appropriate commands
  - **info** = Display a command's info entry
  - **whatis** = Display one-line manual page descriptions
  - **alias** = Create an alias for a command

  ##### What Exactly Are Commands?

***