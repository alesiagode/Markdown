# Man Comand.

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

- Executable programs or shell commands
- System calls (functions provided by the kernel)
- Library calls (functions within program libraries
- Games
- Special files (usually found in /dev)
- File formats and conventions eg /etc/passwd
- Miscellaneous (including macro packages and conventions)
- System administration commands (usually only for root)
- Kernel routines [Non standard]

Syntax:
$ man [COMMAND NAME]

Navigation in Man command:
1. $ man *xxxx* ( In this example, manual pages of the command ‘xxxx‘ are simply returned.) 

2. Section-num: Since a manual is divided into multiple sections so this option is used to display only a specific section of a manual.  
$man [SECTION-NUM] [COMMAND NAME]

3. -f option: One may not be able to remember the sections in which a command is present. So this option gives the section in which the given command is present.  
$ man -f [COMMAND NAME].

