# **[Work In Progress]** Stub For AMWA Network Control Specification

The stub provides a sample implementation of the APIs that have been  described in this repository. It uses the files present in the sampledata folder for data simulation.<br>    

## Usage:

./nc-sim -ip:port=\<IPADDRESS>:\<PORTNO\> -dir=\<DIRECTORY IP CONTAINING THE FILES PERTAINING TO THE SIMULATED DATA\> <br>
Eg: ./ne-sim-osx -ip:port=192.168.1.1:8282 -dir=./sampledata

## Supported Platforms
The stub has been tested on the following platforms
* macOS Sierra (10.12.3)
* CentOS Linux release 7.1.1503
* Windows 7

## Accessing the APIs
The APIs can be accessed using the URL - http://\<ip:port\>/x-nmos/netctrl//v1.0/topology/ 
