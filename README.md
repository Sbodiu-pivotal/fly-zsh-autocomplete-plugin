# Concourse CLI zsh complete plugin

This [zsh](http://www.zsh.org/) plugin adds autocompletion options for all [Concourse CLI](http://concourse.ci/fly-cli.html) commands.

## Demo


### Oh-My-Zsh

* Clone this repo to your zsh plugins directory:

```
$ cd ~/.oh-my-zsh/plugins
$ git clone https://github.com/sbodiu-pivotal/fly-zsh-autocomplete-plugin.git fly
```

* Add the `fly` plugin to your `.zshrc` file:

```
plugins=(... fly)
```

### Antigen, Antigen-hs, Antibody

```
antigen bundle sbodiu-pivotal/fly-zsh-autocomplete-plugin
```

## Contributing

In the spirit of [free software](http://www.fsf.org/licensing/essays/free-sw.html), **everyone** is encouraged to help improve this project.

Here are some ways *you* can contribute:

* by using alpha, beta, and prerelease versions
* by reporting bugs
* by suggesting new features
* by writing or editing documentation
* by writing specifications
* by writing code (**no patch is too small**: fix typos, add comments, clean up inconsistent whitespace)
* by refactoring code
* by closing [issues](https://github.com/sbodiu-pivotal/fly-zsh-autocomplete-plugin/issues)
* by reviewing patches

### Submitting an Issue
We use the [GitHub issue tracker](https://github.com/sbodiu-pivotal/fly-zsh-autocomplete-plugin/issues) to track bugs and features.
Before submitting a bug report or feature request, check to make sure it hasn't already been submitted. You can indicate
support for an existing issue by voting it up. When submitting a bug report, please include a
[Gist](http://gist.github.com/) that includes a stack trace and any details that may be necessary to reproduce the bug,
including your gem version, Ruby version, and operating system. Ideally, a bug report should include a pull request with
 failing specs.

### Submitting a Pull Request

1. Fork the project.
2. Create a topic branch.
3. Implement your feature or bug fix.
4. Commit and push your changes.
5. Submit a pull request.

## Copyright

Copyright (c) 2016 Sergiu Bodiu. See [LICENSE](https://github.com/sbodiu-pivotal/fly-zsh-autocomplete-plugin/blob/master/LICENSE) for details.