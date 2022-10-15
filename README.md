# ReadMe example

## General Git Commands
### Cloning a git repo
```git clone <URL to repo>```

### List all of the branches that you have access to (-v for more info)
```git branch -a -v```

### Create a new branch
```git branch <NewBranchName>```

### Switch your current branch
```git switch <branchToSwitchTo>```

```git checkout <branchToSwitchTo>```

## Working with remote branches
**Remote** branches refer to the git repository as it is stored on github or other git based web services. When you clone a repository, you download a copy of the repository to your computer. This downloaded copy is called the **local** repository.

When you edit the local repository on your computer, the github copy of the repository does not just automatically update based on your changes. Likewise, your local copy does not automatically update if someone else updates the github repository.

## Updating your local copy with the latest version from github

