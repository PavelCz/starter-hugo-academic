---
title: 'Speech is Silver, Silence is Golden: What do ASVspoof-trained Models Really Learn?'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Nicolas Müller
  - Franziska Dieckmann
  - admin
  - Roman Canals
  - Konstantin Böttinger
  - Jennifer Williams

date: '2021-09-01T00:00:00Z'
doi: '10.21437/ASVSPOOF.2021-9'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proc. 2021 Edition of the Automatic Speaker Verification and Spoofing Countermeasures Challenge*
publication_short: In *ASVspoof2021*

abstract: We present our analysis of a significant data artifact in the official 2019/2021 ASVspoof Challenge Dataset. We identify an uneven distribution of silence duration in the training and test splits, which tends to correlate with the target prediction label. Bonafide instances tend to have significantly longer leading and trailing silences than spoofed instances. In this paper, we explore this phenomenon and its impact in depth. We compare several types of models trained on a) only the duration of the leading silence and b) only on the duration of leading and trailing silence. Results show that models trained on only the duration of the leading silence perform particularly well, and achieve up to 85% percent accuracy and an equal error rate (EER) of 15.1%. At the same time, we observe that trimming silence during pre-processing and then training established antispoofing models using signal-based features leads to comparatively worse performance. In that case, EER increases from 3.6% (with silence) to 15.5% (trimmed silence). Our findings suggest that previous work may, in part, have inadvertently learned thespoof/bonafide distinction by relying on the duration of silence as it appears in the official challenge dataset. We discuss the potential consequences that this has for interpreting system scores in the challenge and discuss how the ASV community may further consider this issue. 

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.isca-speech.org/archive/pdfs/asvspoof_2021/muller21_asvspoof.pdf'
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
