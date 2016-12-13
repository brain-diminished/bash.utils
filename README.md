*This project contains various bash utils scripts, such as git extensions.*

# Install

To install a command, create a symlink inside a folder present in your `$PATH` environment variable (for example, **/usr/local/bin/**).
```sh
ln -s /path/to/folder/git/git-web /usr/local/bin/git-web
```
If you prefer, you can as well add project root folder along with subfolders (such as **/git/**) to `$PATH`.

# git commands

git commands are detected as soon as are they are present in `$PATH`, as an executable file named git-\*\*\*. For example, once
the file git-web is accessible, the command `git web` will be available, with sweet autocomplete!

# PS1 config

The purpose of the **.bash_ps1** script is to customize your terminal prompt. First, copy this file in your home directory:
```sh
cp /path/to/folder/.bash_ps1 ~/.bash_ps1
```
Then, add the following line in your .bashrc file (home directory):
```sh
source ~/.bash_ps1
```
