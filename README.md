# My Rails Installs 2025
To help me and my friends remember how to start a project the way we like.

## RVM
RVM is a command-line tool which allows you to easily install, manage, and work with multiple ruby environments from interpreters to sets of gems.
https://rvm.io/

It's important to me a version manager because some projects I work with are from old ruby versions, and I am sure the new projects one day will be the old ones.

Today ruby version is 3.2.2.

Important: if I am not mistaken, I had to install curl before RVM.

Ubuntu:
```
sudo apt install curl
```

## Rails
Taday rails version is 8.0.2.
https://guides.rubyonrails.org/install_ruby_on_rails.html

## MySQL
I use MySQL... And I always have problems installing it, but since we have to install it only one time I never remeber what I had to go through...

https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-20-04

Inside a Rails Project you have to change the gems to use mysql.

Gemfile:
```ruby
# Use sqlite3 as the database for Active Record
# gem "sqlite3", ">= 2.1"
gem "mysql2"
```
