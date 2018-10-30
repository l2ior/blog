+++
title = "Confidence Preserving Machine for Facial Action Unit Detection"
date = 2016-07-01
year = 2016
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
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*IEEE Transactions on Image Processing*"
publication_short = "*TIP*"

# Abstract and optional shortened version.
abstract = "To address learning with the hard AU samples (such as inter-personal variability, pose, and low intensity), we propose Confidence Preserving Machine (CPM).  CPM is a novel two-stage learning framework that combines multiple classifiers following an “easy-to-hard” strategy.  During the training stage, CPM learns two confident classifiers.  Each classifier focuses on separating easy samples of one class from all else, and thus preserves confidence on predicting each class. During the testing stage, the confident classifiers provide “virtual labels” for easy test samples. We also introduce two CPM extensions: iCPM that iteratively augments training samples to train the confident classifiers, and kCPM that kernelizes the original CPM model to promote nonlinearity. Experiments on four spontaneous datasets GFT, BP4D, DISFA, and RU-FACS illustrate the benefits of the proposed CPM models over baseline methods and state-of-the-art semisupervised learning and transfer learning methods."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = "teaser/teaser_cpm_tip.jpg"

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Journal"]

# Links (optional).
url_pdf = "https://www.ri.cmu.edu/pub_files/2016/7/cpm_final.pdf"
url_code = "#"
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
