# Git Select
> `git checkout` with ease

This little tool improves UX of the `git checkout` command.
Right now it supports only basic operations.

### Usage:
```shell
    git select -b develop
    # This will create the branch `develop` if it doesn't exists.
    
    git select
    # This will open a select menu where you can search 
    # branches and checkout on Enter. 
```

### Installation:
1. Download the latest release [here](https://github.com/Rawnly/git-select/releases/latest)
2. Move the binary in your `$PATH`
3. Enjoy via `git select [flags|branch]`


#### HomeBrew
```shell

    brew tap rawnly/tap
    brew install git-select
    
    # OR
    brew install rawnly/tap/git-select
```

### Features
- [x] Checkout branch via interactive prompt
- [x] Create and checkout a new branch
- [ ] Check for git installation with `cli/safeexec`.
- [ ] Support all the `git checkout` flags/parameters.
