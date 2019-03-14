# ASearch

#### Why ?
- Allows to quite fast search for file located in directories that are hosted on external devices
- Provides API to other plugins to fast look for files 

#### Commands
> extension.showSearchWindow

As it says, shows search window

>extension.reindexFiles

Use it to reindex files. If something bad to them happened.


#### How it works?
1. At start of vsc it should index files that are in working directories.
2. If not, use command above.
3. Use command to show window (Or assign it to shortcut)
4. On new window, in field you can type part of file you are looking for (Do not worry, it's case insensitive)
5. Use mouse, or keys and enter to select file you need.
6. Enjoy ?

