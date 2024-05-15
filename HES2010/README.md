This wargame was introduced at the Hackito Ergo Sum (HES) 2010 conference in Paris and is centered around the fictitious company dirty-underwear.com

The winners of this wargame at HES2010 were CCCP and morla.

As of January 2012, the HES2010 game has been released to the public and can be downloaded here.

The wargame has its own local website on the virtual machine. Once the VM is running, you can find it at http://192.168.66.66

The following instructions are also included on the diskimage:

Included file: instructions.txt

---

--- OverTheWire's HES2010 wargame, released January 2012 --- 

1. Introduction

This wargame revolves around a company called Dirty-Underwear.com which buys and sells dirty 
underwear. Your job, very simply, is to break into the server and beat all levels.
Hint: the credentials for the first level can be found by going through the local 
website. Think like Google!

2. How to play ?

First, download the diskimage because it is intended to run locally.
Import the diskimage into your favorite virtualization software. The game is based on Ubuntu, 
so any virtual hardware supported by Ubuntu should be fine in your virtualization environment.

When booted, the VM configures its network interface with:
   IP 192.168.66.66/24
   gateway 192.168.66.254
   DNS server 8.8.8.8 (Google)
There is no need to give access to the internet to get this VM working.

You can use SSH to login to the VM. For maintenance reasons, there is an account 'otw' with 
password 'otw' with sudo rights to get a root account. This maintenance account is not part of
the wargame and should not be used when playing the wargame fairly.
 
3. Contact information

For information regarding this wargame, find us at http://www.overthewire.org or through
IRC on irc.overthewire.org, channel #social
The OverTheWire community offers more wargames and resources for you to explore.

4. History of this wargame

This wargame was reachable on hes2010.labs.overthewire.org.
With the release of this diskimage, the DNS record has been updated to 
point to 192.168.66.66, which is the local IP address of this offline version of the game. 

Originally, this wargame was created for the Hackito Ergo Sum 2010 conference in Paris,
which was held in April of 2010. Afterwards, the wargame was opened up to any player.

5. References

http://www.overthewire.org/
http://hackitoergosum.org/