---
title: 'Fuzzware: Using Precise MMIO Modeling for Effective Firmware Fuzzing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tobias Scharnowski
  - Nils Bars 
  - Moritz Schloegel
  - Eric Gustafson
  - Marius Muench
  - Giovanni Vigna
  - Christopher Kruegel
  - Thorsten Holz 
  - admin



# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2022'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *31st USENIX Security Symposium*
# publication_short: In *ICW*

abstract: As embedded devices are becoming more pervasive in our everyday lives, they turn into an attractive target for adversaries. Despite their high value and large attack surface, applying automated testing techniques such as fuzzing is not straightforward for such devices. As fuzz testing firmware on constrained embedded devices is inefficient, state-of-the-art approaches instead opt to run the firmware in an emulator (through a process called re-hosting). However, existing approaches either use coarse-grained static models of hardware behavior or require manual effort to re-host the firmware. We propose a novel combination of lightweight program analysis, re-hosting, and fuzz testing to tackle these challenges. We present the design and implementation of Fuzzware, a software-only system to fuzz test unmodified monolithic firmware in a scalable way. By determining how hardware-generated values are actually used by the firmware logic, Fuzzware can automatically generate models that help focusing the fuzzing process on mutating the inputs that matter, which drastically improves its effectiveness. We evaluate our approach on synthetic and real-world targets comprising a total of 19 hardware platforms and 77 firmware images. Compared to state-of-the-art work, Fuzzware achieves up to 3.25 times the code coverage and our modeling approach reduces the size of the input space by up to 95.5%. The synthetic samples contain 66 unit tests for various hardware interactions, and we find that our approach is the first generic re-hosting solution to automatically pass all of them. Fuzzware discovered 15 completely new bugs including bugs in targets which were previously analyzed by other works; a total of 12 CVEs were assigned.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [embedded, fuzzing]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.usenix.org/system/files/sec22-scharnowski.pdf'
url_code: 'https://github.com/fuzzware-fuzzer/fuzzware'
url_dataset: ''
url_poster: ''
url_project: ''
url_source: 'https://www.usenix.org/conference/usenixsecurity22/presentation/scharnowski'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
# caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
