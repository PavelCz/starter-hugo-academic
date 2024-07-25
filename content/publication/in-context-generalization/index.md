---
title: 'In-Context Generalization to New Tasks From Unlabeled Observation Data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Anthony Liang
  - admin
  - Yutai Zhou
  - Stephen Tu
  - Erdem Bıyık

date: '2024-07-27T00:00:00Z'
# doi: '10.21437/Interspeech.2022-108'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-27T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In *1st ICML Workshop on In-Context Learning*
publication_short: In *1st ICL Workshop at ICML 2024*

abstract: "Large pretrained models in natural language processing and computer vision have achieved impressive capabilities by training on vast internet-scale corpora. However, for sequential decision-making agents, such as robots and other autonomous systems, it is difficult and expensive to collect large amounts of expert demonstrations hindering their ability to learn new tasks efficiently. Leveraging unannotated internet videos as a resource, we propose an approach to train a generalist agent capable of few-shot adaptation to new tasks without fine-tuning. Our method, Prompt-DTLA, learns a latent action model to annotate video sequences with latent actions that enables training an in-context causal transformer policy on these annotated trajectories. At inference, the agent can generalize to new, unseen tasks using few-shot in-context demonstrations without additional fine-tuning. Prompt-DTLA offers a potential solution for scaling robot learning with free, internet-scale data rather than expensive human demonstrations, enabling generalist agents to learn new tasks from unlabelled data sources."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=M1v4y0rbFS'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Test'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
