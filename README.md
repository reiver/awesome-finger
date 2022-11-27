# Awesome Finger
A collection of awesome things regarding the **finger protocol** ecosystem.

## What is Finger

**Finger** is one of the early Internet-based **social networks**, with its origins in the early 1970s.

**finger**'ing some could return:

* personal information
* contact information,
* referencs to that person's presence on other parts of the Internet,
* a short biography,
* a journal,
* articles,
* jokes,
* ASCII art,
* and more.

Historically people and even machines were identified by **user** names at a **host** name.
For example:
```
cikrempeaux@changelog.ca
```

Someone could request information _from_ or _about_ a **user** at a **host** using one of the historic `finger` terminal applications.
On the command-line, a simple finger request could be performed with something like the following:
```
finger cikrempeaux@changelog.ca
```

A finger-protocol server could return anything it wanted.
But the spirit of the finger-protocol is that the output should be **human-legible** first, given what technologies are available at the time (and _programmer-legible_ & _machine-legible_ second).

## Table of Contents

* [Clients (Terminal)](#clients-terminal)
* [Clients (GUI)](#clients-gui)
* [Clients (Mobile Android)](#clients-android)
* [Clients (Mobile iOS)](#clients-ios)
* [Clients (Mobile PWA)](#clients-pwa)
* [Servers](#servers)
* [Web Proxies](#web-proxies)
* [Programming](#programming)
* [Specifications](#specifications)
* [Articles](#articles)

## Clients (Terminal)

* [BSD finger](https://wiki.linuxfoundation.org/networking/netkit) — (last updated July 22nd, 2000) one of the historic finger-protocol clients 
* [GNU finger](https://directory.fsf.org/wiki/Finger) — (last updated October 15th, 1992) one of the historic finger-protocol clients
* [finger](https://github.com/reiver/finger) —  a modern finger-protocol client
* [lynx](https://lynx.invisible-island.net/) — a terminal text-based web browser that also supports the finger-protocol

## Clients (GUI)

* [kristall](https://github.com/MasterQ32/kristall) — a GUI gemini-protocol browser that also supports the finger-protocol
* [lagrange](https://github.com/skyjake/lagrange) — a GUI gemini-protocol browser that also supports the finger-protocol

## Clients (Mobile Android)

## Clients (Mobile iOS)

## Clients (Mobile PWA)

## Servers

* [finger.farm](https://github.com/jonroig/finger.farm) — a multi-user finger-protocol server
* [wp-finger](https://danq.me/wp-finger) — turns WordPress into a finger-protocol server 

## Web Proxies

* [the finger api](https://the-finger-api.balbona.me/) — proxies finger-protocol client requests, and returns the response from the finger-protocol server as JSON

## Programming

* [go-finger](https://github.com/reiver/go-finger) —  implements the finger protocol, for the Go programming language; can be used to create both clients & servers

## Specifications

* [IETF RFC-742](https://datatracker.ietf.org/doc/html/rfc742) — (published **1977**) — the finger-protocol existed a was evolving **at least 6 years before** RFC-742 was published; when RFC-742 was published in 1977, RFC-742's purpose was to attempt to describe the protocol that was implemented first by the `finger` program, and then by the `name` program, as well as 3 running finger-sites that existed at the time — `SAIL` (SU-AI), `SRI` (SRI-(KA/KL)), and `ITS` (MIT-(AI/ML/MC/DMS)); i.e., RFC-742 was _not_ attempting to create a new protocol, but instead was an attempting to describe the protocol that already existed, was already implemented, and was already in use by client software, by server software, and by people; i.e., the finger-protocol was created by the person(s) who wrote the software
* [IETF RFC-1288](https://datatracker.ietf.org/doc/html/rfc1288) — (published **1991**) — RFC-742, which was published in 1977, had some parts of it that were considered to be ambiguous by some; RFC-1288, published in 1991 (i.e., **14 years later** after RFC-742 was published, and **at least 20 years after** the finger-protocol existed and was evolving), was an attempt to remove some of the ambiguity of RFC-742, to make it easier for both people who would implement a finger-protocol client or server, and to provide some guidance; **however** RFC-1288 added restrictions to the finger-protocol that did NOT exist in RFC-742; in 1991 some of these restrictions may have seemed reasonable, however today (in 2022) some of the restrictions probably do not make as much sense (and should probably be reconsidered)

## Articles

[History of the Finger Protocol](http://www.rajivshah.com/Case_Studies/Finger/Finger.htm#_Toc484593872) — (published **2000**) — a history of the **finger** and its usage from the early 1970s to the year 2000
