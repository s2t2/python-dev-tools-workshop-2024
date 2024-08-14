
# Version Control Utilities

The goal of a "version control" tool is to help us track changes in our code, and easily interface with code hosting and collaboration platforms like GitHub.

Git is a leading system for performing version control. Professionals may prefer to use Git from the command line, but there is a learning curve. So beginners are encouraged to get started with GitHub Desktop first, which provides an easier to use graphical user interface (GUI).

In this workshop we will use GitHub Desktop to download repositories from GitHub. We will revisit command-line Git in a future workshop.

## GitHub Desktop

Beginners are encouraged to install [GitHub Desktop software](https://desktop.github.com/), for Mac or Windows.

After installing, you will need to login with your GitHub account credentials. See this [GitHub Desktop setup guide](https://docs.github.com/en/desktop/installing-and-authenticating-to-github-desktop/setting-up-github-desktop), and the professor's [GitHub Desktop configuration reference](/notes/devtools/github-desktop.md#configuration) for more details.

> NOTE: GitHub Desktop may require the Git command line utility to also be installed on your computer (see below).

## Git CLI

Installing Git depends on your operating system:

  + Windows users who have [installed Git Bash](.terminal.md) will have satisfied the Git installation requirement.
  + Mac users may find that a system version of Git is already installed, and that might be sufficient to satisfy the Git installation requirement. Any Mac users who encounter errors or who desire a newer version of Git can install Git from https://git-scm.com/downloads, or consider [installing Homebrew](../../notes/clis/brew.md), and using Homebrew to install Git (`brew install git`).

Verifying Git has been installed:

```sh
git --version
```