---
layout: page
title: Summit
permalink: /summit/
---

## OpenXT Summit 2016


The inaugural OpenXT Summit brings together developers and ecosystem participants for a 2-day conference in Fairfax, VA on June 7-8, 2016.

### Registration

There is no fee for attendance, but space is limited.  To reserve a seat, please email persaur at gmail dot com, including your first name, last name and organizational affiliation.  Building security will check identification against the list of registered attendees.

### Location

The event will take place at [Intel Corporation](https://goo.gl/maps/hqaSDhDshx62), 4100 Monument Corner Drive, Suite 540, Fairfax, VA 22030.

### Presentation Agenda: Tuesday 7 June, 2016

 * 08:45 Introduction, *Speaker TBD*
 
 * 09:00 Secure Virtual Platform Research, *Speaker TBD*
 
 * 09:45 OpenXT Platform, *Ross Philipson*, Assured Information Security
 
 > Can OpenXT be moved towards an extensible platform model? The key concepts to be covered are, (a) minimal base platform with core security attributes central to OpenXT, (b) layers that enable the base platform to be easily extended and customized.
 
 * 10:15 Human Interface Devices, *Jean-Edouard Lejosne*, Assured Information Security

 > This presentation will start with an overview of the way human input (keyboard, mouse, touchscreens, ...) is managed by OpenXT today: without tools (emulated) and with tools (backend-frontend). We will then present a new architecture for the latter, SuperHID, that eliminates the need for guest drivers, by surfacing standard HID USB devices through the existing USB backend-frontend mechanism.

 * 10:45 Break

 * 11:00 meta-selinux, grub2, TPM2, *Philip Tricca*, Intel Corp.

 * 11:30 Measured Launch, *Daniel Smith*, Apertus Solutions

 * 12:00 Lunch

 * 13:00 Looking to the Future: ARM Client Virtualization and Operating with an Untrusted dom0, *Kyle Temkin*, Assured Information Security
 
 > As the OpenXT platform has developed and matured, the upstream Xen community has focused on a number of new architectural developments and enhancements—many of which can be used to significantly enhance the OpenXT project. This talk explores two separate areas that may significantly shape the future of OpenXT: the development of client virtualization support for ARM platforms, and the potential to leverage new Xen features and disaggregation techniques to significantly improve OpenXT’s security posture

 * 13:30 Display Handlers, *Brendan Kerrigan*, Assured Information Security

 * 14:00 Toolstack Modernization, *Chris Rogers*, Assured Information Security
 
 > Much OpenXT development over the past year has been motivated by our desire to bring the code base more in line with upstream counterparts.  The Modernization of the toolstack is another such effort.  Until now, OpenXT has used a XenServer-derived toolstack component (xenvm) underneath a domain management-level component (XenMgr). Since the Xen Project has adopted XL as its default toolstack, OpenXT should do the same in order to further reduce technical debt and support newer versions of Xen. Specifically, the Toolstack Modernization effort incorporates libXL into the base platform and focuses on four major areas of integration: communication between XenMgr and libXL, linux-based stubdomains on libXL, removal of old helper daemons such as dm-agent, and support for newer versions of blktap.
 
 * 14:30 Test Automation (UI, ATF, BVT), *Garrett Morgan*, Assured Information Security
 
 > How do we implement an automated test framework on a virtualized platform?  The current CLI-based implementation (BVT) provides a great foundation, and is currently being expanded.  In parallel, a UI-based OO automation framework/plugin is being explored which utilizes Intel's AMT KVM and the SikuliX Java application.  As with any automated framework, certain compromises are made, and by integrating the two technologies we look to expand the testing capabilities and bring the test devices as close to a production configuration as possible.
 
 * 15:00 Break

 * 15:15 Intel Software Guard Extensions (SGX), *Jacob Torrey*, Assured Information Security
 
> As networks become increasingly targeted by attackers in search of sensitive data, a new data protection model is arising: one in which data must be protected even on contested networks. In this new paradigm, a stronger isolation boundary is needed than the current process model of the status quo: hardware-enforced enclaves are a step towards true data protection in contested networks. This talk provides a background of enclaves provided by Intel SGX, followed by an example case study of well-known malware that could have been prevented through the deployment of enclave technologies. Finally a discussion on the weaknesses of the current enclave technologies is provided before concluding remarks.
 
 * 15:45 Topic TBD, *Speaker TBD*, Intel Corp.
 
 * 16:15 ServiceVMs and why APIs matter, Daniel Smith, Apertus Solutions
 
 * 16:45 Virtualization Business Models, *Rich Persaud*, BAE Systems
 
 * 17:15 End of Day 1 presentations 

### Discussion Agenda: Wednesday 8 June, 2016

 * 09:00 Definition: Base Platform
 * 09:30 Definition: Layers and Modular Build
 * 10:00 Definition: Display Architectures, UX
 * 10:40 Break
 * 11:00 Planning: Upstream Xen and OpenEmbedded
 * 11:30 Planning: Governance
 * 12:00 Lunch
 * 13:00 Strategy: UEFI, SecureBoot, TPM2, Virtual TPM, VMCS Shadowing
 * 13:30 Strategy: Modular Policy (SE Linux, XSM, Toolstack, Service VM)
 * 14:00 Strategy: Tablets and ARM
 * 14:30 Strategy: Use Case Spectrum
 * 15:00 Break
 * 15:20 Strategy: Platform APIs, Ecosystem Interfaces, Compatibility, HCL
 * 16:00 Planning: 2016 Roadmap and Timeline
 * 17:00 End of Day 2 discussions
 

### Hotels

 * 2 miles, [Fairfax Marriott at Fair Oaks](http://www.marriott.com/hotels/travel/iadmc-fairfax-marriott-at-fair-oaks/)
 * 2 miles, [Hilton Garden Inn Fairfax](http://hiltongardeninn3.hilton.com/en/hotels/virginia/hilton-garden-inn-fairfax-IADFHGI/index.html)
 * 2 miles, [Hyatt Regency Fairfax](http://fairfax.regency.hyatt.com/en/hotel/home.html)
 * 3 miles, [Hampton Inn Fairfax City](http://hamptoninn3.hilton.com/en/hotels/virginia/hampton-inn-fairfax-city-FFCVAHX/index.html)
 * 8 miles, [Westin Reston Heights](http://westinreston.com)

### Air and Train

 * 6 miles, Washington Metro station, Vienna/Fairfax-GMU (Orange Line)
 * 12 miles, Dulles (IAD) Airport
 * 22 miles, Washington Reagan (DCA) Airport
 * 24 miles, Amtrak Union Station