# ProjetBlog
Step 1 – Install Ruby
Since Jekyll is written in Ruby, you will need a Ruby installation on your machine to run Jekyll. In Linux, you can install it using Snap or Apt package manager.

Install using apt package manager.
First, update your apt repositories to look for the latest Ruby version.

$ sudo apt-get update
Then install Ruby.

$ sudo apt-get install ruby-full
Install using Snap package manager.
$ sudo snap install ruby --classic
If you are running macOS, you can install Ruby using Homebrew.

$ brew install ruby
For Linux, you’ll need to set up a gem installation directory to prevent permission errors. Add the lines below at the bottom of the .bashrc file located in the home folder.

export GEM_HOME="$HOME/gems"
export PATH="$HOME/gems/bin:$PATH"
You can use the echo command to append the above lines at the bottom of the .bashrc file.

$ echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
$ echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
Then execute the .bashrc file.

$ source ~/.bashrc
Step 2 – Install Jekyll
Jekyll comes as a Ruby Gem and can be installed in any system running Ruby. Run the command below in a terminal to install Jekyll.

$ gem install jekyll bundler

To run the website locally 

$ cd folder location

$ bundle exec jekyll serve
