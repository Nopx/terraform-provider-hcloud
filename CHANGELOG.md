Changelog
=========

v1.2.0 (Unreleased)
------

* improved test coverage
* resource update methods return the result of the read method
* removed `reverse_dns` property of `hcloud_floating_ip`, because it was not useable, see https://github.com/hetznercloud/terraform-provider-hcloud/issues/32

v1.1.0 (March 2, 2018)
------

* Save hashsum of `user_data`, existing state is migrated
* update hcloud-go to v1.4.0
* update terraform from v0.11.2 to v0.11.3

v1.0.0 (January 30, 2018)
------
* Initial release
