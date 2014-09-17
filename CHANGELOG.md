# knife-ec2 change log

Note: this log contains only changes from knife-ec2 release 0.8.0 and later
-- it does not contain the changes from prior releases. To view change history
prior to release 0.8.0, please visit the [source repository](https://github.com/opscode/knife-ec2/commits).

## Unreleased changes

* [KNIFE-464](https://tickets.opscode.com/browse/KNIFE-464) Support EC2 STS, i.e. AWS Federation tokens for authentication
* [KNIFE-464](https://tickets.opscode.com/browse/KNIFE-466) Knife ec2 should use gateway from net::ssh config if available
* [KNIFE-422](https://tickets.opscode.com/browse/KNIFE-422) Knife ec2 server create doesn't respect identity file of gateway server from ssh\_config

## Last release: 1.4.0 (2014-08-28)

* Merge changes from upstream

## 1.2.1 (2014-04-22)

* Add nil check to vpc tag getter

## 1.2.0 (2014-04-09)

* Add filter for server list
* Linting cleanup of ec2 server list

## 1.1.0 (2014-03-26)

* Includes all EverTrue changes, plus all changes of 0.8.0 (see below).
    * See https://github.com/evertrue/knife-ec2/compare/v0.6.5...v1.1.0 for complete changeset

## 0.8.0 (2014-03-10)

* [KNIFE-458](https://tickets.opscode.com/browse/KNIFE-458) Docs: Increase detail about necessary
  options for VPC instance creation
* [KNIFE-456](https://tickets.opscode.com/browse/KNIFE-456) Documentation for :aws\_credential\_file difficult to read
* [KNIFE-455](https://tickets.opscode.com/browse/KNIFE-455) knife ec2 may try to use private ip for vpc bootstrap even with --associate-public-ip flag
* [KNIFE-453](https://tickets.opscode.com/browse/KNIFE-453) knife-ec2 doesn't handle aws credentials files with windows line endings
* [KNIFE-451](https://tickets.opscode.com/browse/KNIFE-451) Update Fog version to 1.20.0
* [KNIFE-430](https://tickets.opscode.com/browse/KNIFE-430) server creation tunnelling should wait for a valid banner before continuing
* [KNIFE-381](https://tickets.opscode.com/browse/KNIFE-381) Gabriel Rosendorf Add ability to associate public ip with VPC
  instance on creation

## Releases prior to 0.8.0
Please see <https://github.com/opscode/knife-ec2/commits> to view changes in
the form of commits to the source repository for releases before 0.8.0.


