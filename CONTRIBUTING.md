# 💥 How to Contribute

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)][pull-request-list]
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/)

- Take a look at the existing [Issues][issue-list] or [create a new issue][new-issue]!
- [Fork the Repo](https://github.com/vikasganiga05/tailwind-vite-starter/fork). Then, create a branch for any issue that you are working on. Finally, commit your work.
- Create a **[Pull Request](https://github.com/vikasganiga05/tailwind-vite-starter/compare)** (_PR_), which will be promptly reviewed and given suggestions for improvements by the community.
- Add screenshots or screen captures to your Pull Request to help us understand the effects of the changes proposed in your PR.

## ⭐ HOW TO MAKE A PULL REQUEST:

**1.** Start by making a fork the [**tailwind-vite-starter**][github-repo] repository. Click on the <a href="https://github.com/vikasganiga05/tailwind-vite-starter/fork"><img src="https://i.imgur.com/G4z1kEe.png" height="21" width="21"></a> symbol at the top right corner.

**2.** Clone your new fork of the repository:

```bash
git clone https://github.com/<your-github-username>/tailwind-vite-starter
```

**3.** Navigate to the new project directory:

```bash
cd tailwind-vite-starter
```

**4.** Set upstream command:

```bash
git remote add upstream https://github.com/vikasganiga05/tailwind-vite-starter.git
```

**5.** Create a new branch:

```bash
git checkout -b YourBranchName
```

**6.** Sync your fork or your local repository with the origin repository:

- In your forked repository, click on "Fetch upstream"
- Click "Fetch and merge"

### Alternatively, Git CLI way to Sync forked repository with origin repository:

```bash
git fetch upstream
```

```bash
git merge upstream/main
```

### [Github Docs](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github) for Syncing

**7.** Make your changes to the source code.

**8.** Stage your changes and commit:

⚠️ **Make sure** if there are no changes in package-related stuff not to commit `package.json` or `package-lock.json` file.

⚠️ **Make sure** not to run the commands `git add .` or `git add *`. Instead, stage your changes for each file/folder.

```bash
git add <your file/folder changes>
```

```bash
git commit -m "<your_commit_message>"
```

**9.** Push your local commits to the remote repository:

```bash
git push origin YourBranchName
```

**10.** Create a [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)!

**11.** **Congratulations!** You've made your first contribution to [**tailwind-vite-starter**][contributors]! 🙌🏼

**_:trophy: After this, the maintainers will review the PR and will merge it if it helps move the LinkFree project forward. Otherwise, it will be given constructive feedback and suggestions for the changes needed to add the PR to the codebase._**

## Style Guide for Git Commit Messages :memo:

| Type(Scope)           | Description                                         |
|-----------------------|-----------------------------------------------------|
| `feat(optional):`     | A new feature                                       |
| `fix(optional):`      | A bug fix                                           |
| `docs(optional):`     | Documentation related changes                       |
| `style(optional):`    | Everything related to styling                       |
| `refactor(optional):` | A code that neither fix bug nor adds a feature      |
| `test(optional):`     | Everything related to testing                       |
| `chore(optional):`    | Updating build tasks, package manager, configs, etc |

**How you can add more value to your contribution logs:**

- Use the present tense. (Example: "Add feature" instead of "Added feature")
- Use the imperative mood. (Example: "Move item to...", instead of "Moves item to...")
- Limit the first line (also called the Subject Line) to _50 characters or less_.
- Capitalize the Subject Line.
- Separate subject from body with a blank line.
- Do not end the subject line with a period.
- Wrap the body at _72 characters_.
- Use the body to explain the _what_, _why_, _vs_, and _how_.
- Reference [Issues][issue-list] and [Pull Requests][pull-request-list] liberally after the first line.

Use this to start the message. Like if we added test for a function which checks leap year, we start with `test`. Then in short describe the work we did :point_down:

```bash
$ git commit -m "test: add unit test for leapYearCheck()"
```

For more detailed reference to the above points, refer here: https://chris.beams.io/posts/git-commit.

## 💥 Issues

In order to discuss changes, you are welcome to [open an issue][new-issue] about what you would like to contribute. Enhancements are always encouraged and appreciated.

## All the best! 🥇

<p align="center">

[![built with love](https://forthebadge.com/images/badges/built-with-love.svg)][github-repo]

</p>


[github-repo]: https://github.com/vikasganiga05/tailwind-vite-starter
[new-issue]: https://github.com/vikasganiga05/tailwind-vite-starter/issues/new/choose
[issue-list]: https://github.com/vikasganiga05/tailwind-vite-starter/issues
[pull-request-list]: https://github.com/vikasganiga05/tailwind-vite-starter/pulls
[contributors]: https://github.com/vikasganiga05/tailwind-vite-starter/graphs/contributors
