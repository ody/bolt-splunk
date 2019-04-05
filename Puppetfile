# frozen_string_literal: true

forge "http://forge.puppetlabs.com"

moduledir File.join(File.dirname(__FILE__), 'modules')

mod 'puppetlabs-package', '0.3.0'
mod 'puppetlabs-service', '0.4.0'
mod 'puppetlabs-puppet_conf', '0.3.0'
mod 'puppetlabs-facts', '0.3.1'
mod 'puppet_agent',
    git: 'https://github.com/puppetlabs/puppetlabs-puppet_agent',
    ref: '443c9b2dc8e7b302fbac83976887e4ea011365a5'

# Core types and providers for Puppet 6
mod 'puppetlabs-augeas_core', '1.0.3'
mod 'puppetlabs-host_core', '1.0.1'
mod 'puppetlabs-scheduled_task', '1.0.0'
mod 'puppetlabs-sshkeys_core', '1.0.1'
mod 'puppetlabs-zfs_core', '1.0.1'
mod 'puppetlabs-cron_core', '1.0.0'
mod 'puppetlabs-mount_core', '1.0.2'
mod 'puppetlabs-selinux_core', '1.0.1'
mod 'puppetlabs-yumrepo_core', '1.0.1'
mod 'puppetlabs-zone_core', '1.0.1'

# If we don't list these modules explicitly, r10k will purge them
mod 'canary', local: true
mod 'aggregate', local: true
mod 'puppetdb_fact', local: true

# Building out Splunk Bolt Quickstart

mod 'profiles', local: true
mod 'puppetlabs-stdlib', '5.2.0'
mod 'puppetlabs-inifile', '2.5.0'
mod 'puppetlabs-concat', '5.3.0'
mod 'puppet-archive', '3.2.1'
#mod 'puppetlabs-amazon_aws', '0.2.0'

# Need to rest updated version of module
#mod 'puppet-splunk', '7.3.0'
mod 'puppet-splunk',
    git: 'https://github.com/nick-markowski/puppet-splunk',
    ref: '7_2_support'
