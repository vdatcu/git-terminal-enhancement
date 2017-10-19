# git-terminal-enhancement

Here are the steps required in order to have enhanced terminal functionality: git branch on pwd indicator, ip and diff commands (OS X with Homebrew is a prerequisite). Tested only with bash (not sure with zsh and other shells:

 - brew install jq
 - brew install cdiff
 - copy the .git-completion.bash to your home dir ~/
 - copy the contents of .bash_profile_example to your .bash_profile file, located in the home dir

Restart the terminal and you should see the changes. In order to test try:

```vdatcu@vdatcu-osx ~ $ getip``` - this works anywhere

The following command work only when inside a git repo:

```vdatcu@vdatcu-osx ~/Playground/git-terminal-enhancement (master) $ xdiff``` - should show the changes made to the working directory, but only files which are not hidden (don't start with *.*)