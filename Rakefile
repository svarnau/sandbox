require 'rubygems'
require 'puppetlabs_spec_helper/rake_tasks'
require 'puppet-lint/tasks/puppet-lint'
PuppetLint.configuration.fail_on_warnings = true
PuppetLint.configuration.send('disable_80chars')

#
# Disable check due to upstream bug: https://github.com/rodjek/puppet-lint/issues/170
PuppetLint.configuration.send('disable_class_parameter_defaults')
