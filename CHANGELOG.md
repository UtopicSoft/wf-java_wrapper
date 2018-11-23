## rew-3.0.7 (2018-08-15)
CONTRIBUTORS
  - Maddox Morton
  - Malakai Stein
  - Vincent Noel
  - Sol Dorsey
IMPROVEMENTS
  - Updated versions 7.5.101-101

## rew-3.0.6 (TBD)
CONTRIBUTORS
  - Coen Hernandez
IMPROVEMENTS
  - Fix spec tests for Puppet 4.10.4 and rspec-puppet-2.6.9

## rew-3.0.5 (2017-09-26)
CONTRIBUTORS
  - Ian Wilde
  - Maddox Morton.
IMPROVEMENTS:
  - Updated linux to version 7.4.101-58

## rew-3.0.4  (2017-08-16)
CONTRIBUTORS:
  - Krista Osborne
IMPROVEMENTS:
  - Changing versioncmp() fail to warnings  if newer version of the product is installed.
  - If warning due to newer version installed notice message current version  and version trying to install.
  - Changing rhel72 to rhel73 for 2016.1 and 2016.4 puppet enterprise version.

## rew-3.0.3 (2017-07-31)
CONTRIBUTORS
  - Sol Dorsey
IMPROVEMENTS:
  - Updated windows to ver sion 7.4.101.58

## rew-3.0.2 (2017-05-23)
CONTRIBUTORS
  - Brandon Short
IMPROVEMENTS:
  - Supports PE 2016.4

## rew-3.0.1 (2017-01-25)
CONTRIBUTORS
  - Kelvin Huber
IMPROVEMENTS:
  - none
BUG FIXES:
  - Ensure can be set to absent without causing an error on Windows. Package already stops service before uninstalling so just set service_manage to false.

## rew-2.4.0 (2016-09-21)
CONTRIBUTORS
  - Kelvin Huber
IMPROVEMENTS:
  - Refactored version processing using Puppet 4 Selector/Validator

## rew-2.0.0 (2016-02-10)
CONTRIBUTORS
  - Raphael Roach
COMPATIBILITY
    - Puppet 2015.2, Puppet Enterprise 3.2. Windows 2008 R2, 2012 R2, RHEL 6.6
BREAKING CHANGES:
  - none
IMPROVEMENTS:
  - Converted module to bunsen environment
  - Created Puppet RSpec tests
  - Created Serverspec tests ( only for install, none for registration )
DEPRECATIONS:
  - none
BUG FIXES:
  - none

## Previous
The changelog began with version rew-2.0.0 so any changes prior to that can be seen by reading git commit messages.
