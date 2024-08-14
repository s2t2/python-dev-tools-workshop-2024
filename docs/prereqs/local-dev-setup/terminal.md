
# Command-line Application

The goal is to have access to a command-line application, which we'll use to programmatically interface with our computers. Choice of tool depends on your operating system:

  + Mac users who don't already have a preferred command-line application are encouraged to use the built-in Terminal application (no need to download anything, although you may want to optionally [customize](./terminal-config.md) the Terminal appearance as desired)
  + Windows users who don't already have a preferred command-line application are encouraged to install [Git Bash](https://git-scm.com/downloads), which will allow Windows users to write the same unix-style commands as Mac users

## Success Criteria

If successful, you should be able to use your command-line application to issue the commands below, which are some of the most relevant and common commands for navigating the filesystem.

Change directories, for example to the Desktop:

```sh
cd ~/Desktop
```

What is the present working directory? Where are we right now?

```sh
pwd
```

List the files and folders in this place:

```sh
ls -al
```

You should now also be able to use your command-line application to complete the ["Command-line Computing" Exercise](../../exercises/command-line-computing/index.md), which will introduce you to additional commands.
