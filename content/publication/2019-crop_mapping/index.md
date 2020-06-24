---
title: "Smallholder maize area and yield mapping at national scales with Google Earth Engine"
authors:
- Zhenong Jin
- George Azzari
- admin
- Stefania Di Tommaso
- Stephen Aston 
- Marshall Burke
- David B. Lobell
date: "2019-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-09-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Remote Sensing of Environment, 228*"
publication_short: "RSE"

abstract: "Accurate measurements of maize yields at field or subfield scales are useful for guiding agronomic practices and investments and policies for improving food security. Data on smallholder maize systems are currently sparse, but satellite remote sensing offers promise for accelerating learning about these systems. Here we document the use of Google Earth Engine (GEE) to build “wall-to-wall” 10 m resolution maps of (i) cropland presence, (ii) maize presence, and (iii) maize yields for the main 2017 maize season in Kenya and Tanzania. Mapping these outcomes at this scale is extremely challenging because of very heterogeneous landscapes, lack of cloud-free satellite imagery, and the low quantity of quality ground-based data in these regions.\n

First, we computed seasonal median composites of Sentinel-1 radar backscatter and Sentinel-2 optical reflectance measures for each pixel in the region, and used them to build both crop/non-crop and maize/non-maize Random Forest (RF) classifiers. Several thousand crop/non-crop labels were collected through an in-house GEE labeler, and thousands of crop type labels from the 2015–2017 growing seasons were obtained from various sources. Results show that the crop/non-crop classifier successfully identified cropland with over 85% out-of-sample accuracy in both countries, with Sentinel-1 being particularly useful for prediction. Among the cropped pixels, the maize/non-maize classier had an accuracy of 79% in Tanzania and 63% in Kenya.\n

To map maize yields, we build on past work using a scalable crop yield mapper (SCYM) that utilizes simulations from a crop model to train a regression that predicts yields from observations. Here we advance past approaches by (i) grouping simulations by Global Agro-Environmental Stratification (GAES) zones across the two countries, in order to account for landscape heterogeneity, (ii) utilizing gridded datasets on soil and sowing and harvest dates to setup model simulations in a scalable way; and (iii) utilizing all available satellite observations during the growing season in a parsimonious way by using harmonic regression fits implemented in GEE. SCYM estimates were able to capture about 50% of the variation in the yields at the district level in Western Kenya as measured by objective ground-based crop cuts.\n

Finally, we illustrated the utility of our yield maps with two case studies. First, we document the magnitude and interannual variability of spatial heterogeneity of yields in each district, and how it varies for different parts of the region. Second, we combine our estimates with recently released soil databases in the region to investigate the most important soil constraints in the region. Soil factors explain a high fraction (72%) of variation in predicted yields, with the predominant factor being soil nitrogen levels. Overall, this study illustrates the power of combining Sentinel-1 and Sentinel-2 imagery, the GEE platform, and advanced classification and yield mapping algorithms to advance understanding of smallholder agricultural systems."

# Summary. An optional shortened abstract.
summary: We created maps of (i) cropland presence, (ii) maize presence, and (iii) maize yields for the 2017 maize season in Kenya and Tanzania.

tags:
- Crop Mapping
- Remote Sensing
- Google Earth Engine
- Development
- Machine Learning
featured: true

links:
- name: "RSE"
  url: "https://www.sciencedirect.com/science/article/abs/pii/S0034425719301610?via%3Dihub"
url_pdf: https://web.stanford.edu/~mburke/papers/jin%20et%20al%202019.pdf
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: []
---
