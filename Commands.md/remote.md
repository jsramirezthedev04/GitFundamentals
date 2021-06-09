# git remotes
---
When working with git, a **remote** is any git repository that is not on the machine you're working on. The counterpart to this is **local**, or the maching that is being developed on.

Take github for example. While git is the technology that allows yo to create local repositories, github is the site that will host your remote repositories. once stored remotely, you can bring that repository back down or share it with others.

**note**: while the repositories(local and remotes) are related and track the same project, they can have differente states if changes are not shared betweeen the two.

---
### Adding a remote
A remote can be added with the `git remote add` command, followed by the name and location of the remote.

The name is a local name, meaning it's your label and does not impact the actual remote whatsoever.
```
git remote add origin https://github.com/ElevenfiftyAcademy/GitFundamentasl.git
```
### Removing a remote
A remote can be removed with the `git remote remove` command, followed by the name of the remote
```
git remote remove origin
```
## Resources
- [git remote Documentation](httmps://git-scm.com/docs/git-remote)
---
[back to home](../README.md)