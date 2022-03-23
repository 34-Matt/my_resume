---
title: "Robust Motion Mapping Between Human and Humanoids Using CycleAutoencoder"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Lingfeng Tao
- Xiaoli Zhang

date: "2021-12-06"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-09"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings in *IEEE International Conference on Robotics and Biomimetics*
publication_short: Proc. in *IEEE ROBIO*

abstract: Teleoperation needs accurate and robust motion mapping between human and humanoid motion to generate intuitive robot control with human-like motion. Data-driven methods are often deployed as it can result in intuitive, real time motion mapping. When using these methods, the common focus is on the accuracy of the motion mapping model. However, effort needs to be put into making the mapping model robust in face of noisy or incomplete dataset. In other words, the model needs to learn the generalizable mapping rules, not just be accurate in predicting the training data. To create a robust and accurate model for motion mapping, we developed the novel CycleAutoencoder method. This method simultaneously trains two autoencoders using traditional losses, mixed losses, and cycle losses. These losses allow the autoencoders to reconstruct the motion mutually between humans and humanoids. This allows the method to learn the mapping with improved accuracy and robustness compared to training a traditional autoencoder. The results of human subject involved experiments demonstrated that the CycleAutoencoder method can achieve both accuracy and robustness for the mapping compared with other autoencoder-based mapping methods.

# Summary. An optional shortened abstract.
summary: Using a new transferability metric with our new, cyclically designed autoencoder, we developed a framework for producing more robust motion mapping for intuitive robot teleoperation.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://drive.google.com/file/d/1hC5YNAN98tpePSI3LJxzgdS41pC7x1oA/view?usp=sharing'
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
  caption: 'The CycleAutoencoder Model' 
  focal_point: ""
  preview_only: false

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
