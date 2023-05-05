# Man Command.

**Man command** in Linux is used to display the user manual of any command that we can run on
the terminal. 
It provides a detailed view of the command which includes:
- NAME 
- SYNOPSIS
- DESCRIPTION
- OPTIONS
- EXIT
- STATUS, 
- RETURN VALUES,
- ERRORS, 
- FILES,
- VERSIONS, 
- EXAMPLES,
- AUTHORS
- SEE ALSO.

Every **manual** is divided into the following sections:

1. Executable programs or shell commands
2. System calls (functions provided by the kernel)
3. Library calls (functions within program libraries
4. Games
5. Special files (usually found in /dev)
6. File formats and conventions eg /etc/passwd
7. Miscellaneous (including macro packages and conventions)
8. System administration commands (usually only for root)
9. Kernel routines [Non standard]
 

## Navigation in Man command:
1. $ man *xxxx* ( In this example, manual pages of the command ‘xxxx‘ are simply returned.)  
$ man [COMMAND NAME]

2. Section-num: Since a manual is divided into multiple sections so this option is used to display only a specific section of a manual.  
$man [SECTION-NUM] [COMMAND NAME]

3. -f option: One may not be able to remember the sections in which a command is present. So this option gives the section in which the given command is present.  
$ man -f [COMMAND NAME].

4. -a option: This option helps us to display all the available intro manual pages in succession.  
$ man -a [COMMAND NAME] 

5. -k option: This option searches the given command as a regular expression in all the manuals and it returns the manual pages with the section number in which it is found.  
$ man -k [COMMAND NAME]

6. -w option: This option returns the location in which the manual page of a given command is present.  
$ man -w [COMMAND NAME]

7. -I option: It considers the command as case sensitive.  
$ man -I [COMMAND NAME]

Once you have accessed manual page, you can use following keyboard shortcuts to navigate and search page −  

-Press "space" bar to move forward one page.
-Press "b" key to move backward one page.
-Press "enter" key to move forward one line.
-Press "q" key to exit manual page.
-Press "/" key to initiate a search. Type in search term and press "enter" to find next occurrence of term.

# Conclusion.
The Linux man command is an essential tool for anyone who is serious about using command line interface. By using man command, users can quickly and easily access information about a wide range of topics, allowing them to become more efficient and effective in their work.  
When using man command, it's important to remember that not all commands and utilities will have a manual page associated with them. In these cases, users may need to consult other resources, such as online forums, documentation, or online tutorials.  
Overall, Linux man command is a powerful tool that can help users become more proficient in using command line interface. By providing detailed information on a wide range of topics, man command can help users increase their productivity and efficiency when working with Linux systems.


 
