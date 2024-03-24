---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Modeling Multi-turn Conversation with Deep Utterance Aggregation"
authors: 
- Zhuosheng Zhang *
- Jiangtong Li *
- Pengfei Zhu
- Hai Zhao
- Gongshen Liu.
date: 2018-08-26T14:01:16+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-29T14:01:16+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 27th International Conference on Computational Linguistics (COLING 2018)
publication_short: "COLING 2018"

abstract: "Multi-turn conversation understanding is a major challenge for building intelligent dialogue systems. This work focuses on retrieval-based response matching for multi-turn conversation whose related work simply concatenates the conversation utterances, ignoring the interactions among previous utterances for context modeling. In this paper, we formulate previous utterances into context using a proposed deep utterance aggregation model to form a fine-grained context representation. In detail, a self-matching attention is first introduced to route the vital information in each utterance. Then the model matches a response with each refined utterance and the final matching score is obtained after attentive turns aggregation. Experimental results show our model outperforms the state-of-the-art methods on three multi-turn conversation benchmarks, including a newly introduced e-commerce dialogue corpus."

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
url_code: https://github.com/Jiangtong-Li/DeepUtteranceAggregation
url_dataset: https://drive.google.com/file/d/154J-neBo20ABtSmJDvm7DK0eTuieAuvw/view?usp=sharing
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