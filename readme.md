# git-iterate-and-run

Enumerate a range of commits and run a command on each.

This is the opposite of git-bisect which aims to isolate the bad commit by bisection. It's useful to ensure the recent history contains no errors.

# Usage 

You can either specify a branch name or only the number of commits to test.

```
# run command for all N commits of currently checked out branch
$ git-iterate-and-run <N commits> -- <command with muplitpe args>

# run command for all N commits of specified branch
$ git-iterate-and-run <branch name> <N commits> -- <command with muplitpe args>
```

# Licence

This script is licensed for you under the MIT license

