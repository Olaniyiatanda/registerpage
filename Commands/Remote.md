# git remote

When working with git, a  **remote** is any git repository that is not on the machine you're working on. The counterpart to this is  **local**, or the machine that is being developed on.

Take GitHub for example. While git is the technology that allows you to crearte local repositories, GitHUb is the site that will host remote repositories.
Once stored remotely, you can bring that repositohry back down  or share it with others.

**Note**: While the repositories  (local and remote) are related and track the same project , they can  have different states if changes are not shared between two.

### Adding a remote

A remote can be added with the `git remote add` command, folloowed by the name and location of ther remote.

The name is local name, meanong kit's your label and does not impact the actual remote whatsoever.

```
git remote add origin https://github.com/ElevenfiftyAcademy/GitFundamentals.git
```

### Removing a remote

A remote can be removed with the `  git remote remove` command, followed by the name of the remote.

```
git remote remove origin
```
## Resources

-[Git Remote Docummentation](https://git-scm.com/docs/git-remote)

---
[Back to home](../README.md)