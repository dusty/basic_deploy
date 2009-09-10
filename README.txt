# Dusty's basic capistrano deploy script

* Inspired by http://github.com/leehambley/railsless-deploy
  Thanks Lee!

## Installation

  # gem sources -a http://gems.github.com/
  # gem install dusty-basic_deploy

## Usage

  # vi Capfile

    require 'rubygems'

    begin
      require 'basic_deploy'
    rescue LoadError
      puts <<-EOD

    BASIC-DEPLOY RECIPE REQUIRED

    $ sudo gem install dusty-basic_deploy

      EOD
      exit
    end

    load 'config/deploy'

