# Basic Sysadmin
This contains the basics of setting up a "clean" install that you might launch on AWS. The base AMI images (for RedHat or Ubuntu, for example) come quite bare - which is a good thing! Doing updates and getting the basic software installed can be daunting when you start out, but the ability to customize your workstation can open up lots of new possibilities. It will also help you upgrade and troubleshoot issues when (not if!) they come up.

## Ubuntu 20.04
This is based on:
`Ubuntu Server 20.04 LTS (HVM), SSD Volume Type - ami-0d058fe428540cd89 (64-bit x86)`

Setting up a system is split into the following steps (that progressively get more and more specific / bespoke:

* [General system updates](system.md)
* R and Bioconductor
* Python
* Common bioinformatics software