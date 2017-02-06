# Basics

## Checking the status, tracking new files, staging modified files
`$ git status`
`$ git status -s` OR `git status --short` a more compact form
`$ git add <file OR directory>...` to update what will be committed
`$ git checkout -- <file>...` to discard changes in working directory

## Viewing Your Staged and Unstaged Changes
`$ git diff` show changes that are still unstaged
`$ git diff --staged` OR `git diff --cached` to see what you’ve staged so far 

## Skipping the Staging Area
`$ git commit -a` == `$ git add; git commit`

## Removing Files
`$ git rm <file>` it stages the file’s removal
`$ git rm --cached <file>` to remove from staging area
`$ git mv <file> <new_file>` stages the file's movement

## Viewing the Commit History
`$ git log`
`$ git log -p` shows the difference introduced in each commit
`$ git log -2` limits the output to only the last two entries
`$ git log --stat` shows some abbreviated stats for each commit
`$ git log --pretty=<oneline | short | full | fuller | format> --graph`
`$ git log --since=2.weeks`
`$ git log --until="2008-01-15"`

### Common options to **git log**
-p, --stat, --shortstat, --name-only, --name-status, --abbrev-commit, --relative-date, --graph, --pretty

### Options to limit the output of **git log**
-(n), --since, --after, --until, --before, --author, --committer, --grep, -S

## Showing Your Remotes
`$ git remote -v` remotes with URL


