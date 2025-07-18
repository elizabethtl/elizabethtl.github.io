---
layout: single
title: Research
permalink: /research/
author_profile: true
toc: true
toc_sticky: true
---



# Research

## [Context Matters](../_posts/2025-07-16-context-matters.md) (SCA)

[Context Matters: Qualitative Insights into Developers’ Approaches and Challenges with Software Composition Analysis](https://www.usenix.org/conference/usenixsecurity25/presentation/lin-elizabeth)  
*__Elizabeth Lin__, Sparsha Gowda, <a href="https://enck.org/" class="author-link">William Enck</a>, and <a href="https://dwermke.com/" class="author-link">Dominik Wermke</a>* 

*To appear at the 2025 USENIX Security Symposium*

Software Composition Analysis (SCA) is often discussed in software supply chain security. 
SCA tools are used to identify vulnerabilities in third-party software. 
Some prior work have looked into how SCA tools perform.
However, there lacks an understanding of user experience with SCA tools.

We talked to 20 industry professionals and discovered *a lack of context* along the entire SCA deployment process.
In short, we find the following:
- SCA alerts are too generic and lack **infrastructure**, **network configuration**, **reachability**, and **exploitability** context.
- Integrating SCA tools into pipelines can halt development if builds are failed on every SCA alert.
- Scaling SCA across multiple teams and projects can result in communication overhead.
Large organizations develop custom tooling around SCA tool results to better manage and triage the alerts.


Read the [full paper here](../assets/context-matters.pdf), or read this [blog post](../_posts/2025-07-16-context-matters.md) I wrote that summarizes our paper and findings.

**See my talk @ VulnCon 2025 [here](https://youtu.be/g-SYh9v3W5Y?feature=shared)**



## [UntrustIDE](../_posts/2024-03-07-untrustide.md) (VSCode extensions)

[UntrustIDE: Exploiting Vulnerabilities in VS Code Extensions](https://www.ndss-symposium.org/ndss-paper/untrustide-exploiting-weaknesses-in-vs-code-extensions/)  
*__Elizabeth Lin__, <a href="https://igibek.com/" class="author-link">Igibek Koishybayev</a>, Trevor Dunlap, <a href="https://enck.org/" class="author-link">William Enck</a>, and <a href="https://www.kapravelos.com/" class="author-link">Alexandros Kapravelos</a>.* 

**Distinguished Paper Award** @ NDSS Symposium 2024

VS Code is the most popular IDE for developers. In this study we take a look at its extension ecosystem, the marketplace.
As the first ecosystem-wide research, we proposed a threat model and identified vulnerabilities within the ecosystem with taint analysis using [CodeQL](https://codeql.github.com/).
With our [custom CodeQL queries](https://github.com/s3c2/UntrustIDE/), we identified and verified vulnerabilities and their proof-of-concept exploits for 21 extensions, impacting 6 million users.


Don't want to read the [full paper](../assets/UntrustIDE.pdf)? My short [blog post](/untrustide) includes an overview of our methods, findings, and an example of how a vulnerable data flow in an extension could lead to code execution.

**Also see my talk at NDSS [here](https://www.youtube.com/watch?v=QQ9W2FM1X-w)**

## Abandabot

[Designing Abandabot: When Does Open Source Dependency Abandonment Matter?](https://courtney-e-miller.github.io/papers/designingAbandabot.pdf)  
*<a href="https://courtney-e-miller.github.io/" class="author-link">Courtney Miller</a>\*, <a href="https://hehao98.github.io/" class="author-link">Hao He</a>\*, Weigen Chen, __Elizabeth Lin__, <a href="https://www.cs.cmu.edu/~cyang3/" class="author-link">Chenyang Yang</a>, <a href="https://bvasiles.github.io/" class="author-link">Bogdan Vasilescu</a>, and <a href="https://www.cs.cmu.edu/~ckaestne/" class="author-link">Christian Kästner</a>*

We perform a need-finding interview study with 22 open source maintainers to explore what makes the abandonment of certain dependencies impactful to their project, as well as their information needs and design requirements for such an automated notification tool.
We build an LLM-based classifier based on: *depth of integration*, *availability of alternatives*, *importance of the functionality*, and *external environmental pressures*.

Our results show that the classifier is effective at predicting whether a dependency’s abandonment would be impactful to a project.

## Software Bill of Materials (SBoMs)

[Software Bills of Materials Are Required. Are We There Yet?](https://ieeexplore.ieee.org/abstract/document/10102604?casa_token=NVD2tRbNNHUAAAAA:vbRR4xuGYuPFZgiUntR7TiZZDW-yY6juXO3XAYDyFKAPEBQ037xjRgYy6BfhP7DUrx5zgQP27g) IEEE Security & Privacy 21, no. 2 (2023): 82-88.  
*<a href="https://www.nzahan.net/" class="author-link">Nusrat Zahan</a>, __Elizabeth Lin__, <a href="https://sites.google.com/view/mahzabintamanna/home" class="author-link">Mahzabin Tamanna</a>, <a href="https://enck.org/" class="author-link">William Enck</a>, and <a href="https://www.csc.ncsu.edu/people/lawilli3" class="author-link">Laurie Williams</a>.* 

A grey literature review was conducted on articles relating to the benefits and challenges of SBoMs.

The top 5 benefits and challenges are outlined in the above article.


## VFCFinder

[VFCFinder: Seamlessly Pairing Security Advisories and Patches](https://arxiv.org/abs/2311.01532)  
*Trevor Dunlap, __Elizabeth Lin__, <a href="https://enck.org/" class="author-link">William Enck</a>, and <a href="https://bradreaves.net/" class="author-link">Bradley Reaves</a>.*

A tool that generated the top 5 vulnerable fixing commits for a given security advisory.

VFCFinder used to backfill over 300 missing VFCs in the GitHub Security Advisory (GHSA) database.





<!-- ## Publications -->
<!-- pub -->
