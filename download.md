---
layout: page
title: Download
permalink: /download/
---

## Unstable Binary

This is a daily build of the most recent OpenXT source, generated at 2014-10-15 05:10 UTC.

+ OpenXT daily [Installer ISO](http://openxt.org/build/unstable/openxt-installer-12345.iso) 
+ OpenXT daily [Guest Tools](http://openxt.org/build/unstable/openxt-guest-tools-12345.zip)
+ [Archive of older builds](http://openxt.org/build/unstable/archive)

## Quality Assurance

OpenXT manual and automated test cases need to be triaged:  

+ [Manual Test Cases](https://github.com/OpenXT-Extras/test-cases/blob/master/OpenXT_Test_Cases.doc)
+ [Automated Test Harness](https://github.com/OpenXT-Extras/bvt) &middot; Test Cases ?
+ OpenXT [Administrator Guide](https://github.com/OpenXT-Extras/docs/blob/master/XTEngineAdministratorGuide.pdf?raw=true)

Automated testing for Xen and XenServer:

+ XenRT [Code](http://xenserver.org/discuss-virtualization/virtualization-blog/entry/introducing-open-source-xenrt.html) &middot; [Architecture](http://wiki.xen.org/wiki/XenRT_Architecture_Guide) &middot; [Getting Started](http://wiki.xen.org/wiki/Getting_Started_with_XenRT) &middot; [User Guide](http://wiki.xenproject.org/wiki/XenRT_User_Guide) 
+ Nov 2013, Alex Brett, Test-as-a-Service: [video](http://www.youtube.com/watch?v=s11_Iw7AI_U) &middot; [slides](http://events.linuxfoundation.org/sites/events/files/slides/XenSummit%20TaaS%20and%20XenRT_0.pdf)
+ Sep 2013, OSSTest [Standalone Mode Step by Step](https://blog.xenproject.org/2013/09/30/osstest-standalone-mode-step-by-step/)
+ Nov 2009, [Practical Xen Testing at Intel](http://www.slideshare.net/xen_com_mgr/practical-xen-testing-at-intel)
+ 2005, IBM, [Testing the Xen Hypervisor and Linux Virtual Machines](https://www.kernel.org/doc/ols/2005/ols2005v1-pages-279-288.pdf)

Automated testing for Linux distros:

+ [LSB DTK Manager Nightly](http://ispras.linuxbase.org/index.php/LSB_DTK_Manager_Nightly_Run_HOWTO) &middot; [Wrapper](https://wiki.linuxfoundation.org/en/Distribution_Autotesting)
+ Phoronix Test Suite, Linux Benchmarking [History](http://en.wikipedia.org/wiki/Phoronix_Test_Suite) &middot; [Software](http://www.phoronix-test-suite.com/)
+ Kernel Autotest: [Testing the Untestable](https://www.kernel.org/doc/ols/2009/ols2009-pages-9-18.pdf) &middot; [Software](http://autotest.github.io/) &middot; [virt-test](http://virt-test.readthedocs.org/en/latest/)
+ Apr 2012, Lars Wirzenius, [Re-thinking system and distro development](http://liw.fi/rethinking-distro-dev/)
+ Fedora 18+ [Testing secureboot with KVM](https://fedoraproject.org/wiki/Testing_secureboot_with_KVM)

## Hardware Disclaimer

As an open-source project, OpenXT does not offer any guarantee of compatibility with specific hardware models or BIOS versions.  Hardware is tested by OEMs and integrators of vertical solutions based on the OpenXT toolkit.  Please contact your [OEM or system integrator]({{ site.baseurl }}/interoperability) for more information about hardware compatibility.

The devices on this page have exhibited, *at some time in the past*, a model and BIOS combination which enabled the TPM, VT-d (NIC/GPU passthrough) and TXT (measured launch) hardware functions used by OpenXT components.  This does not guarantee that any current device model and BIOS combination will be compatible with any software binary derived from the OpenXT toolkit.

Intel maintains a list of Dell, HP & Lenovo [vPro devices](https://msp.intel.com/find-a-vpro-system). OpenXT requires devices with integrated Intel GPUs, for the [Sandy Bridge](http://en.wikipedia.org/wiki/Sandy_Bridge), [Ivy Bridge](http://en.wikipedia.org/wiki/Ivy_Bridge_%28microarchitecture%29) and [Haswell](http://en.wikipedia.org/wiki/Haswell_%28microarchitecture%29) generations.

#### Ivy Bridge &mdash; Anecdotal Reports

+ Dell Latitude 6630, 6530, 6430, 6430S, 6230, Optiplex 9010
+ HP 8570p, 8470p, 2170p, Folio 9470m, Elite 8300, Z220 Workstation
+ Lenovo X230, T530, T430, T430s, X1 Carbon, M92p


#### Sandy Bridge &mdash; Anecdotal Reports

+ Dell Latitude 6420, 6220, Optiplex 990
+ HP 8460p, 2760p, 2560p, Elite 8200
+ Lenovo T520, M91p 

#### PCI Discrete NIC &mdash; Anecdotal Reports

+ Broadcom NetExtreme II
+ Allied Telesis Optical

#### PCI Discrete GPU &mdash; Anecdotal Reports

+ ATI Radeon HD 4550, HD 5450, HD 5500, HD 6570

