---
title: 'MosaicOS: A Simple and Effective Use of Object-Centric Images for Long-Tailed Object Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Cheng Zhang
  - admin
  - Yandong Li
  - Hexiang Hu
  - Dong Xuan
  - Soravit Changpinyo
  - Boqing Gong
  - Wei-Lun Chao

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2021-02-17'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-02-17'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV) 2021*
publication_short: In *ICCV 2021*

abstract: "Many objects do not appear frequently enough in complex scenes (*e.g.*, certain handbags in living rooms) for training an accurate object detector, but are often found frequently by themselves (*e.g.*, in product images). Yet, these object-centric images are not effectively leveraged for improving object detection in scene-centric images. In this paper, we propose Mosaic of Object-centric images as Scene-centric images (MosaicOS), a simple and novel framework that is surprisingly effective at tackling the challenges of long-tailed object detection. Keys to our approach are three-fold: (i) pseudo scene-centric image construction from object-centric images for mitigating domain differences, (ii) high-quality bounding box imputation using the object-centric images' class labels, and (iii) a multi-stage training procedure. On LVIS object detection (and instance segmentation), MosaicOS leads to a massive 60% (and 23%) relative improvement in average precision for rare object categories. We also show that our framework can be compatibly used with other existing approaches to achieve even further gains. Our pre-trained models are publicly available at [MosaicOS](https://github.com/czhang0528/MosaicOS/)."


Summary: ''

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: 'https://arxiv.org/abs/2102.08884'

url_pdf: 'https://openaccess.thecvf.com/content/ICCV2021/papers/Zhang_MosaicOS_A_Simple_and_Effective_Use_of_Object-Centric_Images_for_ICCV_2021_paper.pdf'
url_code: 'https://github.com/czhang0528/MosaicOS/'
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
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
