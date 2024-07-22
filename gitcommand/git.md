# Git command

### Git status

> - git status

### Git add

> - git add .
>
> - git add "filename"

### Git commit

> - git commit -m "name changes"
>
> - git commit -am "name changes"
>
>> only works with a modified file not a new file

### Git push

> - git push origin main (default)
>
> - git push -u origin main (set upstream)
>
>> git push command will default to origin main

### Git reset

> - git reset
>
> - git reset "filename"
>
> - git reset HEAD
>
>> HEAD is a pointer to the last commit
>
> - git reset HEAD~1
>
>> HEAD~1 means point to the one commit furthur
>
> - git reset --hard "hash-log"
>
>> to not just be unstaged but to be completely remove
>> (get the log hash from "git log")

### Git log

> - git log

## Sync local folder to github

### Git init

> - git init
>
>> use for init a local folder

### Git remote

> - git remote add origin "link.git"

## Git branches

### Git branch

> - git branch
>
> - git branch -d branch-name
>
>> to delete the unused branch

### Git checkout

> - git checkout (switch between branches)
>
> - git checkout -b feature-name-version-up_to_you
>
>> creating a new branch

### Git diff

> - git diff branch-name

### Git merge

> - git merge branch-name
>
>> usually we use git push from the branch and then pull request to the origin


