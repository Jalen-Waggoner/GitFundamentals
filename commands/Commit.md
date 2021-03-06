# git commit

<!--- I think that there may be a typo here in the course module. The module reads "[git add](./ADD.md))" when it should be "[git add](./Add.md))" -->

The command `git commit` will take all tracked changes (items added with [git add](./Add.md)) and package them up in what is called a commit.

Commits come with commit messages that are required for each commit. You add a message to a commit command by suing the `-m` flag followed by a message in quotes.

A commit message _can_ be anything, but best practice dictates that you should use that message to indicate the changes included in the commit.

For example, if we have an application we're working on where we just built out the ability to register new accounts, then you might have some variation of the following:

```
git add.
git commit -m "Added register functionality"
```

## Resources

- [Git Commit Documentation](https://git-scm.com/docs/git-commit)

---

[Back to home](../README.md)