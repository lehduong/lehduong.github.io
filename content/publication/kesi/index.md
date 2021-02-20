---
title: "Paying more attention to snapshots of Iterative Pruning: Improving Model Compression via Ensemble Distillation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Trung-Nhan Vo
  - Nam Thoai

# Author notes (optional)

date: "2020-8-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In The 31st British Machine Vision Virtual Conference
publication_short: In *BMVC* (2020)

abstract: Network pruning is one of the most dominant methods for reducing the heavy inference cost of deep neural networks. Existing methods often iteratively prune networks to attain high compression ratio without incurring significant loss in performance. However, we argue that conventional methods for retraining pruned networks (i.e., using small, fixed learning rate) are inadequate as they completely ignore the benefits from snapshots of iterative pruning. In this work, we show that strong ensembles can be constructed from snapshots of iterative pruning, which achieve competitive performance and vary in network structure. Furthermore, we present simple, general and effective pipeline that generates strong ensembles of networks during pruning with large learning rate restarting, and utilizes knowledge distillation with those ensembles to improve the predictive power of compact models. In standard image classification benchmarks such as CIFAR and Tiny-Imagenet, we advance state-of-the-art pruning ratio of structured pruning by integrating simple l1-norm filters pruning into our pipeline. Specifically, we reduce 75-80% of total parameters and 65-70% MACs of numerous variants of ResNet architectures while having comparable or better performance than that of original networks.

# Summary. An optional shortened abstract.
summary: We propose KESI - a method that combine knowledge distillation, network pruning and ensemble learning to improve the performance of compact networks.

tags: [Efficient Deep Learning, Network Pruning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: "https://www.bmvc2020-conference.com/assets/papers/0817.pdf"
url_code: "https://github.com/lehduong/kesi"
url_dataset: ""
url_poster: "https://www.bmvc2020-conference.com/conference/papers/paper_0817.html"
url_project: ""
url_slides: ""
url_source: ""
url_video: "https://www.bmvc2020-conference.com/conference/papers/paper_0817.html"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.

# UNCOMMENT THIS
# image:
#   caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - KESI
# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.

#slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->

Supplementary can be founded [here](https://www.bmvc2020-conference.com/assets/supp/0817_supp.zip)
