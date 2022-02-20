# git status

The commands `git status` is extreamly helpful when it comes to checking on the, you gessed it, status of your repository.

Using `git status` will show you what changes are being tracked, aren't being tracked, what [commits](./Commit.md) need to be [pushed](./Push.md)/[pulled](./Pull.md), etc. It is exactly what it sounds like, a status check. 

Status is a command that is safe to use at any time. if you want to see what is going on it's good to use `git status` in between commands until you get to know the floow better.

```
git add .
git status

git commit -m "Modified landing page"
git status

git push
git status
```

## Resources

- [Git Status Documentation](https://git-scm.com/docs/git-status)

---

[Back to home](../README.md)