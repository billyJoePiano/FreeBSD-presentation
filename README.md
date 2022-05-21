# FreeBSD server

Spring 2022 Enterprise Java, Professional Development Presentation

### Presentation Description/Overview

I will be presenting about a development/web server using FreeBSD (a Unix OS similair to Linux but also somewhat different).  The server includes some public-facing services, as well as a number of services only available to me
(SSH and SMB file-sharing) and/or to people on my local network (some beta apps).

I would also like to demonstrate the security aspects of this -- firewall & access-control policies, FreeBSD "jails" (similair to docker containers,
but implemented at the kernel-level), and other security considerations.

### Supporting Materials 

* [Powerpoint Presentation](FreeBSD%20server.pptx)
* [Jails diagram](Jails%20diagram.png) 
* [FreeBSD website](https://www.freebsd.org/)
* [History of Unix, BSD, and FreeBSD (FreeBSD foundation website)](https://freebsdfoundation.org/freebsd/timeline/#:~:text=FreeBSD%20Foundation%20Founded&text=Funding%20comes%20from%20individual%20and,Gibbs%20on%20March%2015%2C%202000.)

### Public-facing websites, hosted on my FreeBSD server
* https://wisconsincheeseclub.com/
* https://068-190-112-250.res.spectrum.com:4444/

### Feedback

[Link to the peer feedback form](Feedback.md)


## Diagram of the "Jails" setup
Note: This can be a little overwhelming at first.  The best place to start is the key in the lower right-hand corner.

![FreeBSD "jails" diagram](Jails%20diagram.png)
