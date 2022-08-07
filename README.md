# Remove-error-in-bash-file-not-found-
You can reset your bash when the bash error: no file found pops up on your terminal even when u reset your terminal.
you can backup your exsisting bashrc file if you want the exsisting content of it.

## Solution

To remove this error
Follow the steps..

* ### Go to your home directory.
```
cd ~
```

* ### Move your bashrc file to a new file(.bash.old).
So,now go the /etc/apt/sources.list.d with this command.

```
mv .bashrc .bashrc.old
```

* ### To check if you have this new file .bashrc.old and there is no .bashrc run this.
```
ll
```

* ### Now copy your bashrc file to the home directory.
```
cp /etc/skel/.bashrc ./
```

* ### check your new bashrc file.
```
ll
```

#### now just reboot your system ans you are good to go :).
