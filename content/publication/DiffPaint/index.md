---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Painterly Image Harmonization using Diffusion Model"
authors: 
- Lingxiao Lu
- Jiangtong Li
- Li Niu
- Liqing Zhang.
date: 2023-10-03T14:01:16+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-10-03T14:01:16+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 31th ACM International Conference on Multimedia (ACM MM 2023)
publication_short: "ACM MM 2023"

abstract: "Painterly image harmonization aims to insert photographic objects into paintings and obtain artistically coherent composite images. Previous methods for this task mainly rely on inference optimization or generative adversarial network, but they are either very time-consuming or struggling at fine control of the foreground objects (*e.g.*, texture and content details). To address these issues, we focus on feed-forward diffusion models and propose a novel Stable diffusion with Dual Encoder fusion network (SDENet), which includes a lightweight adaptive encoder and a Dual Encoder Fusion (DEF) module. Specifically, the adaptive encoder and the DEF module first stylize foreground features through aggregating relevant style information from background within each encoder. Then, the stylized foreground features from both encoders are combined to provide sufficient guidance for the harmonization process. During training, besides the noise loss in diffusion model, we additionally employ two style losses, *i.e.*, AdaIN style loss and contrastive style loss, aiming to balance the trade-off between style migration and content preservation. Compared with the state-of-the-art models from related fields, our SDENet can stylize the foreground more sufficiently and simultaneously retain finer content on the benchmark datasets."

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