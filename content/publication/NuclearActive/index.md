---
title: "An Active Learning Strategy for the Development of Data-Driven Reactor Models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Cliff Ghiglieri
- Michael Bowman
- admin
- Xiaoli Zhang
- Jeffery King

date: "2021-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings in *International Congress on Advances in Nuclear Power Plants*
publication_short: Proc. in *ICAPP*

abstract: There is a recent and growing interest in applying machine learning and artificial intelligence techniques to the monitoring and operation of nuclear reactor systems. One challenge posed by the application of machine learning techniques to nuclear reactor power systems is the need for a large and reliable set of data for the data-driven models tolearnfrom.Thus, in the near term, it is likely that machine learning models for nuclear systems will be built using physics-based simulation data.This poses an additional challenge – many reactor simulations are based on Monte Carlo methods, which can be computationally expensiveand include uncertainties inherent to Monte Carlo solutions. This project developed a machine learning model for the critical control rod positions in a sodium-cooled fast reactor, using an active learning model coupled to aMonte Carlo N-Particle (MCNP) physics-based model.Initial results indicate that including a selection filter in the activelearning routines based on a simple control rod worth curve can significantly reduce the required search space and improve the efficiency of the active learning process.

# Summary. An optional shortened abstract.
summary: We created a uncertainty-aware data-driven model to filter noise and reduce sensor uncertainty inside of a trigger reactor.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  caption: 'TREAT from Idaho National Laboratory' 
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
