# Awesome Audio Over IP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome [Audio over IP](https://www.avid.com/resource-center/audio-over-ip-avb-and-dante-what-todays-music-producer-should-know) tools and resources.

In the professional audio sector, Audio over IP (AoIP) is about transmitting uncompressed, low-latency audio over an IP (layer 3) network. Popular examples of protocols are [Dante](https://en.wikipedia.org/wiki/Dante_(networking)), [AES67](https://en.wikipedia.org/wiki/AES67) and [Ravenna](https://en.wikipedia.org/wiki/Ravenna_(networking)).

This list is WIP. The AoIP ecosystem is still growing and there is rather sparse tooling available at the moment. Right now this list (and maybe the whole topic) does not match the requirements to be an official awesome list. Also have a look at the other lists, if looking for inspiration.

Contributions welcome! Read the [contribution guidelines](contributing.md) first (TL;DR: Has to be actively maintained and awesome).

---

## Contents

- [Other Lists](#other-lists)
- [Tools](#tools)
- [Organizations](#organizations)
- [Standards](#standards)
- [Education](#education)
- [Unverified](#unverified)

## Other Lists

- [AES67 Wishlist](https://gist.github.com/njh/c9196c465ea33ae9f97db782870464ef) - Popular wishlist for AES67 software, which inspired this list.
- [Curated Web Page](https://aes67.app/resources) - Read-only "curated list of AES67 resources" by Philipp Hartung.
- [Networked Audio Products](https://rhconsulting.uk/blog/networked-audio-products-2024/) - A census of AoIP products, conducted every year.

## Tools

- [Network Audio Controller](https://github.com/chris-ritsen/network-audio-controller) - Reverse engineered Dante Controller on the command line.
- [Pipewire AES67](https://gitlab.freedesktop.org/pipewire/pipewire/-/wikis/AES67) - Show AES67 streams as native audio devices on Linux.
- [Merging ALSA RAVENNA/AES67 Driver](https://bitbucket.org/MergingTechnologies/ravenna-alsa-lkm/src/master/) - Open source driver that doesn't accept contributions.
- [AES67 Linux Daemon](https://github.com/bondagit/aes67-linux-daemon) - Fork of Merging's driver with an open source web server.
- [AES67 Monitor](https://github.com/philhartung/aes67-monitor) - Cross plattform AES67 monitoring app.

### Closed Source

- [Aneman](https://www.merging.com/aneman/) - **A**udio **NE**twork **MAN**ager, the Ravenna equivalent for Dante controller.

## Organizations

- [IPMX](https://ipmx.io/about/) - A proposed set of open standards and specifications for control, copy protection, connection management and security.
- [Audinate](https://audinate.com) - Its proprietary Dante technology is the most popular AoIP solution by far.
- [Ravenna](https://www.ravenna-network.com/) - Second most popular AoIP solution, which is more open than Dante.

## Standards

- [AES67](https://www.aes.org/publications/standards/search.cfm?docID=96), public [draft](https://aes2.org/standards-blog/call-for-comment-on-draft-revised-aes67-xxxx-high-performance-streaming-audio-over-ip-interoperability/) - The open standard to den Audio over IP.
- [NMOS](https://github.com/AMWA-TV/nmos) - REST APIs for controlling network media devices.
- [SMPTE ST 2110-30](https://en.wikipedia.org/wiki/SMPTE_2110) - AES67 based audio transport in a video stream (TODO: Find better source).

## Education

- [Dante Certification](https://www.getdante.com/resources/training/dante-certification-program/) - Understanding Dante helps understanding AoIP. The training requires an account. I recommend lv 1 and lv 2.
- [Ravenna Ressources](https://www.ravenna-network.com/resources/) - Webinars and slides by Andreas Hildebrand about Ravenna, AES67, SMPTE 2110, PTP and IPMX.
- [Connecting Dante with AES67](https://download.yamaha.com/files/tcm:39-868466/) - Setting up AES67 from a Dante device isn't very straight forward, here's a guide from Yamaha as an example.


## Unverified

- List of things that sound good, but I was unable to try out or assess. Will vanish if this list will ever mature.
- [PAM](https://github.com/martim01/pam) - Open source, AES67 capable audio monitor.

