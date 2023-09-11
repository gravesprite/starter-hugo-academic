---
title: "Towards Designing and Learning Piecewise Space-Filling Curves"
publication_types:
  - "1"
authors:
  - admin
  - Zheng Wang
  - Gao Cong
  - Cheng Long
  - Han Mao Kiah
  - Bin Cui
publication: PVLDB 2023
abstract: "To index multi-dimensional data, space-filling curves (SFCs) have been used to map the data to one dimension, and then a one-dimensional indexing method such as the B-tree is used to index the mapped data. The existing SFCs all adopt a single mapping scheme for the whole data space. However, a single mapping scheme often does not perform well on all the data space. In this paper, we propose a new type of SFC called piecewise SFCs, which adopts different mapping schemes for different data subspaces. Specifically, we propose a data structure called Bit Merging tree (BMTree), which can generate data subspaces and their SFCs simultaneously and achieve desirable properties of the SFC for whole data space. Furthermore, we develop a reinforcement learning based solution to build the BMTree, aiming to achieve excellent query performance. Extensive experiments show that our proposed method outperforms existing SFCs in terms of query performance."
draft: false
featured: true
image:
  filename: ""
  focal_point: Smart
  preview_only: true
date: 2023-04-17T08:18:00.000Z

url_code: "https://github.com/gravesprite/Learned-BMTree"
url_pdf: "publication/vldb23-lsfc/p1347-li.pdf"
url_slides: "ublication/vldb23-lsfc/slides_p1347-li.pdf"
---
