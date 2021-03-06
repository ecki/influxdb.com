+++
title = "downloads"
layout = "sidebar"
+++
# Downloads

## Version 0.9 (Stable)

### OS X

- Via [Homebrew](http://brew.sh/)

		brew update
		brew install influxdb

### Ubuntu & Debian

- 64-bit system install instructions

		wget https://s3.amazonaws.com/influxdb/influxdb_0.9.0_amd64.deb
		sudo dpkg -i influxdb_0.9.0_amd64.deb

### RedHat & CentOS

- 64-bit system install instructions

		wget https://s3.amazonaws.com/influxdb/influxdb-0.9.0-1.x86_64.rpm
		sudo rpm -ivh influxdb-0.9.0-1.x86_64.rpm

## Version 0.9 (Release Candidate)
Release candidates are made available for testing one week prior to release of the stable point release. The current release candidate is for 0.9.1.

### Ubuntu & Debian

- 64-bit system install instructions

        wget https://s3.amazonaws.com/influxdb/influxdb_0.9.1-rc1_amd64.deb
        sudo dpkg -i influxdb_0.9.1-rc1_amd64.deb

### RedHat & CentOS

- 64-bit system install instructions

        wget https://s3.amazonaws.com/influxdb/influxdb-0.9.1_rc1-1.x86_64.rpm
        sudo rpm -ivh influxdb-0.9.1_rc1-1.x86_64.rpm


## Version 0.9 (Nightly)
Nightly builds are created once-a-day using the top-of-tree of [master](https://github.com/influxdb/influxdb/tree/master) source code. These builds will include all the latest fixes, but also undergo only basic testing.

### Ubuntu & Debian

- 64-bit system install instructions

        wget https://s3.amazonaws.com/influxdb/influxdb_nightly_amd64.deb
        sudo dpkg -i influxdb_nightly_amd64.deb

### RedHat & CentOS

- 64-bit system install instructions

        wget https://s3.amazonaws.com/influxdb/influxdb-nightly-1.x86_64.rpm
        sudo rpm -ivh influxdb-nightly-1.x86_64.rpm


## Deprecated Releases

Deprecated versions are no longer actively developed.

- [version 0.8](/docs/v0.8/introduction/installation.html)
