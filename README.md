# Personal Website

Based on Jekyll

## Setup

This project uses a local Ruby installation via `rbenv` to keep everything isolated.

**Prerequisites:** Homebrew, rbenv, and ruby-build
```bash
brew install rbenv ruby-build
```

**Install Ruby and dependencies:**
```bash
# Install Ruby 3.4.8 locally
rbenv install 3.4.8
rbenv local 3.4.8

# Install dependencies locally
gem install bundler
bundle config set --local path 'vendor/bundle'
bundle install
```

**Development:**
```bash
# Initialize rbenv (add to ~/.zshrc to avoid repeating)
eval "$(rbenv init - zsh)"

# Serve the site at http://127.0.0.1:4000/
bundle exec jekyll serve

# Or just build without serving
bundle exec jekyll build
```

**Clean uninstall:**
```bash
rm -rf ~/.rbenv
brew uninstall rbenv ruby-build
```

## License

[GNU GPL v3](https://github.com/bk2dcradle/researcher/blob/gh-pages/LICENSE)
