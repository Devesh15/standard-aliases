Standard Aliases
================

Make Linux more user friendly with this collection of bash aliases.

Bash aliases are most useful device for customizing your Linux...
Here is a short list of ones i find most useful:

** t - tree
l/ll/lll (GIF)
cpdir/mvdir/rmdir
** rb - runs command in background
** o  - open file with default app
mk - mkdir and descend into
me - make executable
gr - grep with pager
** extract - extracts archive of any type
ch - can haz
version
** wi - what is (GIF)
gs - git status
gl - git log
gd - git diff
ip1 - internal ip
ip2 - external ip
pa - ping all
** ne - network status
wr - wireless reset
i - internet: default browser in background
al - opens this file in vim

?ma - make with pager
?m  - cat or less
?te - open another terminal with same working directory
?fu - fuck: runs last command as sudo
?ty - type


[**LIST OF ALL FUNCTIONS**]('FUNCTION_DESCRIPTIONS.md')

Every alias that doesen't just define a different name for a command is defined as a function with descriptive name. This function is then aliased with a shorher and more convinient name. Do not change the names of the functions because they may be used by other functions.

Also only aliases get documented by generate-readme script.

By convention a function that calls the a command with some set of options that are quiet sensible for that command to be run with is named <command-name>WithSensibleOptions. This function is then usualy aliased with <command-name>1, and often also with a two letter aberration.




This aliases were made for debian based linux (ubuntu, mint,...) with gnome desktop environment, but most aliases will work on all systems with bash shell.

Most aliases will send output to pager if it will be too long to fit the screen.

Some aliases require special tools that are not installed by default on most systems. You can install them all at one with command belove, but it is probably more reasonable to just install them when demand arises.

Usualy if alias only makes command easier to use, either by providing the options that should have been set by default, or just by sending output of command to pager if necesary, then it has same name as command, but with number 1 apended at the end. Some examples are:
ps1
pgrep1
tree1
mkdir1

Only aliases that override the commands are cp, mv and rm. They are all run in interactive mode, meaning you get asked for conformation before any destructive operation. If you want to execute them without this promptint, then use -f (force) option. 

If the list belowe seems too long here is a shorthened list of aliases, that I consider almost necesary:)
m
l/ll/lll
cpdir/mvdir/rmdir
rb
o
ty
te
(ma)
mk


When adding new alias alwalys check if it is already taken by any command with `wi <alias>`.

Do not change the names of the functions, because other functions and/or aliases may be using it. You can however freely change the names of the aliases.


// Intentions
I know it is a bit abnockuous to think your colection of aliases is so great, that it should become adopted as standard, but what a hack, I worked on and been using them for long time, and I just feel so limited withouth them.


completions...
automatioc completions from the command that gets parameters in function.

Linux for the rest of us.

Linux is elegant and concise, but it is also hard.
If you can't type well and/or have problem with memorizing stuff you're basically screwed.

