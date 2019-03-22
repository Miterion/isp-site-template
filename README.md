# ISP Template for Jekyll Theme

This is a template site for using the isp jekyll theme. It provides a basic jekyll page in tu design which can be used as a starting point for bigger projects.
You can find the theme [here](https://github.com/Miterion/isp-theme).

## Installation
Since this is a jekyll site, it requires the same setup as jekyll.

### Linux
Install the bundler package provided by your system
#### Ubuntu/Mint/Debian
```# apt install bundler```
#### Arch Linux
``` # pacman -S ruby-bundler```

If bundler is not available for your distro install the gem tool from [here](https://rubygems.org/pages/download) and use it to install bundler 

```# gem install bundler```

After installing bundler run 

`$ bundle install --path vendor/bundle`

inside the project directory.

This should download and install all necessary dependencies locally into the vendor/bundle folder. You can then start the server using

`$ bundle exec jekyll s`

You can now visit http://locahost:4000 to see the page in action. Use the `--livereload` option, if you want the page to live reload on every change.
