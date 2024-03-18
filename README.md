# git-messages

## Description

A small executable cheatsheet to show the list of conventional commit types.

This was based initially on https://github.com/angular/angular/blob/master/CONTRIBUTING.md and was updated with https://www.conventionalcommits.org/en/v1.0.0/#specification, which adds 'chore:' to the list.

## Installation

### 0. Have a recent version of Ruby installed

### 1a. Via Homebrew

```shell
$ brew tap thoran/tap
$ brew install thoran/tap/git-messages
```

### 1b. Manually

```shell
$ git clone https://github.com/thoran/git-messages
$ cp ./git-messages/bin/git-messages to your preferred executable path
$ chmod +x /path/to/git-messages
```

## Usage

### 1. If `git` is installed
```shell
$ git messages
```

### 2. If `git` is not installed (though I'm not sure why you'd want this installed if it wasn't)
```shell
$ git-messages
```

## Contributing

1. Fork it: `https://github.com/thoran/git-messages/fork`
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Create a new pull request
