**vmaki** is a web-based Management Application for the _Xen Hypervisor_ that allows its users to administer a number of host servers and their Dom0 guests **without** any technical knowledge. It is built on _Ruby on Rails_ and _ExtJS_. The communication between those two is based upon the RESTful architecture and allows for **easy integration** into other applications.

Installation is done via a Debian package, which installs and configures all required dependencies (incl. Xen, NFS & PostgreSQL).

A Getting Started guide can be found [here](http://code.google.com/p/vmaki/wiki/GettingStarted).

## Requirements ##
  * A physical host running Debian Lenny
  * Xen 3.2
  * PostgreSQL
  * libvirt
  * Ruby on Rails 2.3

## Features ##
  * No Xen knowledge required!
  * Supports HVM and paravirtualized VMs
  * Fully automated provisioning of Debian Lenny based paravirtualized guests
  * A slick, desktop-like user interface
  * A RESTful API with XML and JSON interfaces allowing easy integration & automation

## Screenshots ##
[![](http://vmaki.googlecode.com/files/overview_small.png)](http://code.google.com/p/vmaki/wiki/Screenshots)
[![](http://vmaki.googlecode.com/files/vnc1_small.png)](http://code.google.com/p/vmaki/wiki/Screenshots)
[![](http://vmaki.googlecode.com/files/vnc2_small.png)](http://code.google.com/p/vmaki/wiki/Screenshots)
[![](http://vmaki.googlecode.com/files/vnc3_small.png)](http://code.google.com/p/vmaki/wiki/Screenshots)
[![](http://vmaki.googlecode.com/files/vnc4_small.png)](http://code.google.com/p/vmaki/wiki/Screenshots)