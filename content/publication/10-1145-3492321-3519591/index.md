---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Nyx-Net: Network Fuzzing with Incremental Snapshots'
subtitle: ''
summary: ''
authors:
- Sergej Schumilo
- Cornelius Aschermann
- Andrea Jemmett
- Ali Abbasi
- Thorsten Holz
tags:
- software security
- testing
- fuzzing
categories: []
date: '2022-01-01'
lastmod: 2022-10-12T14:00:02+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-10-12T12:00:02.267803Z'
publication_types:
- '1'
abstract: Coverage-guided fuzz testing (\"fuzzing\") has become mainstream and we
  have observed lots of progress in this research area recently. However, it is still
  challenging to efficiently test network services with existing coverage-guided fuzzing
  methods. In this paper, we introduce the design and implementation of Nyx-Net, a
  novel snapshot-based fuzzing approach that can successfully fuzz a wide range of
  targets spanning servers, clients, games, and even Firefox's Inter-Process Communication
  (IPC) interface. Compared to state-of-the-art methods, Nyx-Net improves test throughput
  by up to 300x and coverage found by up to 70%. Additionally, Nyx-Net is able to
  find crashes in two of ProFuzzBench's targets that no other fuzzer found previously.
  When using Nyx-Net to play the game Super Mario, Nyx-Net shows speedups of 10--30x
  compared to existing work. Moreover, Nyx-Net is able to find previously unknown
  bugs in servers such as Lighttpd, clients such as MySQL client, and even Firefox's
  IPC mechanism---demonstrating the strength and versatility of the proposed approach.
  Lastly, our prototype implementation was awarded a $20.000 bug bounty for enabling
  fuzzing on previously unfuzzable code in Firefox and solving a long-standing problem
  at Mozilla.
publication: '*Proceedings of the Seventeenth European Conference on Computer Systems*'
doi: 10.1145/3492321.3519591
links:
- name: URL
  url: https://doi.org/10.1145/3492321.3519591
---
