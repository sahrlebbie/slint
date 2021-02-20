# slint

This repo serves as part of Splunk Automation build for SLINT Demo.

It can do a few things but aslo assumes other things as well. The assumptions are very important because they are dependencies on the package in this repo successfully working. 

ASSUMPTIONS:

1) You have internet access or satellite access to install wget,git, curl, tcpdump, telnet, and a few other tools.You may elect to modify which utilities to modify.
2) You have enough permissions to install packages on /opt of the server at hand.
3) You are installing this package on a Redhat/Centos Linux Server.

Actions of Script
1) **Installs a few utilities to prep for download.*
2) **Downloads Splunk Enterprise 8.1.2.
3) **Installs Splunk
4) **Monitors Python Script
5)**Sets Port
6) Enables Web SSL
7) **Sets Login Page Logo(SLinT Logo)
8)****Monitors Scraped Web Results from DSTI Python script
