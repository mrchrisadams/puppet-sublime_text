# Sublime Text Puppet Module for Boxen

[![Build Status](https://travis-ci.org/boxen/puppet-sublime_text.png?branch=master)](https://travis-ci.org/boxen/puppet-sublime_text)

Install [Sublime Text](http://www.sublimetext.com//), a text-editor/IDE for Mac

Current Version: 3 Beta (Build 3059)
## Usage

```puppet
include sublime_text
sublime_text::package { 'Emmet':
  source => 'sergeche/emmet-sublime'
}
```

## Required Puppet Modules

None.
