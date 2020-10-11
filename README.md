# GitHub CLI

`gh` is GitHub on the command line. It brings pull requests, issues, and other GitHub concepts to the terminal next to where you are already working with `git` and your code.

![screenshot of gh pr status](https://user-images.githubusercontent.com/98482/84171218-327e7a80-aa40-11ea-8cd1-5177fc2d0e72.png)

## 1. Availability

GitHub CLI is available for repositories hosted on GitHub.com and GitHub Enterprise Server 2.20+, and to install on macOS, Windows, and Linux. 


## 2. Documentation

Read the [official docs][] for usage and more information.



## 3. We want your feedback

We'd love to hear your feedback about `gh`. If you spot bugs or have features that you'd really like to see in `gh`, please check out the [contributing page][].



<!-- this anchor is linked to from elsewhere, so avoid renaming it -->
## 4. Installation

### (a) macOS

`gh` is available via [Homebrew][] and [MacPorts][].

#### (b) Homebrew

|Install:|Upgrade:|
|---|---|
|`brew install gh`|`brew upgrade gh`|

#### (i) MacPorts

|Install:|Upgrade:|
|---|---|
|`sudo port install gh`|`sudo port selfupdate && sudo port upgrade gh`|



### (c) Linux

See [Linux installation docs](./docs/install_linux.md).

### (d) Windows

`gh` is available via [scoop][], [Chocolatey][], and as downloadable MSI.

#### (i) scoop

Install:

```powershell
scoop bucket add github-gh https://github.com/cli/scoop-gh.git
scoop install gh
```

Upgrade:

```powershell
scoop update gh
```

#### (ii) Chocolatey

|Install:|Upgrade:|
|---|---|
|`choco install gh`|`choco upgrade gh`|


#### (iii) Signed MSI

MSI installers are available for download on the [releases page][].

### (e) Other platforms

Download packaged binaries from the [releases page][].

### (f) Build from source

See here on how to [build GitHub CLI from source][build from source].

## 5. Comparison with hub

For many years, [hub][] was the unofficial GitHub CLI tool. `gh` is a new project that helps us explore
what an official GitHub CLI tool can look like with a fundamentally different design. While both
tools bring GitHub to the terminal, `hub` behaves as a proxy to `git`, and `gh` is a standalone
tool. Check out our [more detailed explanation][gh-vs-hub] to learn more.


[official docs]: https://cli.github.com/manual
----------------------------------------------------------------------------------
[Homebrew]: https://brew.sh
----------------------------------------------------------------------------------
[MacPorts]: https://www.macports.org
----------------------------------------------------------------------------------
[scoop]: https://scoop.sh
----------------------------------------------------------------------------------
[Chocolatey]: https://chocolatey.org
----------------------------------------------------------------------------------
[releases page]: https://github.com/cli/cli/releases/latest
----------------------------------------------------------------------------------
[hub]: https://github.com/github/hub
----------------------------------------------------------------------------------
[contributing page]: https://github.com/cli/cli/blob/trunk/.github/CONTRIBUTING.md
----------------------------------------------------------------------------------
[gh-vs-hub]: ./docs/gh-vs-hub.md
----------------------------------------------------------------------------------
[build from source]: ./docs/source.md

**************************************************************************************************************************************************************
