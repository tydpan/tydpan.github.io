---
title: 'Learning with Free Object Segments for Long-Tailed Instance Segmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Cheng_Zhang
  - admin
  - Tianle_Chen
  - Jike_Zhong
  - Wenjin_Fu
  - Wei_Lun_Chao

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-02-22'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-02-22'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of European Conference on Computer Vision 2022*
publication_short: In *ECCV 2022*

abstract: "One fundamental challenge in building an instance segmen- tation model for a large number of classes in complex scenes is the lack of training examples, especially for rare objects. In this paper, we ex- plore the possibility to increase the training examples without laborious data collection and annotation. We find that an abundance of instance segments can potentially be obtained freely from object-centric images, according to two insights: (i) an object-centric image usually contains one salient object in a simple background; (ii) objects from the same class often share similar appearances or similar contrasts to the background. Motivated by these insights, we propose a simple and scalable frame- work FreeSeg for extracting and leveraging these “free” object fore- ground segments to facilitate model training in long-tailed instance seg- mentation. Concretely, we investigate the similarity among object-centric images of the same class to propose candidate segments of foreground instances, followed by a novel ranking of segment quality. The resulting high-quality object segments can then be used to augment the exist- ing long-tailed datasets, *e.g.*, by copying and pasting the segments onto the original training images. Extensive experiments show that FreeSeg yields substantial improvements on top of strong baselines and achieves state-of-the-art accuracy for segmenting rare object categories."


Summary: ''
# summary: We propose NORCAL, Normalized Calibration for long-tailed object detection and instance segmentation, a simple and straightforward recipe that reweighs the predicted scores of each class by its training sample size.
# summary: In *NeurIPS 2021*

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: 'https://arxiv.org/abs/2202.11124'

url_pdf: 'https://arxiv.org/pdf/2202.11124.pdf'
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
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
