---
layout: page
title: Development
permalink: /development/
---

Please read the draft [contribution](https://github.com/OpenXT/openxt/wiki/Contributing) guidelines. There are 50+ source repositories on [Github](https://github.com/openxt), with [build instructions](https://github.com/OpenXT/openxt/wiki/How%20to%20build%20OpenXT).  Issues and enhancements are tracked in [JIRA](https://openxt.atlassian.net).

The documents below are dated, especially with respect to video architecture, but may be useful to new developers.  They will be converted to the Github wiki and edited to revise or remove dated sections.

+ [OpenXT Architecture Guide](https://github.com/OpenXT-Extras/docs/blob/master/XTArchitectureGuide.pdf?raw=true)
+ [OpenXT Appliance Developer Guide](https://github.com/OpenXT-Extras/docs/blob/master/XTEngineDeveloperGuide.pdf?raw=true)
+ [OpenXT Appliance Administrator Guide](https://github.com/OpenXT-Extras/docs/blob/master/XTEngineAdministratorGuide.pdf?raw=true)
+ [OpenXT Management Administrator Guide](https://github.com/OpenXT-Extras/docs/blob/master/XTSynchronizerAdministratorGuide.pdf?raw=true)

We are hosting a [mirror](http://openxt.org/mirror) of 3rd-party components needed for an appliance build. Please cache these files locally and build from your local mirror. The system hosting the mirror has limited bandwidth. 

Questions and feedback on OpenXT are welcome on the [mailing list](https://groups.google.com/forum/#!forum/openxt).

### Hardware Platform

+ Dell, HP & Lenovo [vPro laptops and desktops](https://msp.intel.com/find-a-vpro-system): [Sandy Bridge](http://en.wikipedia.org/wiki/Sandy_Bridge), [Ivy Bridge](http://en.wikipedia.org/wiki/Ivy_Bridge_%28microarchitecture%29) or [Haswell](http://en.wikipedia.org/wiki/Haswell_%28microarchitecture%29)
+ AMD discrete GPUs for desktop PCI passthrough 

### Breakage Basics

+ Stanford U, [CS155: Computer and Network Security](http://crypto.stanford.edu/cs155/) &middot; [old projects](http://crypto.stanford.edu/cs155old/) &mdash; [old solution](http://blogs.hulmahan.com.ph/archives/category/hack-101)
+ Exploit [Development](https://www.corelan.be/index.php/category/security/exploit-writing-tutorials/) &middot; [Exercises](http://exploit-exercises.com/) &middot; [Wargames](http://smashthestack.org/faq.html#a1)
+ Reversing [Tutorials](https://tuts4you.com/download.php?list.17) &middot; [Phrack](http://phrack.org/issues/1/1.html) &middot; [Fravia](http://en.wikipedia.org/wiki/Fravia) 
+ 2010 book: [A Guide to Kernel Exploitation](http://www.amazon.com/Guide-Kernel-Exploitation-Attacking-Core/dp/1597494860) by Enrico Perla et al. 
+ 2012 book: [Practical Malware Analysis](http://www.amazon.com/Practical-Malware-Analysis-Dissecting-Malicious/dp/1593272901/) by Michael Sikorski et al.
+ 2014 book: [Practical Reverse Engineering](http://www.amazon.com/Practical-Reverse-Engineering-Reversing-Obfuscation/dp/1118787315) by Bruce Dang et al.

### Operating Systems Basics

+ OS Development: [Wiki](http://wiki.osdev.org) &middot; [Forum](http://forum.osdev.org)
+ Xen [Wiki](http://wiki.xenproject.org/wiki/Main_Page) &middot; [dom0 distros](http://wiki.xenproject.org/wiki/Dom0_Kernels_for_Xen) &middot; [List Search](http://www.xenproject.org/help/mailing-list.html) 
+ Linux [From Scratch](http://www.linuxfromscratch.org/) &middot; [Kernel Newbies](http://kernelnewbies.org/KernelHacking) &middot; [KVM](http://www.linux-kvm.org/page/Main_Page) &middot; [LWN](https://lwn.net/Archives/)
+ FreeBSD [Developer](https://www.freebsd.org/doc/en_US.ISO8859-1/books/developers-handbook/index.html) and [Architecture](https://www.freebsd.org/doc/en_US.ISO8859-1/books/arch-handbook/index.html) Handbooks &middot; [Xen Port](https://wiki.freebsd.org/FreeBSD/Xen) &middot; [List Search](https://www.freebsd.org/search/)
+ Assembly Language: [x32](http://www.drpaulcarter.com/pcasm/index.php) &mdash; [x64](https://software.intel.com/en-us/articles/introduction-to-x64-assembly) &middot; [CMU](http://www.cs.cmu.edu/~fp/courses/15213-s07/misc/asm64-handout.pdf) &middot; [Intel](http://www.intel.com/content/www/us/en/processors/architectures-software-developer-manuals.html) &middot; [AMD](http://developer.amd.com/resources/documentation-articles/developer-guides-manuals/) &middot; [processor](http://sandpile.org/)

### Operating Systems Courses

+ Carnegie Mellon U, [Intro to Computer Systems 2013](http://www.cs.cmu.edu/afs/cs/academic/class/15213-f13/www/schedule.html), *USA*
+ U of Birmingham, [Operating Systems with C/C++ 2013/14](http://www.cs.bham.ac.uk/~exr/lectures/opsys/13_14/lectures.php), *UK*
+ M.I.T., [OS Engineering 2011](http://pdos.csail.mit.edu/6.828/2011/schedule.html) &middot; [Xv6 Teaching OS](http://pdos.csail.mit.edu/6.828/2014/xv6.html) &middot; [OpenCourseware 2006](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-828-operating-system-engineering-fall-2006/), *USA*
+ Stanford U, Advanced OS Topics 2013: [readings](http://www.scs.stanford.edu/13wi-cs240/sched/) &middot; [notes](http://www.scs.stanford.edu/13wi-cs240/notes) &middot; [HiStar Teaching OS](http://www.scs.stanford.edu/histar/), *USA*
+ U of New South Wales, [Advanced OS 2014, Microkernels, seL4](http://www.cse.unsw.edu.au/~cs9242/14/lectures/), *Australia*
+ U of New South Wales, [Lions' Commentary on UNIX 6th Edition](http://en.wikipedia.org/wiki/Lions%27_Commentary_on_UNIX_6th_Edition,_with_Source_Code), *Australia*


