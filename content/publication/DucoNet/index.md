---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Deep Image Harmonization in Dual Color Spaces"
authors: 
- Linfeng Tan
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

abstract: "Image harmonization is an essential step in image composition that adjusts the appearance of composite foreground to address the inconsistency between foreground and background. Existing methods primarily operate in correlated 𝑅𝐺𝐵 color space, leading to entangled features and limited representation ability. In contrast, decorrelated color space (*e.g.*, 𝐿𝑎𝑏) has decorrelated channels that provide disentangled color and illumination statistics. In this paper, we explore image harmonization in dual color spaces, which supplements entangled 𝑅𝐺𝐵 features with disentangled 𝐿, 𝑎, 𝑏 features to alleviate the workload in harmonization process. The network comprises a 𝑅𝐺𝐵 harmonization backbone, an 𝐿𝑎𝑏 encoding module, and an 𝐿𝑎𝑏 control module. The backbone is a U-Net network translating composite image to harmonized image. Three encoders in 𝐿𝑎𝑏 encoding module extract three control codes independently from 𝐿, 𝑎, 𝑏 channels, which are used to manipulate the decoder features in harmonization backbone via 𝐿𝑎𝑏 control module. Our code and model are available at https://github.com/bcmi/DucoNet-Image-Harmonization."

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