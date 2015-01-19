# git
Learning git 

Unix Command Refresher

cd - think 'change directory:' change the current working directory. Remember that ~ is a special symbol that always represents your "home" directory.
ls - think 'list:' shows a list of all files/folders in the current directory. With the -a flag, also shows hidden files and folders.
mkdir - think 'make directory:' creates a new directory with the specified name.
touch - updates the "last modified" timestamp on a file to now. Also creates an empty file if the filename specified doesn't exist.
mv - think 'move:' moves a file or directory to a new location. This also makes it a convenient way to rename files and folders.
rm - think 'remove:' deletes the file(s)/folder(s) specified.

Git Commands

git init [project_name] - initializes a new repository. If project_name is provided, it creates a new project directory with that name. If not, it initializes a repository in the current directory.

git add - adds files to the repository so that Git knows to track their changes.

git commit - commits all added files to the repository as a change. With the -a flag, commits all changes to all tracked files. With the -m flag, allows you to specify a commit message directly on the command line instead of in your default editor.

git config - allows you to make configuration changes to Git. With the --global flag, makes these changes available across your entire system.
