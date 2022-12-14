---
# Documentation: https://wowchemy.com/docs/managing-content/

title: On Emulation-Based Network Intrusion Detection Systems
subtitle: ''
summary: ''
authors:
- Ali Abbasi
- Jos Wetzels
- Wouter Bokslag
- Emmanuele Zambon
- Sandro Etalle
tags: []
categories: []
date: '2014-01-01'
lastmod: 2022-10-12T14:00:04+02:00
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
publishDate: '2022-10-12T12:00:04.495347Z'
publication_types:
- '6'
abstract: Emulation-based network intrusion detection systems have been devised to
  detect the presence of shellcode in network traffic by trying to execute (portions
  of) the network packet payloads in an instrumented environment and checking the
  execution traces for signs of shellcode activity. Emulation-based network intrusion
  detection systems are regarded as a significant step forward with regards to traditional
  signature-based systems, as they allow detecting polymorphic (i.e., encrypted) shellcode.
  In this paper we investigate and test the actual effectiveness of emulation-based
  detection and show that the detection can be circumvented by employing a wide range
  of evasion techniques, exploiting weakness that are present at all three levels
  in the detection process. We draw the conclusion that current emulation-based systems
  have limitations that allow attackers to craft generic shellcode encoders able to
  circumvent their detection mechanisms.
publication: '*Research in Attacks, Intrusions and Defenses: 17th International Symposium,
  RAID 2014, Gothenburg, Sweden, September 17-19, 2014. Proceedings*'
doi: 10.1007/978-3-319-11379-1_19
links:
- name: URL
  url: https://doi.org/10.1007/978-3-319-11379-1_19
---
