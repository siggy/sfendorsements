# sfendorsements

November 2022 SF Election Endorsements

Inspired by https://sfendorsements.com/

## Dev setup

### Ubuntu

From https://jekyllrb.com/docs/installation/ubuntu/

```bash
sudo apt install rbenv

sudo apt-get install ruby-full build-essential zlib1g-dev

echo 'eval "$(rbenv init -)"' >> ~/.local.bash

echo '# Install Ruby Gems to ~/gems' >> ~/.local.bash
echo 'export GEM_HOME="$HOME/gems"' >> ~/.local.bash
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.local.bash
source ~/.bashrc

gem install public_suffix -v 4.0.7
gem install jekyll bundler

jekyll new --skip-bundle .


gem update --system 3.2.3
```
