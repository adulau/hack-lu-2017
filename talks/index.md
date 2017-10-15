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

Reverse engineer - author of [Corkami.com](http://www.corkami.com), [Github](https://github.com/corkami).

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
cross-domain security for news organizations and NGOs targeted by
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
These vary from hardware key-logging to driver fuzzing and from power surge
injection to network traffic re-routing. In addition to addressing these issues, the
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

<!-- talk the 17th, 40 min -->

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

Bio: Lukasz Olejnik - @lukOlejnik
---------------------------------

Lukasz Olejnik is a security and privacy researcher and advisor. He specializes in web security and
privacy, privacy engineering, privacy reviews and privacy impact assessments. He has industry,
research and technology policy experience, and he contributes to privacy reviews of web standards as a W3C Invited Expert.

Lukasz completed his Ph.D. at INRIA (Grenoble, France).He worked at Poznan Supercomputing and
Networking Center, CERN and University College London. His interests include information, computer
security and privacy, especially web, mobile and Internet of Things and Web of Things security and privacy.
He has experience in privacy reviews and privacy impact assessments and he helps organizations with their
privacy strategy. He is working on the ePrivacy regulation at the European Parliament as a technology policy advisor.

He can also be found on [his site](https://lukaszolejnik.com).

The Bicho: An Advanced Car Backdoor Maker
-----------------------------------------
by Sheila Ayelen Berta and Claudio Caracciolo

<!-- Talk the 17th -->

Attacks targeting connected cars have already been presented in several conferences,
as well as different tools to spy on CAN buses. However, there have been only a few
attempts to create something similar to a useful backdoor for the CAN bus. Moreover,
some of those proofs of concept were built upon Bluetooth technology, limiting the attack
range and therefore tampering its effects.

Those things are old! Throughout our research we have successfully developed a hardware
backdoor for the CAN bus, called "The Bicho". Its powerful capabilities render it a very smart
backdoor. Have you ever imagined the possibility of your car being automatically attacked based on its
GPS coordinates, its current speed or any other set of parameters? The Bicho makes it all possible.

All the "magic" is in the assembler-coded firmware we developed for a PIC18F2685 microcontroller.
Additionally our hardware backdoor has an intuitive graphical interface, called "Car Backdoor Maker",
which is open-sourced and allows payload customization. The Bicho supports multiple attack payloads and
it can be used against any vehicle that supports CAN, without limitations regarding manufacturer or model.
Each one of the payloads is associated to a command that can be delivered via SMS, allowing remote execution
from any geographical point.

Furthermore, as an advanced feature, the attack payload can be configured to be automatically
executed once the victim's vehicle is proximate to a given GPS location. The execution can also be
triggered by detecting the transmission of a particular CAN frame, which can be associated with the
speed of the vehicle, its fuel level, and some other factors, providing the means to design highly
sophisticated attacks and execute them remotely.

Bio: Sheila Ayelen Berta - @UnaPibaGeek
---------------------------------------

Sheila A. Berta is an Information Security Specialist and Developer, who has begun at 12 years
old by herself. At the age of 15, she wrote hers first book about Web Hacking, published by
RedUSERS Editorial at different countries. Over the years, Sheila has discovered several
vulnerabilities in popular web applications such as Facebook, LinkedIN, Hotmail, ImageShack and others.

Actually, Sheila works at Eleven Paths as Security Researcher which is specialized in web
application security, malware analysis and exploit writing. She is also a developer in ASM x86,
AutoIT, C/C++, Python and the most popular web application technologies. Additionally, Sheila is
Security Researcher at UdeMM University, where she works leading  projects about technology and cybersecurity.

Sheila is an International Speaker, who has spoken about different researches at important
security conferences such as Black Hat USA 2017 & EU 2016 Arsenal, DefCon 25 CHV, Ekoparty
Security Conference, OWASP Latam Tour, APPSEC Latam, DragonJARCon and others.

Bio: Claudio Caracciolo - @holesec
----------------------------------

- Actual Chief Security Ambassador at Eleven Paths.
- Local chapter coordinator at Centro de Ciberseguridad Industrial of Argentina (a Centro de
  Ciberseguridad Industrial de España Subsidiary - CCI-Es.org)
- Former President at ISSA Argentina (through periods 2011-2013 and 2013-2015)
- Information Security specialist consultant - Professor of "Computer Forensics" and "Information Security"
  classes at Instituto Superior de Seguridad Pública (ISSP)
- Active member of several information security associations such as: ISSA International, OWASP, Usuaria, Argentina Cibersegura
- Member of Segurinfo's academic committee from 2007 to date
- Guest speaker at several international information security conferences and events such Black Hat USA 2017 Arsenal,
  DefCon 25 CHV, Ekoparty Security Conference and others.
- Instructor on Ethical Hacking related issues such as: Defense Methodologies, Platform Hardening, Web Security, and
  Anti-Forensic Techniques.
- Social Engineering Passionate.
- Co-author of "Ethical Hacking, un enfoque metodológico" (Editorial Alfaomega - 2010).
- Co-organizer of MS Doing Blue event.

Are your VoLTE and VoWiFi calls secure?
---------------------------------------
by Sreepriya Chalakkal

Voice over LTE (VoLTE) as well as Voice over WiFi (VoWiFi) are variants of Voice over IP
that makes use of IP Multimedia Subsystem (IMS) in its backend. In this talk, we identify
five different attacks on VoLTE/VoWiFi.

This includes mainly (i)sniffing VoLTE/VoWiFi interfaces, (ii)extracting IPSec keys from IP
Multimedia Services Identity Module (ISIM) that is embedded within the SIM card, and (iii)performing
three different kinds of injection attacks in Session Initiation Protocol (SIP) headers that are used for
signaling of VoLTE/VoWiFi. As a result of VoLTE/VoWiFi sniffing, we identified information disclosures
such as leaking IMSI, IMEI, location of users and private IP of IMS.

We also managed to extract the ciphering key and the integrity key (CK/IK) used for IPSec from
ISIM with the help of a hardware device called SIMTrace.

We also discuss three different SIP header injection attacks that enables location
manipulation and side channel attacks.

It is important to note here that all these attacks are valid on the current 3GPP standards
that are used by telecom providers. Thus understanding the attacks and mitigating them is of high relevance.

This is a continuation of the work presented by Schmidt et.al in the talk IMSecure –
Attacking VoLTE at Areas41 conference, 2016. There is also a [reference paper for more information](https://www.ernw.de/download/newsletter/ERNW_Whitepaper_60_Practical_Attacks_On_VoLTE_And_VoWiFi_v1.0.pdf)

Bio: Sreepriya Chalakkal
------------------------

Sreepriya works at ERNW GmbH as a security researcher focused on telecommunication security.

These days, she spends her time playing with telecommunication devices and SIM cards. Sreepriya
likes to do security analysis of large code bases, packet captures and logs. She completed her
masters from Technical University of Berlin and University of Trento with a dual degree in Computer
Security and Privacy in March 2017. She is inspired by the mission "Making the world a safer place" and
loves to work towards fulfilling that goal.

Snuffleupagus - Killing bugclasses in PHP 7, virtual-patching the rest
---------------------------------------------------------------------
by Sébastien (blotus) Blot, Thibault (buixor) Koechlin & Julien (jvoisin) Voisin

Suhosin is a great PHP module, but unfortunately, it's getting old, new ways have been found
to compromise PHP applications, and some aren't working anymore; and it doesn't play well with the
shiny new PHP 7. As a secure web-hosting company, we needed a reliable and future-proof
solution to address the flow of new vulnerabilities that are published every day.
This is why we developed Snuffleupagus, a new (and open-source!) PHP security module, that
provides several features that we needed: passively killing several PHP-specific bug classes,
but also implementing virtual-patching at the PHP level, allowing to patch vulnerabilities
in a precise, false-positive-free, ultra-low overhead way, without even touching the applications' code.

Bio: Sébastien (blotus) Blot, Thibault (buixor) Koechlin, Julien (jvoisin) Voisin
---------------------------------------------------------------------------------

- Sébastien (blotus) Blot is a pretty cool guy.
- Thibault (bui) Koechlin used to write exploits for fun, he's now CISO at NBS System,
  writing the naxsi WAF to prevent web pwning.
- Julien (jvoisin) Voisin used to pwn and reverse stuff while contributing to radare2,
  he nowadays focus on protecting web stuff while keeping his own bug alive on websec.fr
  and writing stuff on dustri.org. He's also running some high-speed Tor relay.


SMT Solvers in the IT Security - deobfuscating binary code with logic
---------------------------------------------------------------------
by Thaís Moreira Hamasaki

<!-- Not thursday afternoon -->


Malware is sneaky. Malicious codes are implemented to stay hidden during the infection and
operation, preventing their removal and the analysis of the code. Most samples employ some sort of
packing or obfuscation techniques in order to thwart analysis. Similar techniques are also used to
protect digital assets from intellectual property theft.

Analysis tools help getting new insights that can be used to secure software and hardware by
identifying vulnerabilities and issues before they cause harm downstream. Tools and techniques
beyond standard debuggers can enhance analysts capabilities with better adaptability and automation.

This talk will give you a small taste on some practical applications of SMT solvers in IT security,
investigating the theoretical limitations and practical solutions, focusing on their use as a tool for
binary static analysis and code deobfuscation.


Bio: Thaís Moreira Hamasaki - @barbieauglend
--------------------------------------------

Thaís Moreira Hamasaki is an independent malware researcher focussing on static analysis, reverse
engineering and logical programming. Thaís started her career within the anti-virus industry
working on data and malware analysis, where she developed her knowledge on threat protection systems.
She won the "best rookie speaker" award from BSides London for her first talk about "Using SMT solvers to
deobfuscate malware binaries". Recent research topics include malware binary code deobfuscation, generic
unpacking and malware analysis automation. She is an active member of the Düsseldorf Hackerspace, where she
also leads the groups for Reverse Engineering and x86 Assembly. In her free time, you can find Thaís building
tools, cooking or climbing somewhere offline.


What is the max Reflected Distributed Denial of Service (rDDoS) potential of IPv4?
----------------------------------------------------------------------------------
by Éireann Leverett & Aaron Kaplan

Sounds crazy to even try to estimate right?

This presentation will cover the details of the calculation, and how we
can track these numbers over time. We will also do some visualisation of
this data and initiate discussion of where our resources should be
spent best in fighting the threat of rDDoS attacks. The key contribution
is an extensible methodology for measuring global potential for rDDoS
attacks, in realistic terms of throughput. Why might this matter to DDoS
mitigation, and what can we learn by watching these trends over time?

Bio: Éireann Leverett
---------------------

Éireann Leverett hates writing bios in the third person. He once placed
second in an Eireann Leverett impersonation contest. He likes teaching
the basics, and learning the obscure. He is sometimes jealous of his own
moustache for being more famous than he is. If he could sum up his life
in one sentence; he wouldn't. That would be a life-sentence! He is
primarily known for smashing the myth of the air-gap in industrial
systems with his master's thesis, and Switches Get Stitches. He believes
security takes an awful lot more than penetration-testing and speaks
often about the wider effects of embedded system insecurity. Lately he
works on security economics matters for cyber insurance with his own
company Concinnity Risks.

Bio Aaron Kaplan
----------------

Aaron Kaplan works at CERT.at and is on the board of FIRST.org
He likes global perspectives on the Internet since he believes this is a common space for all of us.
Outdated devices on the 'net == pollution.

With Eireann he shares quite a few interests starting from data science, asking smart questions to
each other and of course the resentment of writing one's own bio in the third person.


Network Automation is not your Safe Haven: Protocol Analysis and Vulnerabilities of Autonomic Network
-----------------------------------------------------------------------------------------------------
by Omar Eissa

<!-- 45 min -->

Autonomic systems are smart systems which do not need any human management or intervention.
Cisco is one of the first companies to deploy the technology in which the routers are just "Plug and
Play" with no need for configuration. All that is needed is 5 commands to build fully automated
network. It is already supported in pretty much all of the recent software images for enterprise level
and carrier grade routers/switches.

This is the bright side of the technology. On the other hand, the configuration is hidden and the
interfaces are inaccessible. The protocol is proprietary and there is no mechanism to know what is
running within your network.

In this talk, we will have a quick overview on Cisco's Autonomic main components, then I will
reverse-engineer the proprietary protocol through its multiple phases. Finally, multiple
vulnerabilities will be presented, one of which allows to crash systems remotely by knowing their
IPv6 address.


Bio: Omar Eissa
---------------

Omar Eissa is a security Analyst working for ERNW. His interests are network security and reverse-
engineering. He is a professional Cisco engineer with various years of experience in enterprise and
ISPs networks. He has given talks and workshops at various conferences like Troopers17, Black Hat
US and Def Con.


Hospitals and infosec (the consequences of bad security in health care)
-----------------------------------------------------------------------
by Jelena Milosevic

<!-- 45-60 min -->


Hospitals can be attractive places for hackers. With access to critical medical records and personally
identifiable information, there is great opportunity to exploit patients. Health care workers are very
busy and, more often than not, there is not a lot of interest in computer security. Privacy and the
protection of computer records sometimes gets put on the back burner, and caring for the devices used in
hospitals is an after-thought, meaning that computers and other devices are not updated in a timely
manner and are prone to vulnerabilities.

I see vulnerabilities on all levels and in all roles and locations in the hospital – in software,
devices, and with humans. The consequences of bad security are huge and can cause harm both to the
patient and to employees. Criminal behaviour can go unnoticed for long periods. Without proper security
controls patient records can be manipulated. You can imagine the consequences; they can happen. Security
needs to be built from the ground up so that employees understand the risks at all levels and can do all
they can to protect the patient. We must build awareness programmes and develop processes and procedures
that are possible to follow, thereby creating a higher level of security to ensure that our patients are not in danger.

This presentation will expose the risks and vulnerabilities in hospitals and aims to start driving the discussion and
generation of ideas for procedures to avoid the dangerous pitfalls that put lives in peril. My goal is to ensure that we
create a safe and secure environment for our patients and employees.

Bio: Jelena Milosevic
---------------------


A pediatrician and ICU nurse with a lot of experience, working at many different hospitals in the
Netherlands. Over the past 3 years active in the infosec community and applying the knowledge of
infosec into the healthcare world to improve the security of the environment for patients and the
medical staff. A member of the I Am The Cavalry group and a part of the network of Women in Cyber.

In Soviet Russia, Vulnerability Finds You
-----------------------------------------
by Inbar Raz

Many times, security researchers pick a subject or a field, and then go hunting for interesting
stuff. And let’s face it - in lack of real Security-by-Design policies and adequate security
practices, pretty much every stone you’ll turn will reveal something under it.

But sometimes, interesting things just run into you while you’re going about your business.
Something just appears before your eyes, begging for your attention.

The stories in this talk are all about research that started because I ran into something and it
caught my attention - I wasn’t looking for it. From Web Automation, through Loyalty Card
fraud, Bots on Tinder and Airport Security fails, I just stumbled into all of them. Some allow you
to steal PII, some allow you to steal money, and some allow you to steal, well, an airport.

*Clarification: While the presentation is named after the famous meme, none of the cases
actually happened in Russia.*

Bio: Inbar Raz
--------------
nbar has been teaching and lecturing about Internet Security and Reverse Engineering for nearly
as long as he has been doing that himself. He started programming at the age of 9 on his Dragon 64.
At 13 he got a PC, and promptly started Reverse Engineering at the age of 14. Through
high-school he was a key figure in the Israeli BBS scene. He spent most of his career in the
Internet and Data Security field, and the only reason he's not in jail right now is because he chose
the right side of the law at an earlier age.

Inbar specializes in outside-the-box approach to analyzing security and finding vulnerabilities.
Using his extensive experience of over 20 years in the Internet and Data security fields, he spent
3 years at Check Point, running the Malware and Security Research, and 2 years at PerimeterX,
performing fascinating research on Bots and Automated Attacks and educating both customers
and the public about the subjects.

Inbar has presented at a number of conferences, including Defcon, Kaspersky SAS, Hack.lu,
CCC, Virus Bulletin, ZeroNights, ShowMeCon, several Law Enforcement events and Check
Point events.

Front door Nightmares. When smart is not secure
-----------------------------------------------
by ObiWan666

I will present a closer look onto electro-mechanic door locks, so called "digital cylinders". In my
talk, I will mainly not speak about the RFID hacking part. This has already been done by many other and
will be only a small topic, including what kind of tools to use, comparison chart of different RFID
transponders, etc. I will talk more about the electro-mechanic design of the locks and where to attack
these. We will learn, how these locks are working in general and I show different techniques used by different
vendors. After the overview, we will dig deeper into the mechanical and electronic details of the locks. I
will then show where the weaknesses of the design are, and, how to open the locks without a valid RFID
Transponder. The audience will learn how they can identify good and bad locks. Even a "not so secure" lock can
work in environments where no classified information is stored.

Bio: ObiWan666 - @ObiWan666
---------------------------

Security Evangelist and Firefighter.
48 Years old. Security enthusiast since decades
Interested in hardware hacking, forensic, car security and always want to know, how things work.

ObiWan666 is a 48 year old electronic technician, who works in the oil and gas industry since more than 17 years.
Before that, he joined the german army for more than 6 years as Navigation electronic expert for Helicopters.
During this time, he was in several missions across the world. Electronic and mechanical background is his
force to look from both sides on security.
And last but not least, he his a volunteer firefighter more than 30 Years.
He knows to be "under fire".

WTFrance ?! Cryptography and legislation in France
--------------------------------------------------
by Okhin

France is known for its lack of respect of politicians, cheese, wine andbaguette. It is less known
for its fight against Privacy and Cryptography, especially those last years and during the state of emergency.

And, even if you're not French, you should care, because french representatives in european
parliament are leading the fight against Privacy and Cyptography.

This talk will go through the laws which restrict access to information and cryptography, and how
some of them failed spectacularly, detail the new government and their position regarding mathematics
and what is the impact of those representatives on the European Union.


Bio: Okhin
----------

TODO

Randori, a low interaction honeypot with a vengeance
----------------------------------------------------
by Bouke van Laethem

Randori is an opensource honeypot built behind existing services. The author will discuss its
conception and first results. Based on these results he will suggest a different model for
thinking about and dealing with global botnet infections: one that is not based on the idea of
cyber warfare, but cyber disease control.

Bio: Bouke van Laethem
----------------------

Fittingly equipped with a history degree, Bouke set out ten-odd years ago as an ethical hacker.
Recently he saw the light and joined the blue team, where he enjoys solving incidents, building
tools and chanting "Shit's on fire, yo".

API design for cryptography
---------------------------
by Frank Denis

It was a Monday morning in the office and, as usual, everyone was busy sorting through their
mail before starting work.

Still in a daze, Frank innocently and aimlessly typed these words in the Google search box:
"how to encrypt stuff". As he kept reading, his blood pressure kept increasing. And what
happened next remains unclear to this day.

Frank will share his story of recovery with the audience. Why he cried in despair at first,
how he cried even more later, and his slow path to recovery. He will talk about NaCl, libsodium, and
about the paste (sic), present, and future state of cryptographic libraries, with an emphasis on their mesmerizing APIs.

Finally, he will not announce the public availability of a new, related, open-source project.


Bio: Frank Denis
----------------

Frank is a carbon-based living organism, frequently observed in Paris, France.

When he's not slacking off on Twitter, he offers his expertise in malware analysis, distributed systems,
application security and digital image processing to companies of all sizes.

He's also a long-time opensource enthusiast and contributor, with an emphasis on security-oriented projects.

Automation Attacks at Scale
---------------------------
by Will Glazier & Mayank Dhiman

Automation attacks are currently plaguing organizations in industries ranging from
financial and retail, to gaming and entertainment. These attacks exploit stolen credential
leaks, black market & custom attack toolkits, and massively scalable infrastructure to
launch widely distributed attacks that are extremely difficult to detect, let alone attribute.
In this presentation we will inform the audience of the scale of this problem, discuss a
detection methodology to counter these attacks, and walk through 3 real-world examples of
how attackers created and monetized the distributed infrastructure they require to launch these attacks.

Bio: Will Glazier
-----------------

Will Glazier serves as Stealth Security’s Threat Intelligence Analyst & Architect. His
primary interests include understanding attacker infrastructure responsible for malicious
automation attacks, including account takeover. His current focus is on building out a
threat intelligence database with indicators relevant to the problem of malicious automation, by
tracking the use of leaked credentials, shared attacker infrastructure, and black market attack
toolkits. His previous experience includes a stint at Fireeye. He holds a BA in International
Relations & Economics from Tufts University.

Bio: Mayank Dhiman
------------------

Mayank Dhiman serves as Stealth Security’s Principal Security Researcher. His primary
interests include solving problems related to online fraud and internet abuse. His current
focus lies in detecting and mitigating malicious automation attacks. Previously, he had
worked on fraud and abuse related solutions at Facebook and PayPal. He is the co-author of a
number of research papers and book chapters and his work has been presented at USENIX HotSec,
NDSS USEC, APWG eCrime and RSA. He holds a MS in Computer Science from UC San Diego.

Bug hunting using symbolic virtual machines!
--------------------------------------------
by Anto Joseph

<!-- 17th or 18th -->

In this talk , we introduce the participants to the world of symbolic execution. It's uses in
reverse engineering, fuzzing or vulnerability discovery is less known in the infosec community.
We try to impart the basics to get up and running with the KLEE symbolic virtual machine and
solve some interesting challenges. Software Vulnerabilities like memory corruptions, certain
logical bugs, complex arithmetic used for obfuscation etc could be easily solved using
symbolic execution. Symbolic execution is well discussed in academic papers, but it is not widely
used by security researchers. It has been proved with tools like angr that they are remarkable
in detecting vulnerabilities.

Bio: Anto Joseph
----------------

Anto Joseph is a Security Engineer at Intel. He has 4 years of corporate experience in developing
and advocating security in Mobile and Web Platforms. Machine Learning is one of his key areas of
Interest. He is very passionate about exploring new ideas in these areas and has been a presenter
and trainer at various security conferences including BH USA 2016, DEF CON 24, BruCon,
HackInParis, HITB Amsterdam, NullCon, GroundZero, c0c0n, XorConf, and more. He is an active
contributor to many open-source projects and some of his work is available at https://github.com/antojoseph

Vulnerability Disclosure, Governments and You
---------------------------------------------
by Jeroen van der Ham

Vulnerability Disclosure has earned its place in security. The trend of full disclosure died in the 90s as
realisation set in that writing software really is complex, and not all vendors are at fault for having errors in code.

In the 21st century vulnerability disclosure has become more and more acceptable. This can be seen by the rise in
companies that help with vulnerability disclosure, and the large companies that have paid programs, so called bug
bounties. More and more governments are showing an interest in making this possible.

Vulnerability disclosure and incident response has become a recognised practice also in policy making. At the EU
level it has hugely influenced debates about GDPR and the NIS directive. It has also been affected by high-level
policy discussions regarding export control and dual-use goods in the international Wassenaar Arrangement.

Policy-making has become a factor in the world of security and incident response. Join me in the discussion on how we can start moving this forward.


Bio: Jeroen van der Ham
-----------------------

Jeroen van der Ham is a security researcher at the NCSC-NL since 2015. In his current research he
focuses on privacy and security, as well as ethics in security research. He has published on ethical
analyses of research and education, network monitoring, and semantic descriptions of computer networks and
associated infrastructures. He currently holds positions at the TU Delft as well as the University of Amsterdam,
where he serves as ethics advisor.

Jeroen received his Ph.D. degree from the University of Amsterdam in 2010 for his thesis entitled "A Complex
Model for Computer Networks, the Network Description Language", after which he worked as a researcher at the University of Amsterdam until 2015.


TIDS: A Framework for Detecting Threats in Telecom Networks
-----------------------------------------------------------
by Alexandre De Oliveira & Cu D. Nguyen

Telecommunication networks started to be designed 40 years ago without taking into account security to a large
extent. As a result, they are known to be vulnerable to various attacks, such as location tracking, spoofing, and
interception. In parallel, we have seen recently more services giving an easy access to SS7 interconnection, SMSC and
interception of calls and SMS. This challenges our security objectives. Moreover, Telecom networks are considered
critical infrastructure and protecting them is a must for the nation.

We present a monitoring framework, called TIDS - Telecom IDS, which we devise at POST Luxembourg for
security network monitoring and detecting anomalies. The aim is to protect our infrastructure from
abuses and DoS attacks on one hand. On the other hand, we want to pro-actively detect security related
issues affecting our subscribers that pertain to spoofing and user privacy evasion, among others. The
proposed framework consists of two main components. First, a data collector listens to live signaling data,
parses and filters relevant events before sending them to Splunk, an industry-leading bigdata analytics platform.
Second, an analytics app, which rests on top of Splunk, applies various statistical and machine-learning methods to
provide the user with real-time traffic and anomaly reports.

Bio: Alexandre De Oliveira
--------------------------

As telecom security researcher, Alexandre De Oliveira is part of the POST.lu CSE Red Team. Previously
coming from P1 Security were he provided security expertise for SS7/SIGTRAN, LTE technologies and all the
systems linked to critical infrastructures for major telecom networks, he has always been looking for new
security challenges around unknown & proprietary technologies that telecom networks cherish so much. Speaker at
different conferences about telecom security, Alexandre started mainly research in offensive telecom security and more
recently moved to a more chalenging part, the defense which back is theses years was notexistent. Conferences were he
presented excludes HITB, Troopers, Hackito, CCC.

Bio: Cu D. Nguyen
-----------------

Dr. Cu D. Nguyen has 15+ years proven broad and deep experience in machine learning, computer
security, and secure software engineering. He received his Ph.D. degree with a distinguished
dissertation in the field of Artificial Intelligence and Software Engineering from the University of
Trento, Italy in 2009. Before joining POST Luxembourg as a Data Scientist and Security Expert, he
worked as a researcher at the University of Luxembourg and has published 50+ scientific papers to
prestigious international conferences and journals.

Myths and realities of attribution manipulation
-----------------------------------------------
by Félix Aimé & Ronan Mouchoux

Who is attacking us? The cyber security companies and media have identified
France, US, Russia, China, Iran or North Korea as responsible of cyber
attacks. However, this work stay complex to achieve without having access
to human intelligence (HUMINT), signal intelligence (SIGINT) or computer
network exploitation (CNE). When technical details of an APT group and
their TTPs are published on the Internet, it may be possible to create a
copycat of the modus operandi to deceive defenders and victims. After
presenting the difference between each notion (Attribution, copycat, False
flag etc.) with real-life examples, this presentation will show that
creating a real and working copycat is more complex than just “repackaging
malwares”. Then we will explain more precisely why most of the wild use of
copycats is more about using what is working than a real objectives for the
attackers. The presentation will conclude with a reflexion to the future of
attribution and identification of malicious actors, while covering the
myths and realities of the use of deception on real Life.

Bio: Félix Aimé
---------------

Félix starts its career as a cybercrime analyst, identifiying emergent
threat and conductiong investigation. He then becomes a pentester for some
time, but quickly come back to investigation activities, as a Threat
Intelligence analyst for the ANSSI (French Government CERT). During four
years he tracked APT related actors, developped complex heuristic to follow
campaign and provide geopolitical insight to authorities to better
understand underlying motivation of state-sponsored groups. He joined the
Global REsearch and Analysis Team (GREAT) of Kaspersky in 2017 to enforce
their Threat Intelligence capabilities.

Bio: Ronan Mouchoux
-------------------

Ronan has been a NOC then a SOC analyst, allowing him to developped its
skills in network computer and to developped its corporate IT skills. He
then joined CERT La Poste where he conducted for three years research over
botnet command and control, corporate network filtering evasion and
investigation automation. He then moves to investigation activities for
severals privates companies, creating or developping internal Cyber Threat
Intelligence capabilities. He joined the Global REsearch and Analysis Team
(GREAT) of Kaspersky in 2017 to enforce their Threat Intelligence
capabilities.

The Struggle: dealing with language designers & maintainers on proper use of CSPRNGs
------------------------------------------------------------------------------------
by Aaron Zauner

Implementation, hazards and updates on use of CSPRNGs in programming languages and the Linux
Kernel (among others):

Over the past two years multiple people have been engaging language
maintainers and designers to change their use of CSPRNGs (mainly relying on user-land RNGs
like the one from OpenSSL, and sometimes suggesting "adding entropy" by various means from
user-land daemons like haveged). In this short presentation we'll survey the struggle of
cryptographers, developers and security engineers to change the path various high-profile
languages have taken to provide randomness to their userbase. Affected languages include
but are not limited to: Ruby, node.js and Erlang. We outline better approaches for language
maintainers and implementers as well as coming changes within the Linux kernel crypto
subsystem (i.e. /dev/random and /dev/urandom) w.r.t. security and performance. Recently
these changes were merged into mainline Linux (4), problems with languages implementations
however remain. We'll also discuss operating system provided randomness testing, attacks/mitigation
in embedded and virtualized environments.


Bio: Aaron Zauner
-----------------

Aaron Zauner (azet) 10+ years of engineering. Has seen the fallacies of distributed computing.
Still enjoys working and researching in the industry. Loves tuning, scaling
and securing of distributed systems - building on and contributing to great
Free & Open Source Software. Above all: getting to meet brilliant people,
exchange ideas and work on exciting projects all the time! I am
self-employed and primarily do engineering work, consulting and research on
IT Infrastructure Architecture, Operations & Development, Applied
Cryptography, High Performance Computing and Information Security. I've
held talks on DevOps, HPC and Security related topics at various venues -
from local meetups to internationally recognized conferences.

[Publications](https://scholar.google.com/citations?user=pMyYN5wAAAAJ)

The untold stories of Hackers in Detention
------------------------------------------
by azet & JKT

Bacause Phrack `Volume 0x0e, Issue 0x43, Phile #0x05 of 0x10` isn't what you should expect:

Two hackers tell their stories about life in pre-trial detention, courtyard talk and everything
that's wrong about the public's perception of incarceration. Prison changes people, not for the
better - these Hackers made the best of their seemingly endless time in prison; hence
have quite a few facts to get right and stories to tell.

The speakers share a combined total of 634 days of kafkaesque remand imprisonment experience
in two different European countries (Denmark & Germany).


Bio: azet
---------

azet (122 days pre-trail detention): detained on 9th of July 2016 for allegedly
assaulting police officers, breach of the peace, [et cetera] during a demonstration against the
illegal eviction of one of the oldest Squats in Berlin/Friedrichshain (Rigaer94)


Bio: JKT
--------

JKT (512 days pre-trail detention): detained on 5th of June 2013 for allegedly being involved
in Mainframe hacking (actually for talking to someone who unsuccessfully attempted logging onto an FTP server)

Applying bug hunters methodologies to your organisation, lessons from the field.
--------------------------------------------------------------------------------
by Paul Amar

Bug bounty community has been extremely active in the last couple of years, providing
grateful resources to perform security assessment of different kind of platforms. Those
techniques and concepts can especially be re-used in similar way inside your organisation,
whatever size it is.

In this talk, we will provide you information on how we got started, from
extracting useful information from different sources such as HackerOne, Shodan, Censys and so on, to
identify similar security issues inside your company. The techniques presented will cover a lot of
reconnaissance skills (combined with benchmarks) actively used in the wild additionally with exploitation ones.

This talk aims at providing tools and content either for bug hunters but also organisations who want to be one
step ahead by using similar techniques. Expect few releases on GitHub this same day :)

Bio: Paul Amar
--------------

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec eu nibh quis tellus iaculis malesuada sit amet eu mi. (...)
More seriously, Paul Amar is working as a Security Analyst for Michelin. He likes breaking things as a hobby and developing open-source tools mostly in Python. (Such as DET, a toolkit to exfiltrate data over multiple channels). He also likes IPA beers and cookies.

Workshops
=========

Reverse Engineering  a (M)MORPG
-------------------------------
by Antonin Beaujeant

<!-- 4 or 6 or 8 hours -->

<!-- Other notes:
Ideally, I would like to set up a game environment locally so the audience can play, reverse, inject along with me.
For this, I would need a server that can run the game.
Can this be provided by Hack.lu?

I guess I'm asking a lot, but would that be possible to have two beamers?
One for the game/hack and the other for the slides?
If not, one should be enough, but I will just need to switch between screen and laptop often.

-->

This workshop will cover the basics of reverse engineering a (M)MORPG. The
target will be Pwn Adventure 3, a MMORPG developed by Vector35 for the Ghost in the
Shellcode 2015 CTF. Despite being old and intentionally vulnerable, the technique and
methodology used should not differ from reality. We will first have a closer look at the
network communication between the client and the game server and dissect the custom binary
protocol used. For this, the instructor will explain a methodology that consist of isolating
data, analyse the changes and raise assumptions. Once the protocol partly reversed, we will
build a Wireshark parser (dissector) in order to start analysing the protocol itself. For
further tests, we will create an asynchronous proxy for intercepting the network traffic in
order to successfully modify and/or inject packets. In the next part of the workshop, we will
reverse engineer the client/server logic in order to highlight "secrets" to finish a few
quests and identify vulnerabilities in the game. We will also patch the binary to become a
Superman (running faster, jumping higher). Finally, we will hook the DLL in order to hack the
game "on the fly".

Bio: Antonin Beaujeant - @beaujeant
-----------------------------------

Antonin Beaujeant [@beaujeant](https://twitter.com/beaujeant) is a professional
penetration tester and researcher. His primary focus is web app and network
penetration test but he also enjoy spending time on hardware, reverse and CTF in general.

Hacking workshop mobile devices
-------------------------------
by Frank Spierings

<!-- 4 hours -->

Bio: Frank Spierings
--------------------

Malware Triage Workshop - Malscripts Are The New Exploit Kit
------------------------------------------------------------
by Sean Wilson and Sergei Frankoff

<!-- 4 hours, 2h is doable but sub optimal-->

Traditionally malware triage has focused on exploit kits which were the initial
infection vector of choice, but this is changing. In recent years malscripts and
file based exploits have become an equally common initial infection vector. Often
delivered via email, malscripts can take many different forms, WScript, Javascript, or
embedded macros. However, the goal is always the same; obtain code execution and deliver a
malicious payload.

In this workshop you will work through the triage of a live malscript sample. During this
process you will identify and extract malscripts from Office documents, manually deobfuscate the
malscripts, circumvent anti-analysis techniques, and finally determine the purpose of the scripts and
payload in order to develop countermeasures.

This workshop is aimed at junior incident responders, hobby malware analysts, and general
security or IT practitioners. If you have a good understanding of scripting languages like
VBScript, and Javascript, and you are familiar with windows internals you should have no
problem completing the workshop. We request that you come prepare with a laptop that you are
able to use to analyze malware. We strongly recommend installing a Virtual Machine. If you
would like to install a temporary Windows 10 virtual machine you can [obtain a free copy](https://developer.microsoft.com/en-us/windows/downloads/virtual-machines).
We also recommend you have Python 2.7 installed on your laptop, you can [obtain a copy](https://www.python.org/download/releases/2.7/).

Bio: Sean Wilson
----------------

Sean is a co-founder of Open Analysis, and volunteers as a malware researcher. He
splits his time between reverse engineering malware and building automation tools for
incident response. He is an active contributor to open source security tools focused on
incident response and analysis. Sean brings over a decade of experience working in a number of
incident response and application security roles with a focus on security testing and threat modelling.

Bio: Sergei Frankoff
--------------------

Sergei is a co-founder of Open Analysis, and volunteers as a malware researcher.
When he is not reverse engineering malware Sergei is focused on building automation
tools for malware analysis. Sergei is a strong believer in taking an open, community
approach to combating cyber crime. He actively contributes to open source tools and tries to
publish as much analysis as possible. With almost a decade of experience Sergei has held roles both,
as the manager of an incident response team, and as a malware researcher.

Getting the Most Out of Windows Event Logs
------------------------------------------
by David Szili

<!-- 4 hours -->

A typical mistake repeatedly made by many security teams is that they collect such
large amount of events that at the end, their Security Information and Event Management (SIEM)
solution chokes on the data fed into it, rendering it slow and ineffective. "Collect all the events!!!"
sounds nice in theory, but in practice, less is often more and we must select and focus on events that
provide real value from a security perspective and have an actual use-case behind them. But what if we do
not even have a SIEM and cannot afford one or do not have the staff or the skill to deploy and maintain one?
Luckily, in a Microsoft Windows environment we have built-in and free tools at our disposal to get quickly
started with security monitoring and hunting using Windows Event Logs.

In this workshop, we will go through some of the most important and valuable Windows Events to be
collected such as AppLocker or EMET events, user and service creation events, PowerShell commands, etc.
We will discuss how to properly configure Advanced Audit Policy Settings, see how to collect events with
Windows Event Forwarding (WEF) and how to set up Sysmon for advanced application and process monitoring.

Once we have the list of events we need, we will see a few simple PowerShell commands and modules that
can help us slice and dice Event Logs like Get-WinEvent. We will also test scripts and tools that are
made for monitoring and detection, such as DeepBlueCLI. Finally, we will use the free Power BI Desktop to
build nice dashboards to give us a better overview of the data we are collecting.

Bio: David Szili
----------------

David Szili is the CTO of Alzette Information Security with penetration testing, security monitoring
and incident response background, previously working for companies like POST Telecom PSF,
Dimension Data, Deloitte and Balabit.

David has two Master’s degrees in Computer Engineering and in Networks and Telecommunication
and a Bachelor’s degree in Electrical Engineering. He also holds several IT security certifications such
as GSEC, GCED, GCIA, GCIH, GMON, GNFA, GMOB, OSCP, OSWP and CEH.

In his spare time, David likes working on hobby electronics projects, develop new IT security tools or
sharpen his skills with CTFs and bug bounty programs.

SAP Pentest - From outside to company salaries tampering
--------------------------------------------------------
by Yvan Genuer

<!-- 3 or 4H (prefered), Tuesday -->

SAP is boring, too big or too complicated? What about learning SAP Security during a fun CTF workshop?
Additionally we'll provide you with a pre-configured attacker VM with all tools required to perform workshop activities.
Attendees learn how to work against different SAP Systems targets with different configuration issues in  a 'realistic' environment.
Few slides, lots of practice - this is the leitmotiv of this guided SAP pentest workshop.

Bio: Yvan Genuer
----------------

Yvan has near than 15 years of experience in SAP. Starting out as a SAP basis administrator for various
well-known French companies, since 5 years, he focuses on SAP Security and is now the head of SAP
assessment and pentesting at Devoteam security team. Although being a very discreet person, he received
official acknowledgements from SAP AG for vulnerabilities he's reported. Furthermore, he is a longtime
member of the Grehack conference organization and has conducted a SAP pentest workshop at Clusir 2017, as
well as a full training at Hack In Paris 2017.


Mobile Security workshop
------------------------
by Frank Spierings & Arthur Donkers

<!-- 4H to 1day -->

This workshop takes students on a tour of testing the security of mobile applications.
Loosely following the OWASP mobile security testing guide (MSTG) students learn how to
find vulnerabilities in mobile applications, circumvent rooting/jailbreak detection and break
certificate pinning. Knowing these techniques enables students to manipulate the traffic
between applications and backend systems, play around with local files and inject their own
code into the applications.

During the workshop, we focus on both static analyses (decompilation of APK files,
manipulate SMALI and disassembling iOS code) and dynamic analysis (tampering with the
runtime behavior of applications).

We make extensive use of the Frida toolkit for runtime injection, overloading and hooking
applications. This toolkit works both on iOS and Android and offers a great interface for
mobile application testers.

Special attention is given to injecting Frida into applications on a non-rooted or non-jailbroken
device. Due to advances in both Android and iOS, it will get harder to break the
security on a device and install your own framework.

Students are encouraged to bring their own laptop with an up-to-date Android SDK and a
(rooted) device so they can do the hands-on exercises on their own. Students may bring
their iOS devices with an up-to-date XCode and a valid developer certificate, but the focus
will be on Android (due to availability). We will demo some of the stuff on IOS.

Bio: Arthur Donkers
-------------------

Arthur Donkers lives in the beautiful northern part of the Netherlands and started
his career as an electrical engineer building his first computer from scratch.
And then Linux happened, which was a great platform for learning and building
things. Using Linux he started doing security scans and penetration testing for a lot
of different clients, on all sorts of infrastructure and platforms.
Using his experience from infrastructure and application testing, he started focussing
on the mobile platform, both iOS and Android. In the early days, testing was relatively
easy as these devices could be rooted and jailbroken without any great effort.
Nowadays he teams up with Frank to find ways to test mobile applications without the
need to jailbreak or root it first. They both found a friend in Frida for this.

Bio: Frank Spierings
--------------------

I am Frank Spierings. I have been a computer nerd since the age of 10. I’ve worked in different
area’s in the IT industry. In the last couple of years I’ve transitioned from building
infrastructure to the computer security game. I’ve always enjoyed solving hackig challenges, so
it is a nice improvement to do this for a living. Arthur Donkers got me interested in mobile
application security about a year ago. Since then, I’ve been playing around with Frida. I find it a
lot of fun to be able to manipulate program flow using a fairly easy to use hooking mechanism.


When I am not playing these kind of computer games, I enjoy other technical stuff like kick
boxing and brazillian jiu-jitsu, as well as listening to tecnhical death metal.

[ManaTI](https://github.com/stratosphereips/Manati): Web Assistance for the Threat Analyst, supported by Domain Similarity. Talk and Workshop
---------------------------------------------------------------------------------------------------------------------------------------------
by Raúl B. Netto

<!-- 2H -->
The increasing diversity and amount of malware traffic is pushing researchers to find
better detection methods. When security analysts analyze such large amount of traffic, they are
overwhelmed and therefore they analyze less traffic with less accuracy.

Among the most used characteristics for finding threats in a network is the analysis of HTTP traffic.
The default unit of analysis is usually called weblog, from a log for the web traffic. Security
analysts usually use these weblogs to detect threats from infected computers in their internal networks.

To find threats it is needed a complex expert knowledge that ranges from looking for domains
which have being reported as malicious, to analyzing the patterns in the URLs and using the
WHOIS information of the domains. Although these techniques may work for the average analysis,
they highly depend on the humans generating the reputation rules and on the malware being analyzed.
All in all, analyzing millions of weblogs with speed and accuracy, balancing the amount of
information and finding threats is at least a daunting task. Security analysts need a tool to
help them organize their work, and a machine learning algorithm that can improve the detection and speed up the analysis.

It is in this context that we researched and created a new tool to assist the network security
analysts to find threats: the ManaTI project. It has two main goals: First to assist the analysts,
be means of a web interface, in evaluating the network traffic to better find and process the network
information. Second, to create a machine learning method that can identify domains which WHOIS
Information is related. Our algorithm can work as a WHOIS classification of similar domains or as a WHOIS similarity distance.

Our WHOIS Distance Algorithm (WDA) works by first extracting the WHOIS data from the two domains to be
compared, then generating eight features from the comparison of both sets, and finally training and applying a
linear model to obtain the final distance. WDA can compute the distance between any type of domains. To make our
labelled dataset for training and testing, we use normal domains of well known companies, such as Facebook,
Apple and Oracle. We obtained the malicious domains from projects as: DNH-BH[1], Ransomware Tracker[2] and the
Stratosphere IPS Project[3]. The WDA can help analysts to find similar domains based on their knowledge of other
normal or malicious domains.

ManaTI was developed using the Django web framework for Python. It has several tools that improve the
efficiency and accuracy of the analysts, such as: a dynamic table to visualize weblogs, bulk labeling of
weblogs, the possibility to get and show information from VirusTotal or online WHOIS databases, the
function to relate domains using the WHOIS distance algorithm explained before and a large number of
features to evaluate the performance of the analyst. ManaTI is highly scalable and modular, allowing the
analysts to create their own Python scripts using the API provided by the system.


Bio: Raúl Benítez Netto - [@HoneyJack](https://github.com/HoneyJack)
--------------------------------------------------------------------

Hi there. I am working with computers since the age of 12. I have been working as Web Developer
during 4 years, and then I decided to move from my native Paraguay to the Czech Republic. Nowadays, I am
trying to create web applications and help security researchers in their analysis of malware behavior in the
network.  I am passionate about cyber-security and machine learning. Master student in the Czech Technical University in Prague

I am working in the startup [SingleCase.cz](https://www.singlecase.cz/cz/home/) as a web-mobile developer and in the
lab of [Stratosphere IDS Project](https://stratosphereips.org) in [AIC](http://aic.fel.cvut.cz). In Stratosphere lab,
we are researching about machine learning and computer security to help NGO and companies with their cyber-security incidents.

Besides, I am interested in hacking stuff like Rubber Ducky USB or small projects with Raspberry Pi or Omega2.
Lover of books, especially of classic writers’ books, backpacker when my time allows it to me and an amateur photographer.
Stay in touch! [@Piuliss](https://twitter.com/Piuliss)


Python and Machine Learning
---------------------------
by Sébastien Larinier

The goal of workshop is to present how to use python to make machine
learning. We take examples of security data like malwares and we explain
how to transform data to use algorithm of machine learnings. We details the
different algorithms and the different librairies Scikit-learn and
Tensorflow.

The algorithms help to clusterize quickly a database malware to create yara
signature for using in Incident Response.
The participants will work on little dataset and develop some code based on
theses librairies and create yara signature.

Bio: Sébastien Larinier - [@sebdraven](https://twitter.com/sebdraven)
---------------------------------------------------------------------

Sébastien Larinier currently is an freelance Senior Researcher
and Incident Handler after created the CERT Sekoia located in Paris. Member
of the honeyproject chapter France and co organizer of botconf. Sébastien
focused his work on botnet hunting, malware analysis, network forensics,
early compromission detection, forensic and incident response. Python
addict he supports different opensource projects like FastIR, veri-sig,
Oletools, pymisp, malcom…,

Breaking Apps with Frida
------------------------
by Jahmel Harris

Frida well know by mobile application testers as a way to bypass security controls such as root
detection or SSL pinning. At its core, frida is a framework for injecting JavaScript into running
applications that makes things significantly easier when it comes to reverse engineering and modifying binaries.

This 2 hour workshop will go though using Frida on Linux and Android and though exercises and
walkthroughs show how Frida can be used to rapidly reverse engineer applications to understand
logic flow, dump secrets and bypass security controls.

Although what we look at here is relevant to mobile applications, this is not a mobile hacking
workshop (in fact, most exercises will take place on Linux binaries) but might be useful to
mobile testers looking to take their security testing to the next level.


Bio: Jahmel Harris
------------------

Jahmel is a security researcher and hacker. He co-founded Digital Interruption this year; a
security testing consultancy which also works with organisations to development tools,
techniques and methodologies to integrate security into agile development teams. With a
background in not only security testing but software development, Jahmel is able to advise
engineers on balancing security with functionality.

Jahmel has a particular interest in mobile application security, reverse engineering and
radio and has presented talks and workshops at home in the UK and abroad. He also runs
Manchester Grey Hats - a group aiming to bring hackers together to share knowledge and skills.

Programming Wireshark With Lua
------------------------------
by Didier Stevens

In this 2 hour workshop, you will learn how to program Wireshark with the
Lua programming language.

Wireshark can be extended using the C and Lua programming languages. In
this workshop, we will look into Lua taps and dissectors to help you
analyze traffic that "pure" Wireshark does not understand. Wireshark
dissectors are often designed to analyze a network protocol.
You will learn how to install Lua dissectors and program your own.
Say you are reversing a botnet, then you can develop your own dissector
that analyses the custom network protocol that the botnet uses to
communicate between the C&C and the clients. But custom dissectors can help
you even with known network protocols. For example, Didier will teach you
the inner workings of a simple custom dissector he developed in Lua to
display TCP flags like Snort (this was later introduced as a permanent
feature in Wireshark).

Attendees of the workshop should bring a laptop with Wireshark installed
and have administrative rights.

Bio: Didier Stevens
-------------------

Didier Stevens (Microsoft MVP, SANS ISC Handler, Wireshark Certified
Network Analyst, ...) is a Senior Analyst working at [NVISO](https://www.nviso.be).
Didier has given Wireshark 2-day trainings at several security conferences.
You can find his open source security tools on his [IT security related blog](https://blog.didierstevens.com).

Hacking the Warrant: A workshop on LEA CNE
------------------------------------------
by Scarlet Kim & Éireann Leverett

<!-- talk the 18th -->

Hacking by law enforcement is on the rise, in criminal cases. What would an ideal warrant look
like in such cases? What would it allow, and what would it prevent? Who would oversee it? Could cryptographic
technologies be employed to limit overuse of exploits? Or to trace the use of them years afterwards? How does
all this intersect with disclosure debates?

CNE by law enforcement is in use around the world, this workshop proposes to discuss that with some real world
examples, and write counterfactuals of how they would have worked with different oversight, and judicial review.
Until every juror is a technologist, hackers will need to contribute to legal processes in order to produce sensible
educated stakeholders in judicial processes.

Scarlet is a seasoned lawyer, and Eireann is an unreasonable hacker. Together, they seek to bring
together law enforcement and computer offence and defence teams, to identify how this could all
work in a multi stakeholder, multi jurisdictional world.

Bio: Scarlet Kim
----------------

Scarlet Kim is a Legal Officer at Privacy International, a London-based human rights NGO
focused on issues arising at the intersection of privacy and technology. Scarlet is involved in
litigating cases concerning government hacking, bulk interception, intelligence sharing, and freedom of
information in the courts of the U.S., the U.K. and Europe. Scarlet previously worked as an Associate Legal
Adviser at the International Criminal Court and as a Gruber Fellow in Global Justice at the New York Civil
Liberties Union. Scarlet received her J.D. from Yale Law School and her B.A. from Yale University. She is a U.S.-qualified
lawyer and is admitted as a Solicitor in England and Wales.

Bio: Éireann Leverett
---------------------

Éireann Leverett was an Open Web Fellow with Privacy International 2016-2017 and continues to enjoy
collaborating with talented lawyers working on hacking problems.

Dr. Honeypots - How I Learned to Stop Worrying and Know My Enemies (and Worms)
------------------------------------------------------------------------------
by Guillaume ARCAS

Nowadays there's a "arm-race" when a new vulnerability is found or exploited between metasploit
plugins developpers and honeypots coders. WannaCry & NotPetya incidents also showed that
honeypots are not dead (they only go to github to recode).

This introductory worshop aims to give the attendees the basics on honeypotting deployment
and pros & cons on this tools.

An install party is not excluded at the end of the workshop.

Note that as the author is member of The Honeynet Project, his visions about how useful honeypots are can be biased.

Bio: Guillaume ARCAS
--------------------

TODO

Incident Response in the Age of Threat Intelligence with MISP, TheHive & Cortex
-------------------------------------------------------------------------------
by Saâd Kadhi, Alexandre Dulaunoy, Andras Iklody

- [MISP](https://www.misp-project.org/), [TheHive](https://thehive-project.org/) & Cortex Overview
- Installing & Configuring MISP
- Installing & Configuring TheHive & Cortex
- Bringing it all together
- The Incident Response process
- Simple IR case study
- Enters MISP: Threat Intelligence, events and alerts
- From Zero to Hero: the complete investigation cycle by example
- Workshop conclusion, Q&A

Attendees must:

- Have prior experience in the field of information security.
- Have good knowledge of TCP/IP, DNS and related concepts such as hashes and URLs.
- Bring laptops powerful enough to run two VMs at the same time.
- Install prior to the workshop the MISP training VM available from the following URL:
- https://www.circl.lu/services/misp-training-materials/
- Install prior to the workshop TheHive+Cortex training VM available from the following URL:

https://github.com/CERT-BDF/TheHiveDocs/blob/master/training-material.md

Attendees should:

- Be comfortable using Linux or Unix-like operating systems.
- Have basic knowledge of Incident Response, Digital Forensics & Threat Intelligence.


Bio: Saâd Kadhi
---------------

Saâd Kadhi is TheHive Project’s leader. He has over 18 years of experience in cybersecurity. He discovered incident response and digital forensics in early 2008 and has been working exclusively in this fascinating field since then. He built a CSIRT at a French multinational food-products corporation and worked as an analyst at CERT Société Générale before joining the French national central bank where he leads a team of 20 analysts. He frequently writes information security articles in a leading French magazine. He also co-organizes the Botconf security conference.

Bio: Alexandre Dulaunoy
-----------------------

Alexandre encountered his first computer in the eighties, and he disassembled it to know how the thing worked. While pursuing his logical path towards information security and free software, he worked as senior security network consultant at different places (e.g. Ubizen, now Cybertrust). He co-founded a startup called Conostix specialized in information security management, and the past 6 years, he was the manager of global information security at SES, a leading international satellite operator. He is now working at the national Luxembourgian Computer Security Incident Response Team (CSIRT) in the research and operational fields. He is also lecturer in information security at Paul-Verlaine University in Metz and the University of Luxembourg.

Bio: Andras Iklody
------------------

Andras Iklody is a software developer working for CIRCL and has been the main developer of the Malware Information Sharing Platform since the beginning of 2013. He is a firm believer that there are no problems that cannot be tackled by building the right tool.

