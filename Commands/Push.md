# Git Push
When You have a [remote](./remote.md) set up you'll need to begin to move [commits](./Commit.md) to he remote this can be done with the command `Git push`.
You can attach a name and a branch anme to your command to specify where you're pushing to.
```
Git push origin main
```
This command will push the **main** branch to the remote called **origin**. This means any commits that in you local will be **pushed** to the remote.

### Upstream Tracking 
Instead of including the name of the remote and the branch you're on every time, you can set local branches to track upstream branch. This mean you can tell the branch to push its assgned upstream remote branch by using the command `git push`.
```
Git push -u origin main
``` 
After this command is used, you can just use `git push` and it will function the same way. 
## Resources 
- [Git Push Doumentation](https://git.com/docas/git-push)
---
[Back to home](../README.md
)