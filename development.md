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

## Learning

### Systems Security

+ Stanford U, [CS155: Computer and Network Security](http://crypto.stanford.edu/cs155/) &middot; [old projects](http://crypto.stanford.edu/cs155old/) &mdash; [old solution](http://blogs.hulmahan.com.ph/archives/category/hack-101)
+ Books: [Systemantics](http://en.wikipedia.org/wiki/Systemantics) (1975) &middot; [TAOSSA](http://www.amazon.com/Art-Software-Security-Assessment-Vulnerabilities/dp/0321444426/) (2006) &middot; [Kernel Exploitation](http://www.amazon.com/Guide-Kernel-Exploitation-Attacking-Core/dp/1597494860) (2010) &middot; [Malware Analysis](http://www.amazon.com/Practical-Malware-Analysis-Dissecting-Malicious/dp/1593272901/) (2012) &middot; [Reverse Engineering](http://www.amazon.com/Practical-Reverse-Engineering-Reversing-Obfuscation/dp/1118787315) (2014) 
+ Exploit [Development](https://www.corelan.be/index.php/category/security/exploit-writing-tutorials/) &middot; [Exercises](http://exploit-exercises.com/) &middot; [Wargames](http://smashthestack.org/faq.html#a1)
+ Reversing [Tutorials](https://tuts4you.com/download.php?list.17) &middot; [Phrack](http://phrack.org/issues/1/1.html) &middot; [Fravia](http://en.wikipedia.org/wiki/Fravia) 
+ History: [Boebert on Secure Coding](http://catless.ncl.ac.uk/Risks/27.25.html#subj16) &middot; [Schaefer on TCSEC](https://www.acsac.org/2004/papers/ClassicPaperSchafer.pdf) &middot; [RISKS Digest](http://catless.ncl.ac.uk/Risks/) &middot; [Cryptography List](https://www.mail-archive.com/cryptography@metzdowd.com/)



### Operating Systems Development

+ OS Development [Wiki](http://wiki.osdev.org) &middot; [Forum](http://forum.osdev.org)
+ Xen [Wiki](http://wiki.xenproject.org/wiki/Main_Page) &middot; [dom0 distros](http://wiki.xenproject.org/wiki/Dom0_Kernels_for_Xen) &middot; [Mini-OS](http://www.cs.uic.edu/~spopuri/minios.html) &middot; [List Search](http://www.xenproject.org/help/mailing-list.html) 
+ Linux [From Scratch](http://www.linuxfromscratch.org/) &middot; [Kernel Newbies](http://kernelnewbies.org/KernelHacking) &middot; [KVM](http://www.linux-kvm.org/page/Main_Page) &middot; [LWN](https://lwn.net/Archives/)
+ FreeBSD [Developer](https://www.freebsd.org/doc/en_US.ISO8859-1/books/developers-handbook/index.html) and [Architecture](https://www.freebsd.org/doc/en_US.ISO8859-1/books/arch-handbook/index.html) Handbooks &middot; [Xen Port](https://wiki.freebsd.org/FreeBSD/Xen) &middot; [List Search](https://www.freebsd.org/search/)
+ Assembly: [x32](http://www.drpaulcarter.com/pcasm/index.php) &mdash; [x64](https://software.intel.com/en-us/articles/introduction-to-x64-assembly) &middot; [CMU](http://web.archive.org/web/20140929141319/http://www.cs.cmu.edu/~fp/courses/15213-s07/misc/asm64-handout.pdf) &middot; [Intel](http://www.intel.com/content/www/us/en/processors/architectures-software-developer-manuals.html) &middot; [AMD](http://developer.amd.com/resources/documentation-articles/developer-guides-manuals/) &middot; [processor](http://sandpile.org/) &middot; [TXT](https://play.google.com/store/books/details/William_Futral_Intel_Trusted_Execution_Technology_?id=HbAAAQAAQBAJ&hl=en) &middot; [SGX](https://www.virusbtn.com/virusbulletin/archive/2014/01/vb201401-SGX)

### Operating Systems Theory

+ Carnegie Mellon U, [Intro to Computer Systems 2013](http://www.cs.cmu.edu/afs/cs/academic/class/15213-f13/www/schedule.html), *USA*
+ U of Birmingham, [Operating Systems with C/C++ 2013/14](http://www.cs.bham.ac.uk/~exr/lectures/opsys/13_14/lectures.php), *UK*
+ M.I.T., [OS Engineering 2011](http://pdos.csail.mit.edu/6.828/2011/schedule.html) &middot; [Xv6 Teaching OS](http://pdos.csail.mit.edu/6.828/2014/xv6.html) &middot; [OpenCourseware 2006](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-828-operating-system-engineering-fall-2006/), *USA*
+ Stanford U, Advanced OS Topics 2013: [readings](http://www.scs.stanford.edu/13wi-cs240/sched/) &middot; [notes](http://www.scs.stanford.edu/13wi-cs240/notes) &middot; [HiStar Teaching OS](http://www.scs.stanford.edu/histar/), *USA*
+ U of New South Wales, [Advanced OS 2014](http://www.cse.unsw.edu.au/~cs9242/14/lectures/) (Microkernels) &middot; [Lions on UNIX](http://en.wikipedia.org/wiki/Lions%27_Commentary_on_UNIX_6th_Edition,_with_Source_Code), *Australia*

### Language Theory

+ Red Hat, [SE Linux Coloring Book](https://people.redhat.com/duffy/selinux/selinux-coloring-book_A4-Stapled.pdf)
+ U Penn, [CIS 194: Introduction to Haskell 2013](http://www.seas.upenn.edu/~cis194/spring13/lectures.html)
+ [Haskell Meta-Tutorial](http://www.haskell.org/haskellwiki/Meta-tutorial) &middot; [Fast & Hard](https://www.fpcomplete.com/school/to-infinity-and-beyond/pick-of-the-week/haskell-fast-hard)
+ Stephen Diehl, [What I Wish I Knew When Learning Haskell 2.1](http://dev.stephendiehl.com/hask/#cabal)
