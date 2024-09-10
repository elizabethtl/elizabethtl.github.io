---
layout: single
title: Research
permalink: /research/
author_profile: true
---

# Research

## SCA Usability

We are currently recruiting participants for a study on SCA (software composition analysis) tools.

More details [here](/sca-usability)

Feel free to contact me if interested!

## UntrustIDE

VS Code is the most popular IDE for developers. In this study we take a look at its extension ecosystem, the marketplace.

As the first ecosystem-wide research, we proposed a threat model and identified vulnerabilities within the ecosystem with taint analysis using [CodeQL](https://codeql.github.com/).

In total, we identified and verified vulnerabilities and their proof-of-concept exploits for 21 extensions, impacting 6 million users.

*Elizabeth Lin, Igibek Koishybayev, Trevor Dunlap, William Enck, and Alexandros Kapravelos.*
[UntrustIDE: Exploiting Vulnerabilities in VS Code Extensions](https://www.ndss-symposium.org/ndss-paper/untrustide-exploiting-weaknesses-in-vs-code-extensions/)

Don't want to read the full paper?  
My short [blog post](/untrustide) includes an overview of our methods, findings, and an example of how a vulnerable data flow in an extension could lead to code execution.

## Software Bill of Materials (SBoMs)

A grey literature review was conducted on articles relating to the benefits and challenges of SBoMs.

The top 5 benefits and challenges are outlined in the following article.

*Nusrat Zahan, Elizabeth Lin, Mahzabin Tamanna, William Enck, and Laurie Williams.* [Software Bills of Materials Are Required. Are We There Yet?](https://ieeexplore.ieee.org/abstract/document/10102604?casa_token=NVD2tRbNNHUAAAAA:vbRR4xuGYuPFZgiUntR7TiZZDW-yY6juXO3XAYDyFKAPEBQ037xjRgYy6BfhP7DUrx5zgQP27g) IEEE Security & Privacy 21, no. 2 (2023): 82-88.


## VFCFinder

A tool that generated the top 5 vulnerable fixing commits for a given security advisory.

VFCFinder used to backfill over 300 missing VFCs in the GitHub Security Advisory (GHSA) database.

*Trevor Dunlap, Elizabeth Lin, William Enck, and Bradley Reaves.*
[VFCFinder: Seamlessly Pairing Security Advisories and Patches](https://arxiv.org/abs/2311.01532)





<!-- ## Publications -->
<!-- pub -->
