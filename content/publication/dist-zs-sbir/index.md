---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Zero-Shot Sketch-Based Image Retrieval with Structure-aware Asymmetric Disentanglement"
authors: 
- Jiangtong Li
- Zhixin Ling
- Li Niu
- Liqing Zhang.
date: 2022-03-25T14:01:16+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-03-25T14:01:16+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Computer Vision and Image Understanding (CVIU 2022)
publication_short: "CVIU 2022"

abstract: "The goal of Sketch-Based Image Retrieval (SBIR) is using free-hand sketches to retrieve images of the same category from a natural image gallery. However, SBIR requires all test categories to be seen during training, which cannot be guaranteed in real-world applications. So we investigate more challenging Zero-Shot SBIR (ZS-SBIR), in which test categories do not appear in the training stage. After realizing that sketches mainly contain structure information while images contain additional appearance information, we attempt to achieve structure-aware retrieval via asymmetric disentanglement. For this purpose, we propose our STRucture-aware Asymmetric Disentanglement (STRAD) method, in which image features are disentangled into structure features and appearance features while sketch features are only projected to structure space. Through disentangling structure and appearance space, bi-directional domain translation is performed between the sketch domain and the image domain. Extensive experiments demonstrate that our STRAD method remarkably outperforms state-of-the-art methods on three large-scale benchmark datasets."

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

url_pdf: 
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
  caption: "Model Structure"
  focal_point: "Right"
  preview_only: True

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