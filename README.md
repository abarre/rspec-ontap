# RSpec On Tap

[Homepage](http://rubyworks.github.com/rspec-ontap) |
[Source Code](http://github.com/rubyworks/rspec-ontap) |
[Report Issue](http://github.com/rubyworks/rspec-ontap/issues)


## Description

**RSpec On Tap** is a TAP-Y/J formatter for RSpec.

You can learn more about TAP-Y/J [here](https://github.com/rubyworks/tapout).


## Usage

Usage is simply a matter of passing the name of the format class to
the `rspec` command via the `-f` option.

    $ rspec -r rspec/ontap -f TapY spec/*.rb

or

    $ rspec -f RSpec::TapY spec/*.rb


## Installation

Installation follows the usual pattern:

    $ gem install rspec-ontap


## Copyrights

Copyright (c) 2011 Rubyworks. All Rights Reserved.

RSpecOnTap is distributable in accordance with the *FreeBSD* license.

See COPYING.md for details.

