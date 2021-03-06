# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)


### Unreleased as of Sprint 82 - 2018-03-26

### Fixed
- Get mac addr if the selected profile is '<Empty>' or '<Template>' [(#227)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/227)

## Gaprindashvili-2 released 2018-03-06

### Fixed
- Fix target host [(#155)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/155)
- Move refresh settings for the Network Manager [(#198)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/198)
- Fix adding vm_location to vm event hash [(#205)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/205)
- Fix updating catalog item when provider missing [(#206)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/206)

### Unreleased as of Sprint 80 - 2018-02-26

### Fixed
- Fix graph targeted host refresh spec [(#213)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/213)
- Discovery namespace change [(#209)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/209)
- Update client to use renamed NetworkDiscovery [(#208)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/208)
- Use correct refresh for older providers [(#207)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/207)

### Unreleased as of Sprint 79 - 2018-02-12

### Fixed
- Add fix and add specs for graph targeted refresh [(#203)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/203)

## Gaprindashvili-1 - Released 2018-01-31

### Added
- Reload provider when api_version available [(#157)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/157)
- Check metrics details from `raw_connect` [(#134)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/134)
- Set default tag category in 'Transform VM' dialog [(#135)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/135)
- Save host 'maintenance' value [(#147)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/147)
- Add admin_ui feature support to InfraManager [(#133)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/133)
- Update Engine version check for admin_ui feature [(#148)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/148)
- oVirt network provider support routers, security groups and floating ips [(#144)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/144)
- Introducing OVN as oVirt's network provider [(#90)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/90)
- Honour `open_timeout` when using V4 [(#126)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/126)
- Handle partial vm entity during creation [(#129)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/129)

### Changed
- Change "Empty" to "No Profile" in profile list [(#151)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/151)

### Fixed
- Raise Miq exceptions on connect [(#162)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/162)
- Update ems version during graph refresh [(#164)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/164)
- Fix Seal option of publish VM [(#167)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/167)
- Implement template targeted refresh [(#165)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/165)
- Handle console events [(#173)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/173)
- Targeting host fails [(#171)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/171)
- Added supported_catalog_types [(#174)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/174)
- Use supports_vm_import? instead of validate_import_vm [(#154)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/154)
- Fix credential validation if no metrics given [(#140)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/140)
- Vm provisioning do not run reconnect_events [(#138)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/138)
- Fix remote console for v4 [(#145)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/145)
- Fix version check in supports_admin_ui method [(#156)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/156)
- Avoid NoMethod error in TemplatePreloadedAttributesDecorator.new [(#106)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/106)
- Propagate user validation errors [(#104)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/104)
- Parse the serial number during refresh [(#97)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/97)
- Identify the redhat events in the core settings [(#99)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/99)
- Target new template when using api v4 [(#96)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/96)
- Support publish VM [(#95)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/95)
- Add connection manager [(#92)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/92)
- v2v: Make "install drivers" checkbox dynamic [(#76)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/76)
- Refresh a host when removed [(#127)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/127)
- Don't close connection explicitly [(#128)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/128)
- Try both API versions in `raw_connect`[(#132)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/132)
- Fix vm removal for apiv4 [(#131)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/131)
- Fix location of `pipeline` and `connections` settings [(#176)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/176)
- Unrecognized events during import from glance [(#179)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/179)
- Store ipv4/ipv6 of guest devices aligned to vmware implementaion [(#170)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/170)
- Provide missing events [(#180)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/180)
- Credential verification errors for new provider [(#188)](https://github.com/ManageIQ/manageiq-providers-ovirt/pull/188)

## Initial changelog added
