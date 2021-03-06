# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)


## Unreleased as of Sprint 94 ending 2018-09-10

### Added
- Use the EvmDatabase method for evm-failover-monitor ExecStart [(#202)](https://github.com/ManageIQ/manageiq-appliance/pull/202)

## Unreleased as of Sprint 91 ending 2018-07-30

### Added
- Add support for OpenID-Connect [(#200)](https://github.com/ManageIQ/manageiq-appliance/pull/200)

## Unreleased as of Sprint 89 ending 2018-07-02

### Added
- Add .ansible.cfg for ansible-playbook [(#196)](https://github.com/ManageIQ/manageiq-appliance/pull/196)

## Gaprindashvili-3 released 2018-05-15

### Fixed
- Use version 2 of appliance console [(#183)](https://github.com/ManageIQ/manageiq-appliance/pull/183)
- httpd reload is not needed with copytruncate [(#185)](https://github.com/ManageIQ/manageiq-appliance/pull/185)

### Removed
- Remove reindex and vacuum scripts [(#180)](https://github.com/ManageIQ/manageiq-appliance/pull/180)

## Unreleased as of Sprint 84 ending 2018-04-23

### Fixed
- httpd reload is not needed with copytruncate [(#185)](https://github.com/ManageIQ/manageiq-appliance/pull/185)

## Unreleased as of Sprint 81 ending 2018-03-12

### Added
- Optimize PostgreSQL Settings for 4x12GB Applaince [(#181)](https://github.com/ManageIQ/manageiq-appliance/pull/181)

### Removed
- Remove reindex and vacuum scripts [(#180)](https://github.com/ManageIQ/manageiq-appliance/pull/180)

## Gaprindashvili-2 released 2018-03-06

### Fixed
- Allow local replication connections [(#178)](https://github.com/ManageIQ/manageiq-appliance/pull/178)

## Gaprindashvili-1 - Released 2018-01-31

### Added
- Configure PostgreSQL ssl by default [(#162)](https://github.com/ManageIQ/manageiq-appliance/pull/162)
- Restore the context of usr/bin for docker executable issues [(#160)](https://github.com/ManageIQ/manageiq-appliance/pull/160)
- Add miqldap_to_sssd launcher [(#134)](https://github.com/ManageIQ/manageiq-appliance/pull/134)

### Changed
- Rename ws to api to not be confused with websockets [(#131)](https://github.com/ManageIQ/manageiq-appliance/pull/131)

### Fixed
- Add /usr/local/bin to the path if it is missing [(#159)](https://github.com/ManageIQ/manageiq-appliance/pull/159)
- Use a better command to add /usr/local/bin to the path [(#161)](https://github.com/ManageIQ/manageiq-appliance/pull/161)
- Increase applinace_console version in manageiq-appliance-dependencies.rb to 1.1 [(#163)](https://github.com/ManageIQ/manageiq-appliance/pull/163)
- mute cron mail when no error [(#152)](https://github.com/ManageIQ/manageiq-appliance/pull/152)
- Use a login shell for the failover monitor service [(#155)](https://github.com/ManageIQ/manageiq-appliance/pull/155)
- Add support for the domain user attribute [(#127)](https://github.com/ManageIQ/manageiq-appliance/pull/127)
- ExecStart requires an absolute executable path [(#151)](https://github.com/ManageIQ/manageiq-appliance/pull/151)

## Unreleased as of Sprint 77 ending 2018-01-15

### Added
- Adding alias apcli for appliance_conosle_cli [(#175)](https://github.com/ManageIQ/manageiq-appliance/pull/175)

### Fixed
- Update manageiq-appliance_console to minimum v1.2.3 [(#168)](https://github.com/ManageIQ/manageiq-appliance/pull/168)
- Enable rewrite engine for http and https [(#167)](https://github.com/ManageIQ/manageiq-appliance/pull/167)

## Unreleased as of Sprint 74 ending 2017-11-27

### Fixed
- Add trailing slash to cockpit machine urls [(#148)](https://github.com/ManageIQ/manageiq-appliance/pull/148)

## Fine-1

### Fixed
- Add the tower log files to our rotation script [(#120)](https://github.com/ManageIQ/manageiq-appliance/pull/120)
- Generate new certificate when the default one is not present [(#119)](https://github.com/ManageIQ/manageiq-appliance/pull/119)

## Added initial changelog
