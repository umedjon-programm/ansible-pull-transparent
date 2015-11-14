#Overview
This project is a sub-project of the [JVM Development Environment](https://github.com/kurron/jvm-development-environment). 
The Ansible plays described here will be applied to the Vagrant environment being built.  The purpose of this project 
is to install a variety of corporate-specific tools and conveniences into the Vagrant box.

#Prerequisites
Nothing additional to what is required by the JVM Development Environment project. 

#Building
All the components of the environment live in repositories on the internet so there is nothing to build.

#Installation
This project is intended to be invoked by the JVM Development Environment project so there is no installation step.

#Tips and Tricks

##Some Conveniences Provided

* install Docker containers for many of the services used by the development team, including MongoDB and RabbitMQ
* install the necessary pieces to access the corporate Docker registry
* create root folders for all of the current projects stored under BitBucket
* update the `/etc/hosts` file with entries to machines that are not in DNS

#Troubleshooting

#License and Credits
This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

#List of Changes

