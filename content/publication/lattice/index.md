---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Lattice-Based Transformer Encoder for Neural Machine Translation,"
authors:
- Fengshun Xiao*
- <b> <i> Jiangtong Li* </i> </b>
- Hai Zhao
- Rui Wang
- Kehai Chen.
date: 2020-03-29T16:31:57+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-29T16:31:57+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 57th Annual Meeting of the Association for Computational Linguistics (ACL 2019)"
publication_short: ""

abstract: "Neural machine translation (NMT) takes deterministic sequences for source representations. However, either word- level or subword-level segmentations have multiple choices to split a source sequence with different word segmentors or different subword vocabulary sizes. We hypothesize that the diversity in segmentations may affect the NMT performance. To integrate different segmentations with the state-of-the-art NMT model, Transformer, we propose lattice-based encoders to explore effective word or subword representation in an automatic way during training. We propose two methods: 1) lattice positional encoding and 2) lattice-aware self-attention. These two methods can be used together and show complementary to each other to further improve translation performance. Experiment results show superiorities of lattice-based encoders in word-level and subword-level representations over conventional Transformer encoder."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/1906.01282.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
