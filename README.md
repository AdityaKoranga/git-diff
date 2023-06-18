# git-diff

Command for going to the desired branch:
```git
git checkout <branch-name>
```

Comparing two branches:
```git
git diff <branch1-name>..<branch2-name>
```

Comparing a file in two branches:
```git
git diff branch1..branch2 -- </path/to/filename>
```

Comparing two branches and only wants file name `changed/ modified/ added/ renamed/ deleted` as result:
```git
git diff --name-status branch1..branch2
```
In this:
* A: Added
* M: Modified
* D: Deleted
* R: Renamed
* C: Copied
