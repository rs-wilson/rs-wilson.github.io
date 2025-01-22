# Personal Site
This is the code for my personal site, mysteriouslever.com. It is powered by github pages, jekyll, and minimal mistakes.

https://mmistakes.github.io/minimal-mistakes/

## Dev
[Get the osx cmd tools](https://developer.apple.com/downloads/index.action?name=for%20Xcode)  
`brew install rbenv`  
`rbenv init` (add to dot profile)  
`rbenv install 3`  
`rbenv global 3`
`gem install --user-install bundler jekyll`  
`bundle config set --local path 'vendor/bundle'`  
`bundle install`  
`bundle update` (or, delete the current Gemfile.lock and just install the latest - could be dangerous but also we want to keep up to date for security reasons)  
`bundle exec jekyll serve`  
