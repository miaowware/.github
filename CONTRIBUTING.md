# Contributing to MiaowWare Projects

## Before You Start

- Make sure there's an issue for the feature, bugfix, or other improvement you want to make.
- Make sure it's something that the project maintainers want.
  We can discuss it and assign the issue to you.
- Make sure work isn't already being done on the issue.

> Some contribution guidelines can vary project-to-project, so make sure to also read the `DEVELOPING.md` file in the project repository.

## While You Develop

Commit messages should be descriptive and mention issues that they fix ("fixes #123") or contain progress on ("progress on #123").
Make commits as needed, but try to keep it reasonable.
If there are too many, your contribution may be squashed when merged.
You may want to squash your commits locally yourself:

```sh
git reset --soft [commit before your changes]
git commit
```

Make sure to document your code as you go, in both comments and external documentation (in `/dev-notes/`) as needed.
`dev-notes` is especially important if you introduce a new json file format or to document some development process (like the command to crush the various images in the repository).

**Test your changes.**
If your code doesn't work, it's not ready for merging.
Make sure you not only test intended behaviour, but also edge cases and error cases.

If you're making a user-facing change, put a quick summary in `CHANGELOG.md` under the `[Unreleased]` heading.
Follow the [Keep a Changelog][1] format.

## When You're Ready to Merge

1. When you have finished working on your contribution, create a pull request from your fork's branch into the master branch of the project.
1. Read through and complete the pull request template.
   If the checklist is not complete, your contribution will not be merged.
1. Your pull request will get reviewed by at least one maintainer.
1. If approved, another maintainer may merge the pull request if everything looks good.

[1]: https://keepachangelog.com/en/1.0.0/

