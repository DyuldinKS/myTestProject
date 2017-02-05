# Basics

# Checking the status, tracking new files, staging modified files
`$ git status`
`$ git status -s` OR `git status --short` // a more compact form
`$ git add <file OR directory>...` // to update what will be committed
`$ git checkout -- <file>... // to discard changes in working directory

# Viewing Your Staged and Unstaged Changes
`$ git diff` // show changes that are still unstaged
`$ git diff --staged` OR `git diff --cached` //  to see what you’ve staged so far 

# Skipping the Staging Area
`$ git commit -a` == `$ git add; git commit`

# Removing Files
`$ git rm <file>` // it stages the file’s removal
`$ git rm --cached <file>` // to remove from staging area
`$ git mv <file> <new_file>` // stages the file's movement
