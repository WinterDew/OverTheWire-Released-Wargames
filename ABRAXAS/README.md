This wargame was introduced at the Hackito Ergo Sum (HES) 2011 conference in Paris and is centered around the fictitious company dildosfromspace.com

The wargame has its own website with the entire backstory. You can find it here.

As of September 2011, the Abraxas game has been released to the public and can be downloaded here.

The following instructions are also included on the diskimage:

Included file: instructions.txt

---

--- OverTheWire's Abraxas wargame, released September 2011 --- 

1. Introduction

The story around this wargame revolves around a secret agent called Agent 7a69.
This agent was recruited to steal a prototype from the factory of a company called 
Dildo's From Space (DFS). The task, codenamed Job 331, was to be an undercover
operation and Agent 7a69 was to act alone. After several months, Agent 7a69 
disappeared under mysterious circumstances. All he left was his journal on Job 331.

You are a newly-appointed talented secret agent recruited to continue Agent 7a69's
mission. Your mission is the same. It is best that you start with Agent 7a69's logbook
which is located at http://agent7a69.blogspot.com/. God speed!

Note: a full copy of the logbook can also be found in /BackgroundStory.pdf of this diskimage.

2. How to play ?

First, download the diskimage because it is intended to run locally.
Import the diskimage into your favorite virtualization software. The game is based on Ubuntu, 
so any virtual hardware supported by Ubuntu should be fine in your virtualization environment.

When booted, abraxas configures its network interface with:
   IP 192.168.66.66/24
   gateway 192.168.66.254
   DNS server 8.8.8.8 (Google)
There is no need to give access to the internet to get abraxas working.

You can use SSH to login to abraxas. For maintenance reasons, there is an account 'otw' with 
password 'otw' with sudo rights to get a root account. This maintenance account is not part of
the wargame and should not be used when playing the wargame fairly.

Once the game is running, find the logbook mentioned earlier and read it. Instructions on how
to start playing are in there.

3. Contact information

For information regarding this wargame, find us at http://www.overthewire.org or through
IRC on irc.overthewire.org, channel #social
The OverTheWire community offers more wargames and resources for you to explore.

4. History of this wargame

This wargame was reachable on abraxas.labs.overthewire.org and 
abraxas.dildosfromspace.com, which both resolved to the same IP address.
With the release of this diskimage, both DNS records have been updated to 
point to 192.168.66.66, which is the local IP address of this offline version of the game. 
The dildosfromspace.com domainname might no longer exist when you read this.

Originally, this wargame was created for the Hackito Ergo Sum 2011 conference in Paris,
which was held from April 7th to April 9th 2011. Afterwards, the wargame was opened up
to any player.

5. References

http://www.overthewire.org/
http://agent7a69.blogspot.com/
http://hackitoergosum.org/