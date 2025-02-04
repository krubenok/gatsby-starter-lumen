---
template: post
title: Enterprise Networking at Home
slug: /posts/meraki-at-home
draft: true
date: 2019-08-03T20:00:00.000Z
description: >-
  A frequent conversation that happens when people come into my apartment
  shortly after they walk in: "What is THAT!?" as they point at my server rack
  in the corner of my living room. I intent to cover what the rest of my homelab
  does and why I adore tinkering with it in a later post but I wanted to start
  with the piece of enterprise hardware that I got started with first: the
  networking.
category: Networking
tags:
  - Meraki
  - Networking
  - Homelab
---
A frequent conversation that happens when people come into my apartment shortly after they walk in: "*What is THAT!?"* as they point at my server rack in the corner of my living room. I intent to cover what the rest of my homelab does and why I adore tinkering with it in a later post but I wanted to start with the piece of enterprise hardware that I got started with first: the networking. 

# Enter: Meraki.

When I was still an IT assistant at my high school in the 11th grade or so, they were shopping around to vendors for a new WiFi system. Cisco, Aruba, Aerohive, Rukus and this little startup Meraki all brought their offerings for evaluation and testing over the course of 6 months. At the end of the day, they ended up deploying an Aruba 802.11n solution but there was a leftover Meraki MR18 demo device with a 3 year license that was never claimed. I brought it home and discovered the joys of leaving consumer grade WiFi behind and I had to get more of it. 

Shortly after I discovered meraki, thy were acquired by Cisco for 1.2 Billion dollars. At the time I didn't much know that Cisco was a titan of the networking industry but I did recognize the brand from cable boxes (LOL Scientific Atlanta Acquisition) and some mediocre Linksys routers (LOL). 

# Cloud Managed Networking

The whole concept of Meraki is that your network is managed in the cloud. When I was first getting started in networking, having a single pane of glass in the cloud where I could experiment with the settings in any easy was was critical to how I learned the technology. My first summer internship at Cisco in 2016 was an eye opener to the traditional way this stuff is configured with CLI's to every device but I still firmly believe that Meraki's cloud controller model is the future. 

This remote management also let me deploy a Meraki full stack network at my Mom's house allowing me to reduce the number of family tech support calls I get while ensuring that the firmware is automatically up to date and have a site-to-site VPN bridge to allow remote access to my media collection.

# Overkill

Yes. Meraki at home is totally overkill but I wouldn't have it any other way. Proper mesh networking that scales well is still very hit or miss in the consumer space and having roaming that actually works is a luxury I can't live without. Finally, the site-to-site and client VPN are huge features that I use on a daily basis while knowing that my network is backed up Cisco Talos security via AMP.

At some point later I'll get into details as to what my network is running with a diagram as well as the configurations...
