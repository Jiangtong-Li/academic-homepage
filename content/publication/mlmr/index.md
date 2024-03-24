---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Multi-Level Region Matching for Fine-Grained Sketch-Based Image Retrieval"
authors: 
- Zhixin Ling
- Zhen Xing
- Jiangtong Li
- Li Niu.
date: 2022-10-10T14:01:16+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-08-10T14:01:16+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 30th ACM International Conference on Multimedia (ACM MM 2022)
publication_short: "ACM MM 2022"

abstract: "Fine-Grained Sketch-Based Image Retrieval (FG-SBIR) is to use free-hand sketches as queries to perform instance-level retrieval in an image gallery. Existing works usually leverage only high-level information and perform matching in a single region. However, both low-level and high-level information are helpful to establish fine-grained correspondence. Besides, we argue that matching different regions between each sketch-image pair can further boost model robustness. Therefore, we propose Multi-Level Region Matching (MLRM) for FG-SBIR, which consists of two modules: a Discriminative Region Extraction module (DRE) and a Region and Level Attention module (RLA). In DRE, we propose Light-weighted Attention Map Augmentation (LAMA) to extract local feature from different regions. In RLA, we propose a transformer-based attentive matching module to learn attention weights to explore different importance from different image/sketch regions and feature levels. Furthermore, to ensure that the geometrical and semantic distinctiveness is well modeled, we also explore a novel LAMA overlapping penalty and a local region-negative triplet loss in our proposed MLRM method. Comprehensive experiments conducted on five datasets (*i.e*., Sketchy, QMUL-ChairV2, QMUL-ShoeV2, QMUL-Chair, QMUL-Shoe) demonstrate effectiveness of our method."

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