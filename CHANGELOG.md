# Changelog

## v2.1.1

- (#31) Migrate from Travis-CI to GitHub Actions for CI
- (#32) Fix data population when generating configurations from the dispatcher

## v2.1.0

- (#26) Updates in poetry packaging for pre 1.0.0 dependencies in Nornir to allow all new up to 1.0.0 releases

## v2.0.3

- (#24) Change import mechanism / changes deprecated function

## v2.0.1

- (#20) Fixes inventory failure when platform is not defined for a device
## v2.0.0

- (#18) Migrates functions to new NTC netutils library, which is removing methods previously available:
  - compliance
  - make_folder
  - hostname_resolves
  - test_tcp_port
  - is_ip

## v0.1.0 - 2020-12-27

Initial release
