# GH Extension: Conventional Commits

> Extension for the GitHub CLI that makes every commit a Conventional Commit.

<div align="center">

![demo](docs/demo.gif)

</div>

# What is this?

[Conventional Commits](https://www.conventionalcommits.org/) is a convention
developers use to indicate the meaning of a git commit. For example, if a
commit fixes a bug in the code, your conventional commit message would look
something like this:

```shell
fix: 🐛 Do not crash on empty index field
```

or if your commit updates a project's documentation your conventional commit would look like:

```shell
docs: 📝 Update FAQ section
```

This GH CLI extension helps to extend every `git commit` commit message with a
conventional commit prefix. 

# Installation

```shell
gh ext install robvanderleek/gh-cc
```

## upgrade

```shell
gh ext upgrade robvanderleek/gh-cc
```

## uninstall

```shell
gh ext remove robvanderleek/gh-cc
```

# Usage

Make sure you have the [GitHub CLI](https://cli.github.com/) up and running.
Next, install the extension (see above), and type the following inside any
cloned repository:

```shell
gh cc -am "commit message here"
```

This extension passes all arguments on to `git commit`, so to save typing you
can add the following alias to your shell configuration: `alias gc="gh cc"`.
The command above then becomes:

```shell
gc -am "commit message here"
```

That's it!

# Configuration

None yet, do you want to configure anything? Please open an issue for it!

# Feedback, suggestions and bug reports

Please create an issue here: https://github.com/robvanderleek/gh-cc/issues

If you like this software, please star :star: it.

# Contributing

If you have suggestions for how this extension could be improved, or want to
report a bug, [open an issue](https://github.com/robvanderleek/gh-cc/issues)!
All and any contributions are appreciated.

# License

[ISC](LICENSE) © 2024 Rob van der Leek <robvanderleek@gmail.com>
(https://x.com/robvanderleek)
