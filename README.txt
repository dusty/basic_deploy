# Dusty's basic capistrano deploy script

* Inspired by http://github.com/leehambley/railsless-deploy
  Thanks Lee!

## Installation

  # gem sources -a http://gems.github.com/
  # gem install dusty-basic_deploy

## Usage

  # vi Capfile

    load 'deploy' if respond_to?(:namespace) # cap2 differentiator
    require 'rubygems'
    require 'basic_deploy'
    load    'config/deploy'

