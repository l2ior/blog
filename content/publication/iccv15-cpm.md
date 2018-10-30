+++
title = "Confidence Preserving Machine for Facial Action Unit Detection"
date = 2015-12-01
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jiabei Zeng", "Wen-Sheng Chu", "Fernando De la Torre", "Jeffrey F. Cohn", "Xiong Zhang"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *IEEE International Conference on Computer Vision*"
publication_short = "In *ICCV*"
add_note = "(Spotlight)"

# Abstract and optional shortened version.
abstract = "Varied sources of error contribute to the challenge of facial action unit detection. Previous approaches address specific and known sources. To address the ubiquity of error, we propose a Confident Preserving Machine (CPM) that follows an easy-tohard classification strategy. During training, CPM learns two confident classifiers. A confident positive classifier separates easily identified positive samples from all else; a confident negative classifier does same for negative samples.  During testing, CPM then learns a person-specific classifier using “virtual labels” provided by confident classifiers. To evaluate CPM, we compared it with a baseline single-margin classifier and stateof-the-art semi-supervised learning, transfer learning, and boosting methods in three datasets of spontaneous facial behavior.  With few exceptions, CPM outperformed baseline and state-of-the art methods."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = "teaser/teaser_cpm.jpg"

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
url_pdf = "https://www.ri.cmu.edu/pub_files/2015/12/cpm_final.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = "video/cpm.mp4"
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
