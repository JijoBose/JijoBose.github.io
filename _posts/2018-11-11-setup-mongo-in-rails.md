---
title: "Setup Rails with MongoDB"
published: true
---

## Create new Rails application
``
rails new AwesomeProject --skip-active-record
``

## Install the gem
``
gem 'mongoid', '~> 7.0'
``

``
gem 'bson_ext'
``

## Configure
Generate Mongoid default configuration file for you by running the following command:

``
$ rails g mongoid:config
``
