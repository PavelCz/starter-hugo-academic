---
title: 'Improving Reward Learning by Estimating Annotator Expertise'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Pavel Czempin
  - Rachel Freedman
  - Ellen Novoseller
  - Vernon Lawhern
  - Cameron Allen
  - Erdem Bıyık

date: '2025-06-07T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-06-07T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *RSS 2025 Workshop on Continual Robot Learning from Humans*
publication_short: In *RSS 2025 Workshop CRLH*

abstract: "Reinforcement learning from human feedback (RLHF) has been used successfully to teach robots tasks that are difficult to specify procedurally. However, feedback from human annotators can be suboptimal and noisy, decreasing accuracy and leading to potentially unsafe behavior. Furthermore, different human annotators may have varying context-dependent expertise. In this work, we study the feasibility of learning annotator expertise jointly with a reward model based on annotator feedback. As opposed to prior works that assume human annotators are perfect or that their expertise levels are known, our method performs RLHF training without these assumptions by estimating the expertise of every annotator given information about annotator identities in the data. We show that if annotators exhibit varying degrees of expertise, estimating annotator expertise improves the ranking accuracy of the learned reward functions. When the annotator's expertise depends on the context, our method shows limited success."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=LB9mzsdemd'
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
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
