# SCMD
***SCMD*** stand for ***Short/Smart Commands***.

## Help
`newcmd` *[new command]*
- *It will automatically add a new command to scmd file.*
- **syntax** : **newcmd** *command_name* *"bash command"*
- **usage**: `newcmd home "cd ~/"`

------------



`vedit` *[vi/vim edit]*
- *Edit scmd file in **vi** or **vim** editor.*
- **syntax** : `vedit`
- **usage**: Just type `vedit` in terminal.

------------



`nedit` *[nano edit]*
- *Edit scmd file in **nano** editor.*
- **syntax** : `nedit`
- **usage**: Just type `nedit` in terminal.

------------



`ocmd` *[open scmd]*
- *Open scmd file in default **text** editor.*
- **syntax** : `ocmd`
- **usage**: Just type `ocmd` in terminal.

------------



`lsbranch` *[list branch]*
- *list all the local **git branches***
- **syntax** : `lsbranch`
- **usage**: Just type `lsbranch` in terminal.

------------



`cbranch` *[current branch]*
- *It displays **current working git branch name**.*
- **syntax** : `cbranch`
- **usage**: Just type `cbranch` in terminal.

------------



`newbranch` *[new branch]*
- *This command is used to create and switch to **new git branch**.*
- **syntax** : **newbranch** *branch_name*
- **usage**: `newbranch my-new-feature-branch`

------------



`rmbranch` *[remove branch]*
- *This command is used to **remove a git branch**.*
- **syntax** : **rmbranch** *branch-name-to-delete*
- **usage**: `rmbranch my-feature-branch-to-delete`

------------



`cpbn` *[copy branch name]*
- *It stands for **Copy Branch Name**. It is used to **copy** current working **git branch name** to clipboard.*
- **syntax** : `cpbn`
- **usage**: Just type `cpbn` in terminal.

------------



`gst` *[git status]*
- *Short for **git status**. Used to display status of the current working branch.*
- **syntax** : `gst`
- **usage**: Just type `gst` in terminal.

------------



`gad` *[git add]*
- *This command is used to all or particualr file to the **HEAD**.*
- **syntax** : **gad** *perameter*
- **usage**: `gad .`, `gad file_path`

------------



`addall` *[add all]*
- *This command add all the modified and newly created files to the **HEAD**.*
- **syntax** : `addall`
- **usage**: Just type `addall` in terminal.

------------



`gcmit` *[git commit]*
- *It is used to commit all the files available in the HEAD. Unadded & Untracked file will not being commited by using this command. Please refer `gacmit` and `gcmitall`*
- **syntax** : **gacmit** *"commit message"*
- **usage**: `gacmit "my commit message"`

------------



`gacmit` *[git add commit]*
- *This command is similar to `gcmit` and the minor difference is it will **add modified files to the HEAD** and then perform the **commit**. This command does not commit any untracked file. Please refer `gcmitall` to commit untracked files.*
- **syntax** : **gacmit** *"commit message"*
- **usage**: `gacmit "my commit message"`

------------



`gcmitall` *[git commit all]*
- *This commad is similar to the `gacmit` command, the only difference is that it will add both **tracked** and **untracked** files to the HEAD and **commit**.*
- **syntax** : **gcmitall** *"commit message"*
- **usage**: `gcmitall "my commit message"`

------------



`mergewith` *[merge with]*
- *This command is used to **merge** other branch with the **current** branch.* Also refer `mergein ` command.
- **syntax** : **mergewith** *branch-name*
- **usage**: If you want to merge branch **Alpha** with branch **Bita** then,
`git checkout Bita` and then **`mergewith Alpha`**.

------------



`mergein` *[merge in]*
- *This command is used to **merge current branch changes in other branch**.*
- **syntax** : **mergein** *branch-name*
- **usage**: If you are **in** branch **Alpha** and you want to merge **Alpha**'s changes in branch **Bita** then type `mergein Bita` in terminal.
- **Note**: After using `mergein` command you will automatically switched from **Alpha** branch  to **Bita** branch.

------------



