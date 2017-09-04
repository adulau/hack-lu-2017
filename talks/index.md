---
layout: page
title: Talks at Hack.lu 2017
excerpt: "Talks at Hack.lu 2017"
modified: 2017-03-14T19:44:38.564948-04:00
image:
  feature: talks-s.jpg
  credit: Alexandre Dulaunoy
  creditlink: https://www.flickr.com/photos/adulau/5129843510
---

Talks, workshops and presentations will be published after the [Call for Papers]({{ site.url }}/blog/Call-for-Papers/). Feel free to submit your presentations or researches to be part of the 2017 edition.

Keynotes
========

Queer Privacy & Building Consensual Systems
-------------------------------------------
by Sarah Jamie Lewis

This is a talk about privacy. Unlike many talks on privacy we won't get into state surveillance, PGP or anonymous browsing.

Instead, I'm going to tell you stories. These stories belong to real people. People trying to live their lives, find love, find comfort and
find happiness in a world that, at best, pretends they don't exist, and at worst, punishes them for existing.

These stories are from people who need privacy and security, but who are failed by our current tool, systems and communities.

Not all of these stories have happy endings, but each one shines a light that can show us how to build tools, systems and communities that
are more useful, more inclusive and safer for those who are marginalized by society.

Bio: Sarah Jamie Lewis
----------------------

Sarah Jamie Lewis is an independent security researcher currently living in Vancouver Canada. She has a passion for privacy & anonymity
and runs Mascherari Press, an organization dedicated to conducting & promoting privacy research aimed at empowering marginalized & at risk
communities.

Infosec and failure
-------------------
by 杏👼Ąż

The speaker failed to give a proper abstract (as usual).

Bio: 杏👼Ąż
----------------------------

