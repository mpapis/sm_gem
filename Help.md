Usage:

    sm gem build|install|release|info|help {name}

The {name} is optional - in the case auto-detection fails.

- `info`    - will show information about the gem,
- `build`   - will build the gem,
- `install` - will build and install the gem,
- `release` - will build, git(commit, tag, push) and rubygems push the gem,
- `help`    - show this help message.

Configuration `.gem.config`:

    gem_spec=file.gemspec
    gem_tag_prefix=v

All variables are optional:

- `gem_spec` - define gemspec file to use (if multiple available)
- `gem_tag_prefix` - define a prefix for git tag
