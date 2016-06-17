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
1. Seting proxy on or off for  IITK intranet
2. Better git commands(Kudos to helmuthdu)
3. Top 11 commands(google them!):
  1. up:go up the directory structure specified number of times
  2. extract: Extracts zip, tar.gz,tar.bz2 files in one command
  3. compress: similar to above
  4. to_iso: Converts to ISO
  5. remindme: uses  zenity to display notification after specified number of time(remindme [time in seconds] [text])
  6. calc: a simple calculator
  7. ff: find file with a pattern in name
  8. fe: find file with pattern in name and execute a command on it(example: fe a.out 1)
  9. lowercase: move filenames to lowercase
  10. swap: swap2 filenames around
  11. dirsize: Self explanatory
  12. fared: find and remove all empty directories
  13. cd: cd with ls
  14. systemd support with various aliases and functions
  15. mkcd: mkdir and cd into new dir

###Settings
OS, Bash, Bash history, Completion, confog, Ruby, NVM, VTE, ANDROID SDK, EDITOR settings

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
----
###KUDOS TO helmunthdu for sharing his awesome bashrc file and making my life much much easier!
