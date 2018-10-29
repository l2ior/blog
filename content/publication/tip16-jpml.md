+++
title = "Joint Patch and Multi-label Learning for Facial Expression Analysis"
date = 2016-05-18
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Kaili Zhao", "Wen-Sheng Chu", "Fernando De la Torre", "Jeffrey F. Cohn", "Honggang Zhang"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*IEEE Transactions on Image Processing*"
publication_short = "*TIP*"

# Abstract and optional shortened version.
abstract = "Most AU detection methods use one-versus-all classifiers without considering dependencies between features or AUs. In this paper, we introduce a joint patch and multi-label learning (JPML) framework that models the structured joint dependence behind features, AUs, and their interplay. In particular, JPML leverages group sparsity to identify important facial patches, and learns a multi-label classifier constrained by the likelihood of co-occurring AUs.  To describe such likelihood, we derive two AU relations, positive correlation and negative competition, by statistically analyzing more than 350,000 video frames annotated with multiple AUs.  We evaluate JPML on three benchmark datasets CK+, BP4D, and GFT, using within- and cross-dataset scenarios. In four of five experiments, JPML achieved the highest averaged F1 scores in comparison with baseline and alternative methods that use either patch learning or multi-label learning alone."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "http://www.humansensing.cs.cmu.edu/sites/default/files/07471506.pdf"
url_preprint = ""
url_code = "https://github.com/zkl20061823/JPML"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
