---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Video Semantic Segmentation via Sparse Temporal Transformer,"
authors:
- Jiangtong Li
- Wentao Wang
- Junjie Chen
- Li Niu
- Jianlou Si
- Chen Qian
- Liqing Zhang
date: 2021-10-19T16:31:57+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-10-19T16:31:57+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 29th ACM International Conference on Multimedia (ACM MM 2021)"
publication_short: "ACM MM 2021"

abstract: "Currently, video semantic segmentation mainly faces two challenges: 1) the demand of temporal consistency; 2)  the balance between segmentation accuracy and inference efficiency. For the first challenge, existing methods usually use optical flow to capture the temporal relation in consecutive frames and maintain the temporal consistency, but the low inference speed by means of optical flow limits the real-time applications. For the second challenge, flow-based key frame warping is one mainstream solution. However, the unbalanced inference latency of flow-based key frame warping makes it unsatisfactory for real-time applications. Considering the segmentation accuracy and inference efficiency, we propose a novel Sparse Temporal Transformer (STT) to bridge temporal relation among video frames adaptively, which is also equipped with query selection and key selection. The key selection and query selection strategies are separately applied to filter out temporal and spatial redundancy in our temporal transformer.  Specifically, our STT can reduce the time complexity of temporal transformer by a large margin without harming the segmentation accuracy and temporal consistency. Experiments on two benchmark datasets, Cityscapes and Camvid, demonstrate that our method achieves the state-of-the-art segmentation accuracy and temporal consistency with comparable inference speed."

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
