---
layout: page
title: Layr
subtitle: A decentralized cloud storage system
use-site-title: true
---

[Layr](https://github.com/layr-team/Layr) is a decentralized (p2p) cloud storage system built atop Kademlia DHT that enforces data integrity, privacy, and availability through proofs of retrievability, redundancy, and encryption, with cryptocurrency-based incentive scheme

{: .center}
[![Audit Patch Process](/img/demo2.png)](https://youtu.be/dMDRUxPyIkw)

---
<h2> Table of Contents </h2>

1. ToC
{:toc}

---
## Preface

This document is the official case study of the Layr project. Layr is a decentralized cloud storage system. Layr is an ongoing project and we encourage readers to contribute on GitHub. This paper will serve not only as a narrative detailing the problems and solutions we encountered while building Layr, but as an introduction to the problem space of decentralized cloud storage in general.

Software development is an iterative process. We built, and continue to build, Layr in an iterative fashion. The space between a naive and optimal solution is filled with incremental improvements; our development process steps through these increments. In lieu of this, we do not claim to have developed the most optimal system, but we do claim to have a strong understanding of the problem-and solution-space, which provides us with a clear direction forward. We hope that this document will convey that understanding and enable readers who are unfamiliar with the problem space to build their own decentralized cloud storage system.

---
## Introduction to cloud storage
Many of us possess valuable information: information that we do not want to lose. We also know that the personal devices which store this information are subject to failure, and, consequently, data loss. 

### The importance of cloud storage
There are a couple possible solutions to the problem of data loss. One solution is to purchase a set of dedicated servers to host your data and set them up in your home or office. You will have to maintain the hardware of the servers or hire someone to do it for you. Another solution is to carry around compact storage devices, such as a thumb drive or external hard drive. You will have to physically have the device in order to retrieve your data, but at least it’s portable and doesn’t require maintenance. A third option is to store your data on the cloud. With cloud based storage, you no longer need to look after the physical devices that are storing your data. Your ability to retrieve your data is decoupled from the locality of the physical device storing that data. Further, you only need to pay for the storage that you actually use. Cloud storage certainly confers many benefits for anyone who values cost-effectiveness, availability, and safety of their data.

### Centralized cloud storage and its problems
Large cloud storage providers (CSPs) have emerged out of the increasing need to store and retrieve data easily, quickly, and cheaply. Some prime examples of these CSPs are DropBox, Google Drive, and Amazon S3. Though the specific features, user experiences and software differ amongst these providers, they have at least one thing in common: they, as service providers, not only store users’ files, but are entrusted by users to secure those files from privacy breaches, corruption, and loss. In other words, if the storage provider does not take steps to ensure data integrity, privacy, and basic availability, nobody will; in fact, nobody can. The ability to provide these features are centralized to a single provider.

---
## Building Layr

---
## Works cited

---
## Our Team

We are all available for new opportunities, feel free to reach out!

{% include team.html %}
