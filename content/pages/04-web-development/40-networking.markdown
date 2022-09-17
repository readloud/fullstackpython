title: Networking
category: page
slug: networking
sortorder: 0440
toc: False
sidebartitle: Networking
meta: Understanding computer networking is critical to building reliable, performant Python web applications.


Computing networking is critical to building reliable, performant Python
web applications.



### Resources about networking
The "Let's code a TCP/IP stack" series along with its 
[open source code](https://github.com/saminiir/level-ip) gives a ton of 
context on how TCP/IP works while providing the code for implementing the 
foundational pieces. You will likely need to pair this with a more theoretical
reference tutorial such as [RFC 1180](https://tools.ietf.org/html/rfc1180)
to have a more complete understanding of the protocol:

1. [Ethernet & ARP](http://www.saminiir.com/lets-code-tcp-ip-stack-1-ethernet-arp/)
1. [IPv4 & ICMPv4](http://www.saminiir.com/lets-code-tcp-ip-stack-2-ipv4-icmpv4/)
1. [TCP Basics & Handshake](http://www.saminiir.com/lets-code-tcp-ip-stack-3-tcp-handshake/)
1. [TCP Data Flow & Socket API](http://www.saminiir.com/lets-code-tcp-ip-stack-4-tcp-data-flow-socket-api/)
1. [TCP Retransmission](http://www.saminiir.com/lets-code-tcp-ip-stack-5-tcp-retransmission/)

* [Monitoring and Tuning the Linux Networking Stack: Receiving Data](https://blog.packagecloud.io/eng/2016/06/22/monitoring-tuning-linux-networking-stack-receiving-data/)
  along with 
  [Monitoring and Tuning the Linux Networking Stack: Sending Data](https://blog.packagecloud.io/eng/2017/02/06/monitoring-tuning-linux-networking-stack-sending-data/)
  are incredibly detailed technical posts on the networking layer within
  Linux operating systems.

* [Computer networking](http://cnp3book.info.ucl.ac.be/) is a free book
  that explains how networking between computer systems works. There are
  also exercises for testing what you learned along the way.

* [What's the history behind 192.168.1.1? Why not 192.169.1.1 or any other IP address? When did it start being used? Who started it? Why? Why not 1.1.1.1? What is the relation to 127.0.0.1? What about 10.0.0.1 (Apple)?](https://www.quora.com/Whats-the-history-behind-192-168-1-1-Why-not-192-169-1-1-or-any-other-IP-address-When-did-it-start-being-used-Who-started-it-Why-Why-not-1-1-1-1-What-is-the-relation-to-127-0-0-1-What-about-10-0-0-1-Apple)
  is a nice answer on the history of IPv4 addressing and why various
  IP addresses such as 192.168.1.1 became standards for localhost or
  other local networking. 

* [We built network isolation for 1,500 services to make Monzo more secure](https://monzo.com/blog/we-built-network-isolation-for-1-500-services)
  provides the thinking, processes and data analysis behind how one
  team took a complex environment, separated the dependencies and
  was able to improve their network. It's a great case study-style
  article that has more detail than a lot of similar operations posts.

* [Dropbox traffic infrastructure: Edge network](https://blogs.dropbox.com/tech/2018/10/dropbox-traffic-infrastructure-edge-network/)
  explains how Dropbox uses edge-of-the-network resources closer to the
  end user to optimize performance of their service.

* [On the shoulders of giants: recent changes in Internet traffic](https://blog.cloudflare.com/on-the-shoulders-of-giants-recent-changes-in-internet-traffic/)
   examines how the COVID-19 pandemic of 2020 changed the times during the
   day and locations of how the majority of internet traffic was routed
   and consumed.
