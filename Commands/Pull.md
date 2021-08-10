# Git Pull
Similar to a [Git push](./PUSH.md) a `git pull will interact witha remote repository. Only this time it will **pull** the changes it does not have from the remote down to the local repository.

This means any commits made that are on  the remote repository will be pulled down and added to the local repository.

This can be down by adding the remote name and branch name:
```
Git pullorigin main
```
If the is any upstream connections established, you can use `git pull` without specifying a remote or branch.
## Resources
- [GIt Pull Documentation](https://git-scm.com/docs/git-pull)
---
[Back to home](../README.md
)