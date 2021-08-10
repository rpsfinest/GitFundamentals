# Git Remote
When working with git, a ** remote** is any git repository that is not on the machine you're working on. The counterpart to this a **local**, or the machine that is being developed on.

Take GitHub for example. While git is atechnology that allows you to creat local repositiries, GitGun is the sire that will host you remote repositories. Once stored remotely, you can bring that repository back down or share it with others. 

**Note**: Whlile the repositories (local and remote) are related and track the same project, they can have different states if changes are not shared between the two. 
### Adding a remote
A remote can be added with the `git remote add` command, followed by the name and location of the remote. 
The name is a local name, meaning its you rlabel and does not impact the actual remote whatsoever.
```
Git remote add origin http://github.com/Elevenfiftyacademy/Gitfundamentals.git
```
### Removing a Remote
A remote can be removed with the `git remote remove` command, followed bt the name of the remote.
```
git remote remove origin
```

## Resources
-[Git Remote Dcoumentation](https://git-scm.com/docs/git-remote)
---
[Back to home](../README.md)
