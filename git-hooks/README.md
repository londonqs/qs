
# Keeping Jekyll Content Up-To-Date

In order to ensure that the `README.md` file in the *@master* branch is always up-to-date on the *@gh_pages* branch (note: this is the branch which the Jekyll static blog template uses) we must use a “git hook” which is executed whenever a commit is done on *@master*. 

The file found here — `post-commit` - must be manually copied to a checked-out repo’s `.git/hooks` directory with the following command:

> cp git-hooks/post-commit .git/hooks