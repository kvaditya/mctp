# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## Unreleased

### Added

1. mctpd: Add support for endpoint recovery
2. mctpd: Allow recovery of devices reporting a nil UUID for development

### Changed

1. dbus interface: the NetworkID field is now a `u` rather than an `i`, to
   match OpenBMC's MCTP endpoint specification

## [1.1] - 2023-04-13