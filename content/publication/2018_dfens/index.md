---
title: 'Defending Internet of Things Against Malicious Domain Names using D-FENS'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Aziz Mohaisen

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2018-10-25T00:00:00Z'
doi: 'https://doi.org/10.1109/SEC.2018.00051'

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In 2018 IEEE/ACM Symposium on Edge Computing (SEC)
#publication_short: 

abstract: Malicious domain names have long been pervasive in the global DNS (Domain Name System) infrastructure and lend themselves to undesirable activities such as phishing or even DNS-based attacks like distributed denial-of-service (DDoS) and DNS rebinding. With the rise and explosive growth of the Internet of Things (IoT), adversaries are exploiting these devices which typically lack security measures to launch DNS-based attacks through malicious domain names. Typical countermeasures against such malicious domain names employ blacklists and whitelists to determine which domain names should be resolved. While these domain lists offer fast lookup times, they require carefully curated and up-to-date information which tends to fall short of detecting newly-registered malicious domain names. In this work, we present a system called D-FENS (DNS Filtering & Extraction Network System) which works in tandem with blacklists and features a live DNS server and binary classifier to accurately predict unreported malicious domain names. The D-FENS classifier model operates at the character-level and leverages the use of deep learning architectures such as Convolutional Neural Networks (CNN) and Long Short-Term Memory networks (LSTM) for real-time classification which forgoes the need for feature-engineering typically associated with traditional machine learning approaches. Sourcing from free and open datasets, we evaluate our system and achieve a 0.95 area under the receiver operating characteristic curve for binary classification. By accurately predicting unreported malicious domain names in real-time, D-FENS prevents Internet-connected systems from unknowingly connecting to potentially malicious domain names.

# Summary. An optional shortened abstract.
#summary:  

tags: ['Conference']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
 - name: IEEE Link
   url: https://ieeexplore.ieee.org/abstract/document/8567696

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: '' #example
---