Reverse engineer - author of [Corkami.com](corkami.com). [Github](https://github.com/corkami)

Information Flows and Leaks in Social Media
-------------------------------------------
by Vladimir Kropotov and Fyodor Yarochkin

Covfefe or not covfefe? The social network is a very powerful tool of
influence in modern world. Is your opinion really yours? With this
presentation we examine a number of social events and the impact they
had on social media platforms. We try to understand the dynamics of
information dissemination through a social network and demonstrate how
these networks are frequently abused by all sorts of malfactors to
pursue an agenda of their interest. Our findings are presented in form
of several case studies where we walk through series of major events
and analyze how these events were played online. Different regional
groups, different linguistic groups: the behavior on social media
could be a pre-requisite of activity in kinetic world. Known campaigns
of character assassination online were in some cases followed by
physical extermination or attacks on the objects of attention. We
examine such behaviours in different national context: Latin America,
Russia, China, Ukraine and the Middle East and demonstrate the
affiliation of these activities with other Black Market commodities
and services. Further, we discuss how these services could be abused to
have a major impact in physical world.

Bio: Vladimir Kropotov
----------------------

Vladimir is researcher with Trend Micro FTR team. Active for over 15 years in information security projects and research, he previously built and led incident response teams at some of Fortune 500 companies, was head of Incident Response Team at Positive Technologies since 2014, and holds a masters degree in applied mathematics and information security. He participates in various projects for leading financial, industrial, and telecom companies. His main interests lie in network traffic analysis, incident response, botnet and cybercrime investigations. Vladimir regularly appears at high-profile international conferences such as FIRST, CARO, HITB, Hack.lu, PHDays, ZeroNights, POC, Hitcon, and many others.

Bio: Fyodor Yarochkin
---------------------

Fyodor is a researcher with TrendMicro Taiwan as well as a Ph.D.
candidate at EE, National Taiwan University. An early Snort developer,
and open source evangelist as well as a "happy" programmer. Prior to
that, Fyodor professional experience includes several years as a
threat analyst at Armorize and over eight years as an information
security analyst responding to network, security breaches and
conducting remote network security assessments and network intrusion
tests for the majority of regional banking, finance, semiconductor and
telecommunication organisations. Fyodor is an active member of local
security community and has spoken at a number of conferences
regionally and globally.

Talks
=====

On Strategy
-----------
by Eleanor Saitta

How should small development teams think about security?

Dedicated security hires often come fairly late in a startup's life. As a consultant,
I often see teams of up to fifty engineers with no security staff.
Even if they're motivated to build secure systems and consider security a collective responsibility,
their understanding often doesn't go much beyond patching boxes and one-off fixes for basic,
OWASP-level issues.  Even larger organizations in the 300-400 engineer range often don't have
a unified security strategy to coordinate the what security staff they do have.
Lack of understanding, strategy, and coordination yields poor execution.

In this talk, I'll go over my toolkit for working with development teams
who are ready to get serious about security.  Whether you're an
engineering director trying to figure out where to turn, the first
security hire at a startup, or a consultant looking at it from the other
side, this should help you see where to start.  We'll cover:

* Why you want to start with some technical work but not too much
* How to teach teams to see security in a way that enables them to manage it as a whole-systems outcome
* The scope of work teams should be looking at
* How to think about risk and cost usefully
* The relationship security should have with the rest of the organization and the business
* How to deal with security compliance and still be secure
* How to plan for security staffing and when to work with consultants

Bio: Eleanor Saitta - @dymaxion
-------------------------------

Eleanor Saitta is an independent security architecture and strategy
consultant with media, finance, healthcare, infrastructure, and software
clients across the US and Europe.  She was previously the security
architect for Etsy.com, and has worked for a number of commercial
consultancies (Bishop Fox, IOACtive, and others) over the past fifteen
years.  Her work has encompassed everything from core security
engineering and architecture work for Fortune 50 software firms to
cross-domain security for news organizations and NGOs targetted by
nation states.  Her focus is on the ways task and experience design,
system architecture, development process change, and operational changes
can shift the balance of power between adversaries to bring better
outcomes to users.

Saitta is a co-founder and developer for [Trike](http://octotrike.org/),
an open source threat modeling methodology and tool which partially
automates the art of security analysis and has contributed to the [Briar](https://briarproject.org) and
[Mailpile](https://mailpile.is) secure messaging projects.  She's on the advisory boards of the
[Freedom of the Press Foundation](https://pressfreedomfoundation.org), the
[International Modern Media Institute](https://immi.is), and the [Calyx Institute](https://calyxinstitute.org),
all organizations that look at freedom in the media and security online.  Saitta is a regular speaker at industry
conferences; past venues include O'Reilly Velocity, KiwiCon, ToorCon,
CCC, Hack in The Box, and HOPE, among others.  You can find her on
twitter as [@dymaxion](https://twitter.com/dymaxion), and at [https://dymaxion.org](https://dymaxion.org)

Intel AMT: Using & Abusing the Ghost in the Machine
---------------------------------------------------
by Parth Shukla

<!-- 45min + questions -->

Come see how Intel AMT can be used to completely own a modern machine permanently
and without detection.

In the first half of the talk, we’ll see how an attacker can abuse the legitimate
functionalities of Intel AMT to gain long term persistent access with little to no
chance of detection. The demoed attack can be executed to take ownership of AMT in
less than 60 seconds - either through supply chain or temporary physical access.
We will then show how AMT can be used for persistent access to the machine via
readily available and easy-to-use C&C tools. Finally, we will cover possible mitigations
and preventions against such attacks.

In the second half of the talk, we will walk through the process of doing non-destructive
forensics on an Intel AMT to which we don’t know the admin password (i.e. potentially
attacker controlled!). We will also describe how to reclaim ownership of the AMT once
forensics is complete. Finally, we will be releasing the Linux tooling we developed in
order to facilitate AMT forensics.

*What is Intel AMT?*

Intel AMT is an out-of-band, always-on management technology, embedded into Intel
chipsets supporting vPro technology, intended to allow remote management of equipment
without the need for a functioning OS. Intel AMT is commonly available on all Intel-based
business laptops & desktops as well as many high end consumer laptops & desktops.

Bio: Parth Shukla
-----------------

Parth Shukla is a Security Engineer and member of Google's Infrastructure Protection team.
He works on efforts related to improving firmware integrity, verification and transparency.

Prior to Google, Parth was an Information Security Analyst at the Australian Computer
Emergency Response Team (AusCERT). While at AusCERT, Parth analysed the non-public
data of the Carna Botnet that he obtained exclusively from the anonymous researcher
of Internet Census 2012. Parth released a [white paper on this analysis](https://bit.ly/carna-paper)
and presented on it at various conferences, including: DeepSec 2013 in Vienna, Austria;
Blackhat Sao Paulo 2013 in Sao Paulo, Brazil; APNIC 36 in Xi’an, China and AusCERT 2013 in Gold Coast, Australia.

Countering Security Threats by Sharing Information: Emerging Civil Society Practices
------------------------------------------------------------------------------------
by Becky Kazansky

What role does threat information sharing play in the safety and security of civil
society organizations? This talk takes the audience through a case study on information
sharing practices based on interviews with 20 human rights defenders dealing with a set of
serious digital and physical security threats.

The case study presented in this talk explains how a network of civil society organizations
focused on advancing women’s rights in a politically volatile context built up their security
infrastructure by starting to share information about threats with their network of allies. The
talk will walk the audience through how the network of human rights defenders began to build trust
and log security incidents, and to eventually spot patterns that allowed them to put effective security
countermeasures into place.

Controversially, this network of human rights defenders relied on Facebook as their
platform for information sharing about threats, a fact which brings up many important
questions about the merits and pitfalls of using commercial platforms, effective threat modeling,
and generally, what it takes to get people to move to more secure modes of information management.
This talk will show that sharing information about threats strengthened the work of this human rights
network even as it exposed them to further dangers, and came at great cost in terms of time and resources.
What lessons can be gleaned from their experience?

This talk aims to offer rich insights into how ’real-world’ security practices play out in
organizational contexts, as made possible through the kind of ‘longitudinal’, ethnographic study
done by the speaker. The case study is based on interviews, observations, and discussions taking
place around the context of a digital security workshop conducted by the speaker two years ago,
while working together with the Tactical Technology Collective. It is the hope of the speaker
that highlighting the actual practices of people with ‘real-world’ constraints can offer the
security community a chance to think about how to create systems and infrastructures that
build on existing practices rather than providing ill-fitting add-ons.

Bio: Becky Kazansky
-------------------

Becky Kazansky is a PhD candidate and lecturer at the University of Amsterdam,
studying the development of new security infrastructures across transnational civil
society networks. In the past 10 years, she has worked with a number of different civil
society organizations on digital security research and capacity building, previously the
Lead Programme Researcher at Tactical Technology Collective.

Digital Vengeance: Exploiting Notorious C&C Toolkits
----------------------------------------------------
by Waylon Grange

Every year thousands of organizations are compromised by targeted attacks.
In many cases, the attacks are labeled as advanced and persistent which suggests a
high level of sophistication in the attack and tools used. Many times, this title is
leveraged as an excuse that the events were inevitable or irresistible as if the assailants’
skill set is well beyond what defenders are capable of. To the contrary, often these assailants
are not as untouchable as many would believe.

If one looks at the many APT reports that have been released over the years some clear
patterns start to emerge. A small number of Remote Administration Tools are preferred by
actors and reused across multiple campaigns. Frequently sited tools include Gh0st RAT, Plug-X, and
XtremeRAT among others. Upon examination, the command and control components of these notorious RATs
are riddled with vulnerabilities. Vulnerabilities that can be exploited to turn the tables from hunter to hunted.

Although the material in this talk will provide tools for launching an offensive against
attackers this talk is not intended to be instructional for hacking back. The ethics and
legality of counter attacks will be touched on only briefly as that is a discussion beyond the
scope of this talk.

The presentation will disclose several exploits that could allow remote execution or remote
information disclosure on computers running these well-known C&C components. It should serve as a
warning to those actors who utilize such tool sets. That is to say, such actors live in glass houses and
should stop throwing stones.

Bio Waylon Grange
-----------------

Waylon Grange is an experienced reverse engineer, developer, and digital forensics examiner.
He holds a graduate degree in Information Security from Johns Hopkins University, and has worked
numerous computer incident investigations spanning the globe. He currently works as a Senior Threat
Researcher for Symantec and previously worked for the Department of Defense performing vulnerability
research, software development, and Computer Network Operations.

Keynterceptor: Press any key to continue
----------------------------------------
by Niels van Dijkhuizen

The past decade has taught us that there are quite some attacks vectors on USB.
These vary from hardware key-logging to driver fuzzing and from power surge i
njection to network traffic re-routing. In addition to addressing these issues, the
security community has also tried to fix some of these. Several defensive hard- and software
tools focus on a particular piece of the puzzle. However none, is able to completely mitigate the
risks that involves the everyday use of USB in our lives.

Key stroke injectors like Rubber Ducky and MalDuino have a big disadvantage: they are not very stealthy. When no protection
is in place, there is a big change the end-user will notice something fishy is going on. Proper
USB Class filtering policies and a daemon that monitors typing speed will put this kind of
attacks to a halt. To bypass both the user's attention and current security mechanisms, I have
developed Keynterceptor. This is a proof of concept keyboard implant that is able to capture and
inject keystrokes and communicate over the air via a back-channel while keeping the local time.

Since Keynterceptor is made up from very affordable, off-the-shelf electronic parts, it is
likely that such an attack tool can be created and used by someone with few resources.

I will demonstrate the effectiveness of Keynterceptor in a real-world scenario where an end-point gets compromised.

Bio: Niels van Dijkhuizen
-------------------------

Niels is a lead analyst at the CSIRT of a large organization in the
Netherlands. He is a profound advocate of open standards and open-source
software and conducts information security research in his spare time.
Niels previously built monitoring and incident handling teams and
performed network intrusion tests at current and previous jobs. He holds a
bachelor’s degree in embedded systems and a master’s degree in computer
science. His main interests lie in anomaly detection, hardware hacking and
traffic anonymisation.

A view into ALPC-RPC
--------------------
by Clement Rouault and Thomas Imbert


The Advanced Local Procedure Call (ALPC) is an Inter-Process Communication method widely used in recent Windows version.
One important application of the ALPC is to perform Remote Procedure Call (RPC) on the local computer.
Whereas ALPC have been scrutinized by security researcher in the last few years, its usage in the MS-RPC have been less documented.

This presentation will explain what are the core structures & API of ALPC then explore how RPC-over-ALPC works.
Furthermore we will describe how we searched for vulnerabilities using a full-Python implementation of a simple RPC client soon to be released.
Lastly, an UAC bypass and a Local Privilege Escalation found during our research will be presented.


Bio: Clement Rouault - @hakril
------------------------------

Clement Rouault is a security researcher currently working at Sogeti ESEC R&D.
Fervent user of Python he is interested in use, abuse and implementation of this language.
His research interests include reverse engineering, exploitation and windows internals.

Bio: Thomas Imbert - @masthoon
------------------------------

Thomas Imbert works at Sogeti ESEC R&D as a security researcher.
His interests are focused on reverse engineering, virtualization, forensics, vulnerability research and exploitation.
On his free time, he likes to participate to security competitions with the khack40 team.

How I’ve Broken Every Threat Intel Platform I’ve Ever Had (And Settled on MISP)
-------------------------------------------------------------------------------
by John Bambenek

Almost every major enterprise has the same problem, how to categorize, store, and operationalize the
various sources of intelligence (internal and external) so that they can be useful. The way we categorize
information and operationalize information, however, has led to design flaws of almost every intel
platform out there. IP address lists are good for plugging into firewalls, but they don’t appear
organically in the absence of other critical information like hostnames, file names, TLS certificates, and so on.

To perform proper intelligence, all of these items need to be correlated into common events so
discrete data points can be mapped to larger events and to overall patterns and campaigns against
an organization.

This talk covers the adventures of working with various platforms to store a large malware
configuration database so that it can retain its usefulness to users to correlate attacks
back to specific actors. This malware configuration database (called Barncat) ultimately
sits on MISP after attempting other platforms that failed to work for this use case. The
intent of this talk is to shift the paradigm from indicators to events as the starting
element to begin threat intelligence work as the relationship of all the observables of an
attack are important to retain, analyze, and correlate.

Bio: John Bambenek
------------------

John Bambenek is Manager of Threat Systems at Fidelis Cybersecurity and an incident
handler with the Internet Storm Center. He has been engaged in security for 18 years
researching security threats. He is a published author of several articles, book chapters and
one book. He has contributed to IT security courses and certification exams covering such subjects as
penetration testing, reverse engineering malware, forensics, and network security. He has participated in
many incident investigations spanning the globe including the DNC breach and other election related
cybersecurity incidents affecting both parties. He also produces several large intelligence datasets
based on DGAs and malware configurations that are given away for free. He speaks at conferences around the
world and runs several private intelligence groups focusing on takedowns and disruption of criminal entities.

Let’s Play with WinDBG & .NET
-----------------------------
by Paul Rascagneres

.NET is an increasingly important component of the Microsoft ecosystem providing a
shared framework. Many Microsoft tools, such as PowerShell, rely on the .NET platform for
their functionality. Obviously, this makes .NET an enticing language for malware developers too.
Hence, malware researchers must also be familiar with the language and have the necessary skills to
analyse malicious software that runs on the platform. During the presentation, I will explain how to
automate .NET analysis with WinDBG the Microsoft debugger. To illustrate my talk, I will show how to
analyse PowerShell scripts with WinDBG and how to automatically unpack a .NET packer family discovered
recently. The presentation includes several live demo on WinDBG usage in this specific context.

Bio: Paul Rascagneres
---------------------

Paul is a security researcher within Talos, Cisco’s threat intelligence and research
organization. As a researcher, he performs investigations to identify new threats and
presents his findings as publications and at international security conferences throughout
the world. He has been involved in security research for 7 years, mainly focusing on malware
analysis, malware hunting and more specially on Advanced Persistence Threat campaigns and rootkit
capabilities. He previously worked for several incident response team within the private and public sectors.

Sigma - Generic Signatures for Log Events
-----------------------------------------
by Thomas Patzke

Log files are a great resource for hunting threats and analysis of incidents. Unfortunately,
there is no standardized signature format like YARA for files or Snort signatures for
network traffic. This makes sharing of log signatures by security researchers and software
developers problematic. Further, most SIEM systems have their own query language,
which makes signature distribution in large heterogeneous environments inefficient
and increases costs for replacement of SIEM solutions.

Sigma tries to fill these gaps by providing a YAML-based format for log signatures,
an open repository of signatures and an extensible tool that converts Sigma signatures
into different query languages. Rules and tools were released as open source and are
actively developed. This presentation gives an overview about use cases, Sigma rules
and the conversion tool, the development community and future plans of the project.

Bio: Thomas Patzke
------------------

Thomas Patzke has more than 10 years of experience in the area of information security
and currently works at thyssenkrupp CERT. His main job is the discovery of vulnerabilities in
applications and products, but he also enjoys working on defensive topics, especially
in the area of threat hunting. Thomas likes to create and contribute to open source
security tools like Sigma, EQUEL, an ELK configuration for Linux systems, a POODLE
exploit and various plugins for the Burp Suite (github.com/thomaspatzke).

He does not have a single certification and is quite proud of it.

Malicious use of Microsoft "Local Administrator Password Solution"
------------------------------------------------------------------
by Maxime Clementz & Antoine Goichot

<!-- Tuesday or Wednesday-->

"Local Administrator Password Solution", known as LAPS, provides management of
local account passwords of domain joined computers. Passwords are stored in Active
Directory (AD) and protected by ACL, so only eligible users can read it or request its reset.

We started some security research on this solution and managed to get illegitimate
access to local administrator credentials (and to control the generation of a new
administrator password) in a post-exploitation scenario (to maintain presence on a
compromised computer). Moreover, depending on the method used to deploy LAPS, we also
elaborated a privilege escalation scenario.

Both scenarios will be demonstrated on stage, we will explain the inner working of
LAPS and our exchanges with the Microsoft Security Response Center.

Bio: Maxime Clementz & Antoine Goichot
--------------------------------------

Maxime [@maxime_tz](https://twitter.com/maxime_tz) and Antoine [@AntoineGoichot](https://twitter.com/AntoineGoichot)
joined the Cyber Security Advisory team at PwC Luxembourg in 2012 and 2015, respectively.
Their favourite assignments are penetration tests and information security advisory. When
they have the occasion to perform vulnerability research or Security R&D, they are always
delighted to present their results (Hack.lu 2012, 2015 and now 2017!).

Device sensors meet the web - a story of sadness and regret
-----------------------------------------------------------
by Lukasz Olejnik

The web is becoming increasingly rich in features as more powerful APIs are introduced and
implemented by browsers. Among the new features are communication channels such as Web
Bluetooth as well as access to device sensors (light, proximity, magnetic field, etc.)
allowing access to information about users and their surroundings. New web features offer
increased functionality and novel use patterns, but also increase the risk of abuses. In this
talk we will discuss and demonstrate the privacy risks associated with exposing sensors to the
web and how sensors could be abused by malicious websites. We’ll show the risk of abusing of
seemingly innocuous sensor information; we’ll describe how Battery Status API enabled tracking and
information leaks, and show how to steal web browsing history using the ambient light sensor. At the
end we will take a step back and highlight the need to consider security and privacy during the
drafting of new standards, as well as discuss how to improve the big picture for web users.

Bio Lukasz Olejnik
------------------

TODO
