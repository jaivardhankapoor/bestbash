#BESTBASH: The best configuration you will ever find for bash
##Configured for Arch Linux
----
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
i. up:go up the directory structure specified number of times
ii. extract: Extracts zip, tar.gz,tar.bz2 files in one command
iii. compress: similar to above
iv. to_iso: Converts to ISO
v. remindme: uses  zenity to display notification after specified number of time(remindme [time in seconds] [text])
vi. calc: a simple calculator
vii. ff: find file with a pattern in name
viii. fe: find file with pattern in name and execute a command on it(example: fe a.out 1)
ix. lowercase: move filenames to lowercase
x. swap: swap2 filenames around
xi. dirsize: Self explanatory
xii. fared: find and remove all empty directories
xiii. cd: cd with ls
xiv. systemd support with various aliases and functions
xv. mkcd: mkdir and cd into new dir

###Settings
OS, Bash, Bash history, Completion, confog, Ruby, NVM, VTE, ANDROID SDK, EDITOR settings
----
##Configuration Instructions
  #clone into home
  git clone https://github.com/jaivardhankapoor/bestbash ~/.bash/
  #backup old .bashrc and .bashrc related files
  mv .bashrc .bashrc.bak
  #create symlink for .bashrc
  ln -s ~/.bash/init ~/.bashrc
  #ALL DONE!
----
###KUDOS TO helmunthdu for sharing his awesome bashrc file and making my life much much easier!