`rebasewith` *[rebase with]*
- *This command is used to **rebase** other branch to current working branch. Also refer `rebasein` and `mergewith` commands.*
- **syntax** : **rebasewith** *branch-name*
- **usage**: If you want to rebase branch **Alpha** in branch **Bita** then,
`git checkout Bita` and then **`rebasewith Alpha`**.

------------



`rebasein` *[rebase in]*
- *This command is used to **rebase** current branch into **other** branch.*
- **syntax** : **rebasein** *branch-name*
- **usage**: If you are **in** branch **Alpha** and you want to **rebase** current branch changes to **Bita** branch then just do `rebasein Bita`.
- **Note**: After using `rebasein` command you will automatically switched from **Alpha** branch to **Bita** branch.

------------



`rbc` *[rebase continue]*
- *It is very useful when fixing conflicts while rebasing the branch. This command add the changes and then do the rebase continue.*
- **syntax** : `rbc`
- **usage**: Just type `rbc` in terminal.

------------



`rmchng` *[remove changes]*
- *It will reset all the modified file changes of the tracked files. Untracked file will not being removed by using this command. Also see the `rmall` command.*
- **syntax** : `rmchng`
- **usage**: Just type `rmchand` in terminal

------------



`rmall` *[remove all]*
- *It will reset all the modified file's changes and remove all the untracked files.*
- **syntax** : `rmall`
- **usage**: Just type `rmall` in terminal.

------------



`cout` *[check out]*
- *It is a short command for the `git checkout` command.*
- **syntax** : **cout** *perameter*
- **usage**: `cout branch-name`, `cout .`, `cout file_name` & `cout -b new branch-name`

------------



`gcln` *[git clean]*
- *It is used to remove untracked files.*
- **syntax** : `gcln`
- **usage**: Just type `gcln` in terminal.

------------



`gpull` *[git pull]*
- *It is used to pull the changes from the git server.*
- **syntax** : `gpull`
- **usage**: Just type `gpull` in terminal.

------------



`pullr` *[pull with rebase]*
- *This command will pull the changes from the git server and rebase your current changes in same branch.*
- **syntax** : `pullr`
- **usage**: Just type `pullr` in terminal.

------------



`opull` *[origin pull]*
- *This command will pull changes from the current branch origin.*
- **syntax** : `opull`
- **usage**: Just type `opull` in terminal.

------------



`pullo` *[pull to origin]*
- *This command is used to pull from origin of any branch.*
- **syntax** : **pullo** *branch-name*
- **usage**: `pullo my-feature-branch`

------------



`gpush` *[git push]*
- *This command is used to push the local system changes to the server.*
- **syntax** : `gpush`
- **usage**: Just type `gpush` in terminal.

------------



`opush` *[origin push]*
- *This command is used to push to the current branch origin.*
- **syntax** : `opush`
- **usage**: Just type `opush` in terminal.

------------



`pusho` *[push to origin]*
- *This command is used to push changes from local system to any origin branch.*
- **syntax** : **pusho** *branch-name*
- **usage**: `pusho my-feature-branch`

------------



`gl` *[git log]*
- *This command is used to display logs (commits) of the current branch.*
- **syntax** : `gl`
- **usage**: Just type `gl` in terminal.

------------



`gdf` *[git diff]*
- *This command will display the code difference in the terminal.*
- **syntax** : **gdf** *file_path*
- **usage**: `gdf`, `gdf /home/file.txt`

------------



`rmadd` *[remove added]*
- *This command is used to remove all added files to HEAD.*
- **syntax** : `rmadd`
- **usage**: Just type `rmadd` in terminal.

------------



`rmcmit` *[remove commit]*
- *This command will remove the last commit of the current working branch.*
- **syntax** : `rmcmit`
- **usage**: Just type `rmcmit` in terminal.

------------



`reload` *[reload tab]*
- *This command will used to reload current active tab of the terminal. You have to configure this command before using it.*
- **syntax** : `reload`
- **usage**: Just type `reload` in terminal.
- **configuration**: edit **scmd** file and update the path for the reload command, by default it is given for `.bash_profile`. If you are not using the default bash then you can update it accordingly.

------------



## Contributing
1. Fork it ( https://github.com/vishalnagda1/scmd/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request.
