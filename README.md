#BESTBASH: The best configuration you will ever find for bash
##Configured for Arch Linux
##Features
###Colors
1. colored manpages
2. colored outputs for many programs, like gcc, vim, etc.
3. many more...

###Aliases
1. Aliases for pacman
2. Aliases for root-access commands
3. Custom aliases for file, directory, and navigation command
4. Aliases for autocolor

###Functions
Custom commands for super lazy people ;)

1. Seting proxy on or off for  IITK intranet(Unfortunately only works for gnome settings :(  )
2. Better git commands(Kudos to helmuthdu)
3. up:go up the directory structure specified number of times
4. extract: Extracts zip, tar.gz,tar.bz2 files in one command
5. compress: similar to above
6. to_iso: Converts to ISO
7. remindme: uses notify-send to display notification after specified number of time(remindme [time in seconds] [text])
8. calc: a simple calculator
9. ff: find file with a pattern in name
10. fe: find file with pattern in name and execute a command on it(example: fe a.out 1)
11. lowercase: move filenames to lowercase
12. swap: swap2 filenames around
13. dirsize: Self explanatory
14. fared: find and remove all empty directories
15. cd: cd with ls
16. systemd support with various aliases and functions
17. mkcd: mkdir and cd into new dir

###Settings
OS, Bash, Bash history, Completion, Config, Ruby, NVM, VTE, ANDROID SDK, EDITOR settings

##Configuration Instructions
  ```
  #clone into home
  git clone https://github.com/jaivardhankapoor/bestbash ~/.bash/
  #backup old .bashrc and .bashrc related files
  mv .bashrc .bashrc.bak
  #create symlink for .bashrc
  ln -s ~/.bash/init ~/.bashrc
  #ALL DONE!
 ```
