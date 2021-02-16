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

  
  





***