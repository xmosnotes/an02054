:orphan:

##############################################################
AN02054: Using an XCORE.AI QF60 to make a dual-ethernet device
##############################################################

:vendor: XMOS
:version: 1.0.0
:scope: Example
:description: Demonstrates the capability of XCORE.AI-QF60 to drive dual Ethernet
:category: General Purpose
:keywords: Ethernet, Audio
:hardware: 


*******
Summary
*******

This app note demonstrates how a small XCORE.AI device (a 6x6mm
QF60 part) can be used to drive dual 100 Mbit ethernet. This platform
can be used to, for example, implement redundancy or indeed a limited
daisy-chain. This note focusses on the hardware design; the only
software provided is the drivers for the hardware. The main program is
empty otherwise.

********
Features
********

* Dual RMII 100 Mbit ethernet
* Audio CODEC

************
Known issues
************

* None

**************
Required tools
**************

* XMOS XTC Tools: 15.3.1

*********************************
Required libraries (dependencies)
*********************************

* lib_ethernet

*************************
Related application notes
*************************

* `AN00000 - an00000 title <https://www.xmos.com/application-notes/an00000>`_
* `AN00001 - an00001 title <https://www.xmos.com/application-notes/an00001>`_

